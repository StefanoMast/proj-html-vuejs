<template>
  <footer>
      <div class="footer">
          <h2> Working Process</h2>
          <div class="footer-container">
              <div class="footer-card">
                  <div class="footer-circle-card">
                      <img src="../assets/svg/svg-0.svg" alt="">
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="footer-card">
                  <div class="footer-circle-card">
                      <img src="../assets/svg/svg-0.svg" alt="">
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="footer-card">
                  <div class="footer-circle-card">
                      <img src="../assets/svg/svg-0.svg" alt="">
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="footer-card">
                  <div class="footer-circle-card">
                      <img src="../assets/svg/svg-0.svg" alt="">
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
    margin: auto;
    background-image: url(../assets/svg/svg-3.svg);
    background-repeat: no-repeat;
    display: flex;
}

.footer-card {
    width: calc(100%/4);
    border: 1px solid black;
    margin-bottom: 1rem;
}

.footer-circle-card img {
    width: 100%;
    text-align: center;
}

.footer-circle-card {
    width: 100px;
    height: 100px;
    background-color: bisque;
    border-radius: 100%;
    margin: 2rem auto;
}


</style>