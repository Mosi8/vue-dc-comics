<template>
    <div class="sign">
      <button>SIGN-UP NOW!</button>
    </div>
</template>

<script>
export default {
    name: 'Signup'
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';

.sign{
  height: 90px;
  line-height: 90px;
  vertical-align: middle;
  float: left;

  button {
  color: #fff;
  border: solid 2px $mainColor;
  background-color: rgb(51, 51, 51);
  font-size: 12px;
  padding: 12px;
}
}
</style>