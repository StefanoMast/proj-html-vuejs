<template>
  <div class="card">
    <img :src="require(`../assets/img/${cardObj.img}`)" alt="">
  </div>
</template>

<script>
export default {
    name: "AppCard",
    props: {
        cardObj: Object
    },
    
}
</script>

<style scoped>
.card {
    width: calc(100%/3);
}

.card img {
    width: 100%;
}

</style>