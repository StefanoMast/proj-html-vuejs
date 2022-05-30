<template>
  <header>
      <div class="header">
          <div class="header-nav">
              <div class="header-nav-logo">
                  <img src="../assets/img/logo-sidearea-1.png" alt="">
              </div>
              <div class="header-nav-menu">
                <ul>
                  <li><a href="">HOME </a></li>
                  <li><a href="">PAGES </a></li>
                  <li><a href="">ELEMENT </a></li>
                  <li><a href="">PORTFOLIO </a></li>
                  <li><a href="">IMAGES</a></li>
                </ul>
                <img src="../assets/svg/svg-1.svg" alt="">
              </div>
         </div>

         <div class="header-container">
            <div class="header-container-first">
                ciao
            </div>
            <div class="header-container-second">
                buongiorno
            </div>
         </div>
      </div>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>

.header-nav {
    width: 100%;
    height: 30px;
  
    display: flex;
    justify-content: space-between;
}

.header-nav li {
    display: inline;
    list-style: none;
}

.header-nav-menu {
    display: flex;
    justify-content: flex-end;
}

.header-container {
    height: 200px;
    background-color: blueviolet;
    display: flex;
}
.header-container-first {
    width: 50%;
    border: 1px solid black;
}

</style>