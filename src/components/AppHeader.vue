<template>
  <header>
      <div class="header">
          <div class="header-arrow-right"><img src="../assets/svg/svg-5.svg" alt=""></div>
          <div class="header-arrow-left"><img src="../assets/svg/svg-5.svg" alt=""></div>
          <div class="header-nav">
              <div class="header-nav-logo">
                  <img src="../assets/img/logo-sidearea-1-1.png" alt="">
              </div>
              <div class="header-nav-menu">
                <ul>
                  <li
                v-for="(item, index) in links"
                :key="index">
                <a href="">{{ item.text }}</a>
                </li>
                </ul>
                <img src="../assets/svg/svg-1.svg" alt="">
              </div>
         </div>

         <div class="header-container">
            <div class="header-container-first">
                <div class="header-content">
                    <h1>Devotion that never <span>ends</span></h1>
                    <p>Neque porro quisquam est, qui dolorem ispum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi</p>
                    <button>READ MORE</button>
                </div>
                
            </div>
            <div class="header-container-second">
                <img src="../assets/img/h-2-slider-img-15.png" alt="">
                <img src="../assets/img/h-2-slider-img-16.png" alt="">
                <div class="small-image">
                    <img src="../assets/img/short-slider-rev-1-img-2.png" alt="">
                </div>
                <div class="small-image-second">
                    <img src="../assets/img/h-2-slider-img-12.png" alt="">
                </div>
                <div class="small-image-third">
                    <img src="../assets/img/h-2-slider-img-13.png" alt="">
                </div>
                <div class="small-image-fourth">
                    <img src="../assets/img/h-2-slider-img-14.png" alt="">
                </div>
                <div class="small-image-fifth">
                    <img src="../assets/img/short-slider-rev-1-img-6.png" alt="">
                </div>
                <div class="small-image-sixth">
                    <img src="../assets/img/h-2-slider-img-17.png" alt="">
                </div>

                
               
            </div>
         </div>
      </div>
  </header>
</template>

<script>
export default {
    name: "AppHeader",
    data() {
        return {
        links: [
            {
            url: "#",
            text: "HOME",

        },
        {
            url: "#",
            text: "PAGES"
        },
        {
            url: "#",
            text: "PORTFOLIO"
        },
        {
            url: "#",
            text: "BLOG"
        },
        {
            url: "#",
            text: "SHOP"
        },
        {
            url: "#",
            text: "ELEMENTS"
        }
        ]
    }
    }
}
</script>

<style scoped>

.header {
    position: relative;
}
.header-arrow-right {
    width: 38px;
    height: 35px;
    border-radius: 100%;
    background-color: #F0817B;
    text-align: center;
    position: absolute;
    top: 50%;
    right: 2%;
}

.header-arrow-left {
    width: 38px;
    height: 35px;
    border-radius: 100%;
    background-color: #F0817B;
    text-align: center;
    position: absolute;
    top: 50%;
    left: 2%;
    transform: rotate(180deg);
}

.header-nav {
    width: 100%;
    height: 50px;
  
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header-nav li {
    display: inline;
    list-style: none;
}

.header-nav-menu {
    display: flex;
    justify-content: flex-end;
}

.header-nav-menu img {
    margin: 0 2rem;
}

.header-container {
    display: flex;
}
.header-container-first {
    width: 50%;
    display: flex;
    align-items: center;
}

.header-content {
    width: 50%;
    margin: auto;
}

h1 {
    font-size: 4rem;
}

p {
    text-align: start;
}

button {
    width: 250px;
    height: 50px;
    margin-top: 1.5rem;
    border: 2px solid #E1C0B0;
}

button:hover {
    color: white;
    background-color: #E1C0B0;
}
.header-container-second {
    display: flex;
    padding: 2rem 0;
    margin-top: 3rem;
    position: relative;
}

.small-image {
    position: absolute;
    left: 5%;
    top: -5%;
}

.small-image-second {
    position: absolute;
    top: 50%;
    left: -10%;
}

.small-image-third {
    position: absolute;
    bottom: 7%;
}

.small-image-fourth {
    position: absolute;
    right: 5%;
    top: -6%;
}

.small-image-fifth {
    position: absolute;
    top: 20%;
    right: -4%;
}

.small-image-sixth {
    position: absolute;
    bottom: 7%;
    right: -13%;
}

li {
    margin-right: 1rem;
    font-weight: bold;
}

li:hover {
    border-bottom: 3px solid #F0817B;
}

a {
    text-decoration: none;
    color: black;
}



</style>