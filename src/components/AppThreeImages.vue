<template>
<div class="container">
    <div class="container-size">
        <AppCardThree
        v-for="(item, index) in cards"
        :key="index"
        :cardObj="item"/>
    </div>
</div>
</template>

<script>
import AppCardThree from './AppCardThree.vue';
export default {
    name: "AppThreeImages",
    components: { AppCardThree },
    data: function () {
        return {
            cards: [
                {
                    
                    img: "h-2-blog-img-1.jpg",
                    name: "img1"
                },
                {
                   img: "h-2-blog-img-2.jpg",
                   name: "img2"
                },
                {
                    img: "h-2-blog-img-3.jpg",
                    name: "img3"
                }
            ]  
        }
    }
}
</script>

<style scoped>
.container-size {
    width: 60%;
    margin: auto;
    display: flex;
}

</style>