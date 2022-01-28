<template>
  <main>
    <Jumbotron class="jumbo"/>
    <div class="container">
      <h3>CURRENT SERIES</h3>
      <Fumetti />
      <button>LOAD MORE</button>
    </div>
  </main>
</template>

<script>
import Fumetti from './gruppo_main/Fumetti.vue';
import Jumbotron from './gruppo_main/Jumbotron.vue';

export default {
    name: 'Main',
    components: {
      Fumetti,
      Jumbotron,
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';
  main{
    background-color: #000;
    margin-top: 4px;
    color: #fff;

    .jumbo {
      width: 100%;
      height: 300px;
      overflow: hidden;
    }

    .container {
      text-align: center;
      position: relative;

      h3 {
        color: #fff;
        background-color: $mainColor;
        display: inline-block;
        padding: 8px 20px;
        position: absolute;
        left: 0;
        transform: translateY(-50%);
      }

      button {
        font-weight: bold;
        color: #fff;
        background-color: $mainColor;
        padding: 10px 40px;
        border: none;
        margin-bottom: 40px ;
        cursor: pointer;
      }
    }
  }
</style>