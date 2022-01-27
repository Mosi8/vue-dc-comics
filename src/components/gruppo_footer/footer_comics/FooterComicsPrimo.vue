<template>
  <footer>
    <img src="../../../assets/img/buy-comics-digital-comics.png">
    <p>DIGITAL COMICS</p>
  </footer>
</template>

<script>
export default {
    name: 'FooterComicsPrimo'
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';

footer{
  background-color: $mainColor;
  height: 170px;
  vertical-align: middle;
  line-height: 170px;

  img {
    height: 80px;
    line-height: 170px;
    vertical-align: middle;
  }

  p {
    display: inline-block;
    color: #fff;
    font-size: 12px;
    margin: 0 10px;
  }
}
</style>