<template>
  <section>
      <div class="section">
          <div class="section-arrow"><img src="../assets/svg/svg-2.svg" alt=""></div>
          <h2> Working <span>Process</span></h2>
          <div class="section-container">
              <div class="section-card">
                  <div class="section-circle-card">
                      <div class="font-aw">
                          <i class="fa-solid fa-lightbulb"></i>
                      </div>
                      
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
              </div>
              <div class="section-card">
                  <div class="section-circle-card">
                      <i class="fa-solid fa-comment"></i>
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="section-card">
                  <div class="section-circle-card">
                      <i class="fas fa-cloud"></i>
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="section-card">
                  <div class="section-circle-card">
                      <i class="fas fa-pencil-alt"></i>
                  </div>
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>

          </div>
          
      </div>
  </section>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>

.section {
    position: relative;
}

.section-arrow {
    width: 30px;
    height: 35px;
    margin: 2rem 1rem;
    padding: 0.3rem;
    text-align: center;
    background-color: #C0E1CF;
    position: absolute;
    bottom: 0;
    right: 0;
}

.section h2 {
    text-align: center;
    margin: 3rem 0;
    font-size: 3rem;
}

.section-container {
    padding-bottom: 3rem;
    width: 60%;
    background-image: url(../assets/svg/svg-3.svg);
    background-repeat: no-repeat;
    margin: auto;
    display: flex;
}

.section-card {
    width: calc(100%/4);
    margin-bottom: 1rem;
}

.section-circle-card img {
    width: 100%;
    text-align: center;
}

.section-circle-card {
    width: 100px;
    height: 100px;
    background-image: url(../assets/img/rbt-placeholder.jpg);
    border-radius: 100%;
    margin: 1rem auto 0.5rem;
    position: relative;
}

.section-circle-card i {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #C0E1CF;
    font-size: 2rem;
}



</style>