<template>
  <footer>
    <div class="container">
      <FooterComicsPrimo />
      <FooterComicsPrimo />
      <FooterComicsPrimo />
      <FooterComicsPrimo />
      <FooterComicsPrimo />
    </div>
  </footer>
</template>

<script>
import FooterComicsPrimo from './footer_comics/FooterComicsPrimo.vue';
export default {
    name: 'FooterComics',
    components: {
     FooterComicsPrimo,
     }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

footer{
  background-color: $mainColor;
  height: 170px;

  .container {
    display: flex;
    justify-content: space-between;
  }
}
</style>