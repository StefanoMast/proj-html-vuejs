<template>
  <footer>
      <div class="footer">
          <h2> Working <span>Process</span></h2>
          <div class="footer-container">
              <div class="footer-card">
                  <div class="footer-circle-card">
                      <div class="font-aw">
                          <i class="fa-solid fa-lightbulb"></i>
                      </div>
                      
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
              </div>
              <div class="footer-card">
                  <div class="footer-circle-card">
                      <i class="fa-solid fa-comment"></i>
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="footer-card">
                  <div class="footer-circle-card">
                      <i class="fas fa-cloud"></i>
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="footer-card">
                  <div class="footer-circle-card">
                      <i class="fas fa-pencil-alt"></i>
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>

          </div>
          
      </div>
  </footer>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>

.footer {
    width: 60%;
    margin: auto;
}

.footer h2 {
    text-align: center;
    margin: 3rem 0;
}

.footer-container {
    padding-bottom: 3rem;
    width: 80%;
    background-image: url(../assets/svg/svg-3.svg);
    background-repeat: no-repeat;
    margin: auto;
    display: flex;
}

.footer-card {
    width: calc(100%/4);
    margin-bottom: 1rem;
}

.footer-circle-card img {
    width: 100%;
    text-align: center;
}

.footer-circle-card {
    width: 100px;
    height: 100px;
    background-image: url(../assets/img/rbt-placeholder.jpg);
    border-radius: 100%;
    margin: 2rem auto;
    position: relative;
}

.footer-circle-card i {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #C0E1CF;
    font-size: 2rem;
}


</style>