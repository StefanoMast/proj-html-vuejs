<template>
  <div class="contact-us">
      <div class="contact-content">
          <h2>Want to work with us? Send us<span> a message</span></h2>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam quod non ab doloremque ad vero repellat, a cumque aliquid itaque maiores maxime quam quisquam, minus, enim in! Aspernatur, saepe ea!</p>
      </div>
      <div class="contact-btn">
          <button>CONTACT</button>
      </div>
      <div class="contact-image-first">
          <img src="../assets/img/short-slider-rev-1-img-6.png" alt="">
      </div>
      <div class="contact-image-second"></div>
      <div class="contact-image-third"></div>
      <div class="contact-image-fourth"></div>
      <div class="contact-image-fifth"></div>
      <div class="contact-image-sixth"></div>
      <div class="contact-image-seventh"></div>
      <div class="contact-image-eighth">
          <img src="../assets/img/short-slider-rev-1-img-2.png" alt="">
      </div>
        
      
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.contact-us {
    width: 100%;
    height: 400px;
    background-color: #FAF7F1;
    display: flex;
    flex-direction: column;
    justify-content: center;
    position: relative;
}

.contact-content {
    width: 60%;
    margin: auto;
}

h2, p {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 1rem;
}

h2 {
    font-size: 3rem;
}

span {
    margin: 0 0 5px 5px;
}

p {
    text-align: center;
}

button {
    width: 250px;
    height: 50px;
    background-color: #D8F0E3;
    border: 2px solid #C0E1CF;
}

button:hover {
    color: #C0E1CF;
    background-color: #FAF7F1;
}

.contact-btn {
    text-align: center;
    padding-bottom: 5rem;
}
.contact-image-first,
.contact-image-second,
.contact-image-third,
.contact-image-fourth,
.contact-image-fifth,
.contact-image-sixth,
.contact-image-seventh,
.contact-image-eighth {
    position: absolute;
}

.contact-image-first {
    bottom: 0;
    left: 14%;
}

.contact-image-second {
    background-color: #D8F0E3;
    transform: rotate(180deg);
    right: 10%;
    top: 0;
    width: 16%;
    height: 100px;
    clip-path: circle(40% at 50% 140% );
}

.contact-image-third {
    background-color: #C0E1CF;
    right: 0;
    top: 0;
    width: 26%;
    height: 400px;
    clip-path: circle(55% at 14% 140% );
    transform: rotate(180deg);
}

.contact-image-fourth {
    width: 20%;
    height: 400px;
    left: 0;
    top: 0%;
    clip-path: ellipse(55% 20% at 15% 5%);
    background-color: #C0E1CF;
}

.contact-image-fifth,
.contact-image-sixth,
.contact-image-seventh {
    /* position: absolute; */
    width: 10%;
    height: 400px;
}
   
.contact-image-fifth  {left: 15%;
    top: 0%;
    clip-path: circle(55% at 50% 135% );
    background-color: #cbe8c4;
    transform: rotate(180deg);}

.contact-image-sixth {
    left: 23%;
    bottom: 0%;
    clip-path: circle(50% at 50% 135% );
    background-color: #cbe8c4;
}

.contact-image-seventh {
    right: 0;
    bottom: 0%;
    clip-path: circle(50% at 55% 130% );
    background-color: #cbe8c4;
}

.contact-image-eighth {
    top: 10%;
    right: 12%;
}



</style>