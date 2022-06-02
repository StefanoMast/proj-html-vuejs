<template>
  <div class="container-footer">
      <div class="footer-components">
          <AppFooterLogo/>
          <AppFooterContacs/>
          <!-- <div
          v-for="(item, index) in contacts"
          :key="index" 
          class="footer-contacts">
               <p>maree.qode@gmail.com</p>
              <p>+44645 321 789</p> -->
              <!-- {{item.text}} 
              {{item.number}}
          </div> --> 
          <!-- <div class="footer-address">
              <p>Avenue d'Auderghem 10</p>
              <p>1040 Brussels, Belgium</p>
          </div> -->
          <!-- <div class="footer-socials">
              <p>Stay in touch with us</p>
              <div class="footer-socials-icons">
                  <i class="fab fa-twitter"></i>
                  <i class="fab fa-pinterest-p"></i>
                  <i class="fab fa-facebook-f"></i>
                  <i class="fab fa-linkedin-in"></i>
              </div>
          </div> -->
          <AppFooterSocial/>
      </div>
  </div>
</template>

<script>
import AppFooterLogo from './AppFooterLogo.vue'
import AppFooterContacs from './AppFooterContacs.vue'
import AppFooterSocial from './AppFooterSocial.vue'

export default {
    name: "AppFooter",
    // data() {
    //     return {
    //         contacts: [
    //             {
    //                 url: "#",
    //                 text: "maree.qode@gmail.com",
    //                 number: "+44645 321 789"
    //             },
    //             {
    //                 url: "#",
    //                 text: "Avenue d'Auderghem 10",
    //                 number: "1040 Brussels, Belgium"
    //             }
    //         ]
    //     };
    

    components: { 
        AppFooterLogo,
        AppFooterContacs,
        AppFooterSocial },

}
</script>

<style scoped>
.container-footer {
    background-color: #C0E1CF;
    height: 200px;
    display: flex;
    align-items: center;
}

.footer-components {
    width: 60%;
    margin: auto;
    display: flex;
    justify-content: space-between;
}

/* .footer-contacts, .footer-address {
    width: calc(100%/4);
} */

/* .footer-socials-icons {
    width: 100%;
    display: flex;
    justify-content: space-between;
} */

/* p {
    margin: 1rem 0;
} */

</style>