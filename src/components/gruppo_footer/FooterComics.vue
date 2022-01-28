<template>
  <footer>
    <div class="container">
      <FooterComicsCard class="card" v-for="(element, index) in cards" :key="index" :card="element"/>
    </div>
  </footer>
</template>

<script>
import FooterComicsCard from './footer_comics/FooterComicsCard.vue';
export default {
    name: 'FooterComics',
    components: {
     FooterComicsCard,
    },
    data(){
      return {
        cards: [
          {
            img : require('../../assets/img/buy-comics-digital-comics.png'),
            text : "DIGITAL COMICS"
          },
          {
            img : require('../../assets/img/buy-comics-merchandise.png'),
            text : "DC MERCHANDISE"
          },
          {
            img : require('../../assets/img/buy-comics-subscriptions.png'),
            text : "SUBSCRIPTION"
          },
          {
            img : require('../../assets/img/buy-comics-shop-locator.png'),
            text : "COMIC SHOP LOCATOR"
          },
          {
            img : require('../../assets/img/buy-dc-power-visa.svg'),
            text : "DC POWER VISA"
          },
        ] }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

footer{
  background-color: $mainColor;
  height: 120px;
  
  .container {
    display: flex;
    justify-content: space-between;
    color: #fff;
    line-height: 120px;

    .card {
    width: 18%;
    margin: 0 10px;
    }
  }
  
}
</style>