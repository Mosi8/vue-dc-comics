<template>
  <div>
    <div class="ritaglio">
      <img :src="fumettoDc.thumb">
    </div>
    <p>{{fumettoDc.series}}</p>
  </div>
</template>

<script>
export default {
    name : 'Fumetto',
    props : {
        fumettoDc : Object,
    },
}
</script>

<style lang="scss" scoped>

div{
  text-align: left;
  
  .ritaglio{
  height: 150px;
  overflow: hidden;

  img {
    width: 100%;
  }
  }

  p {
    color: #fff;
    font-size: 15px;
    margin: 10px 0;
  }
}
</style>