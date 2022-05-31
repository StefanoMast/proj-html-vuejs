<template>
  <main>
      <div class="main">
          <AppCard
          v-for="(item, index) in cards"
          :key="index"
          :cardObj="item"/>
      </div>
  </main>
</template>

<script>
import AppCard from './AppCard.vue';
export default {
    name: "AppMain",
    components: { AppCard },
    data: function () {
        return {
            cards: [
                {
                    
                    img:"h-2-port-img-1.jpg",
                    name: "img1"
                },
                {
                   img: "h-2-port-img-2.jpg",
                   name: "img2"
                },
                {
                    img: "h-2-port-img-3.jpg",
                    name: "img3"
                },
                {
                    img: "h-2-port-img-4.jpg",
                    name: "img4"
                },
                {
                    img: "h-2-port-img-5.jpg",
                    name: "img5"
                },
                {
                    img: "h-2-port-img-6.jpg",
                    name: "img6"
                }
            ]  
        }
    }
}
</script>

<style scoped>

.main {
    display: flex;
    flex-wrap: wrap;
}

</style>