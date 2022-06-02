<template>
  <div class="footer-socials">
              <p>Stay in touch with us</p>
              <br>
              <div class="footer-socials-icons">
                  <i class="fab fa-twitter"></i>
                  <i class="fab fa-pinterest-p"></i>
                  <i class="fab fa-facebook-f"></i>
                  <i class="fab fa-linkedin-in"></i>
              </div>
          </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer-socials {
    width: calc(100%/4);
}

.footer-socials-icons {
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
}

p {
    text-align: center;
}
</style>