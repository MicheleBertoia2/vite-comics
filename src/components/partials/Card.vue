
<script>
export default {
  name : 'Card',
  props : {
    imgUrl: String,
    imgTitle: String
  }
}
</script>

<template>
  <div class="card">
    <img :src="imgUrl" :alt="imgTitle">
    <h4>{{imgTitle}}</h4>
  </div>
</template>

<style lang="scss" scoped>
  .card{
          width: calc(100% / 6);
          padding: 10px;
          img{
            width: 100%;
            aspect-ratio: 1/1 ;

          }
          h4{
            color: white;
            text-transform: uppercase;
            font-size: 10px;
            padding: 10px
            
          }
        }
</style>