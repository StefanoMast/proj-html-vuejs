<template>
  <div class="card-section">
      <img :src="require(`../assets/img/${cardObj.img}`)" alt="">
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Provident, enim deserunt facere excepturi eos nulla ratione deleniti minus omnis ducimus odio voluptatum maxime, commodi itaque adipisci modi quis, sequi optio?</p>
      <small>descrizio immagine</small>
  </div>
</template>

<script>
export default {
    name: "AppCardThree",
    props: {
        cardObj: Object
    },
}
</script>

<style scoped>
.card-section {
    width: calc(100%/3 - 10px);
    margin: 6rem 5px;
    border: 1px solid black;
}

.card-section img {
    width: 100%;
}

</style>