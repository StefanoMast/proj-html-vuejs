<template>
  <div
          v-for="(item, index) in contacts"
          :key="index" 
          class="footer-contacts">
              <!-- <p>maree.qode@gmail.com</p>
              <p>+44645 321 789</p> -->
              <div>{{item.text}}</div> 
              <br>
              <div>{{item.text1}}</div>
          </div>
</template>

<script>
export default {
    name: "AppFooterContacs",
    data() {
        return {
            contacts: [
                {
                    url: "#",
                    text: "maree.qode@gmail.com",
                    space: " ",
                    text1: "+44645 321 789"
                },
                {
                    url: "#",
                    text: "Avenue d'Auderghem 10",
                    space: " ",
                    text1: "1040 Brussels, Belgium"
                }

            ]
        }
    }
}
</script>

<style scoped>
.footer-contacts {
    display: flex;
    flex-direction: column;
}

</style>