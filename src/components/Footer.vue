
<script>
export default {
  
}
</script>

<template>
  <footer>

    <div class="f-top container">
      <div class="f-left"></div>
      <div class="f-right">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
    </div>

    <div class="f-social container"></div>

  </footer>
</template>

<style lang="scss" scoped>
  @use '../scss/general' as *;
  @use '../scss/utils' as *;
  @use '../scss/vars' as *;
  @use '../scss/mixin' as *;

  footer{
    min-height: 300px;
    background-image: url('../assets/img/footer-bg.jpg');
    .f-top{
      display: flex;
      justify-content: space-between;
        .f-left{
        border: 1px solid white;
        width: 35%;
      }
      .f-right{
        width: 40%;
        img{
          transform: translateY(-10%);
        }
      }
    }
    
  }


</style>