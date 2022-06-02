<template>
  <section>
      <div class="section">
          <div class="section-arrow"><img src="../assets/svg/svg-2.svg" alt=""></div>
          <h2> Working <span>Process</span></h2>
          <div class="section-container">
            <div class="section-background">
              <div class="section-card">
                  <div class="section-circle-card" id="green">
                     <i class="fa-solid fa-lightbulb"></i>
                  </div>
                
                  <h4>First there is an idea</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
              </div>
              <div class="section-card">
                  <div class="section-circle-card" id="yellow">
                      <i class="fa-solid fa-comment"></i>
                  </div>
                  <h4>Then we talk about</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="section-card">
                  <div class="section-circle-card" id="red">
                      <i class="fas fa-cloud"></i>
                  </div>
                  <h4>And we think about</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
              <div class="section-card">
                  <div class="section-circle-card" id="pink">
                      <i class="fas fa-pencil-alt"></i>
                  </div>
                  <h4>So we draw along</h4>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  
              </div>
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
    margin: 0 auto;
    
}

.section-background {
    background-image: url(../assets/svg/svg-3.svg);
    background-size: 100%;
    background-repeat: no-repeat;
    display: flex;
}

.section-card {
    width: calc(100%/4);
    margin: 15px;
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
    font-size: 2rem;
}

#green {
    color: #C0E1CF;
}

#yellow {
    color: #F8D12D;
}

#red {
    color: #80465F;
}

#pink {
    color: #EE2852;
}

h4 {
    margin: 10px 0;
    text-align: center;
}

p {
    text-align: center;
}



</style>