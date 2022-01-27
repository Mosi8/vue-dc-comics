<template>
  <footer>
    <div class="container">
      <Signup />
      <Social />
    </div>
  </footer>
</template>

<script>
import Signup from './footer_finale/Signup.vue';
import Social from './footer_finale/Social.vue';

export default {
    name: 'FooterFinale',
    components: {
        Signup,
        Social
      }
}
</script>

<style lang="scss" scoped>
footer{
  background-color: rgb(51, 51, 51);
  line-height: 100px;
  height: 90px;
}
</style>