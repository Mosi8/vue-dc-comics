<template>
  <footer>
    <FooterComics />
    <FooterCentrale />
    <FooterFinale />
  </footer>
</template>

<script>
import FooterComics from './gruppo_footer/FooterComics.vue';
import FooterCentrale from './gruppo_footer/FooterCentrale.vue';
import FooterFinale from './gruppo_footer/FooterFinale.vue';


export default {
    name: 'Footer',
    components: {
        FooterComics,
        FooterCentrale,
        FooterFinale
      }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';


</style>