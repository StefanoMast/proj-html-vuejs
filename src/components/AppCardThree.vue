<template>
  <div class="card-section">
        <img :src="require(`../assets/img/${cardObj.img}`)" alt="">
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Provident, enim deserunt facere excepturi eos nulla ratione deleniti minus omnis ducimus odio voluptatum maxime, commodi itaque adipisci modi quis, sequi optio?</p>
        <small>descrizio immagine</small>
        <div class="card-date">
            <div class="card-day">
                <span>07</span>
            </div>
            <div class="card-month">
                JUN '22
            </div>
        </div>
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
    position: relative;
}

.card-section img {
    width: 100%;
}

.card-date {
    position: absolute;
    top: -5%;
    left: 5%;
    width: 90px;
    height: 110px;
    
}

.card-day {
    height: 70px;
    background-color: #C0E1CF;
    text-align: center;
    font-size: 3.5rem;
}

.card-month {
    height: 40px;
    text-align: center;
    padding: 2px;
    background-color: #F4D0C7;
    clip-path: polygon( 100% 0, 100% 100%, 50% 50%, 0 100%, 0 0);
}

</style>