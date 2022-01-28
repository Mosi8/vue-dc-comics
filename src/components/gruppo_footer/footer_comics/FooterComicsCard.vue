<template>
  <footer>
    <img :src="card.img">
    <p>{{card.text}}</p>
  </footer>
</template>

<script>
export default {
    name : 'FooterComicsCard',
    props : {
        card : Object,
    },
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';

footer{
  background-color: $mainColor;
  vertical-align: middle;

  img {
    width: 20%;
    vertical-align: middle;
  }

  p {
    display: inline-block;
    color: #fff;
    font-size: 10px;
    margin: 0 10px;
  }
}
</style>