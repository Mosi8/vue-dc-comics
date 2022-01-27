<template>
    <div class="sign">
      <h4>FOLLOW US</h4>
      <ul>
          <li>
            <img src="../../../assets/img/footer-facebook.png">
          </li>
          <li>
            <img src="../../../assets/img/footer-twitter.png">
          </li>
          <li>
            <img src="../../../assets/img/footer-youtube.png">
          </li>
          <li>
            <img src="../../../assets/img/footer-pinterest.png">
          </li>
          <li>
            <img src="../../../assets/img/footer-periscope.png">
          </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'Social',
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';

.sign{
  height: 90px;
  line-height: 90px;
  vertical-align: middle;
  float: right;
  h4 {
    display: inline-block;
    color: $mainColor;
  }

  ul{
    list-style-type: none;
    display: inline-block;
    
    li {
      display: inline-block;
    }

    li img{
      display: inline-block;
      color: #000;
      margin: 0 15px;
      text-decoration: none;
      height: 36px;
      width: 36px;
      line-height: 90px;
      vertical-align: middle;
    }
  }
}
</style>