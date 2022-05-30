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
    name: "CardList",
    components: { AppCard },
    data: function () {
        return {
            cards: [
                {
                    img: "../assets/img/h-2-port-img-1.jpg"
                },
                {
                    img: "../assets/img/h-2-port-img-2.jpg"
                },
                {
                    img: "../assets/img/h-2-port-img-3.jpg"
                },
                {
                    img: "../assets/img/h-2-port-img-4.jpg"
                },
                {
                    img: "../assets/img/h-2-port-img-5.jpg"
                },
                {
                    img: "../assets/img/h-2-port-img-6.jpg"
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