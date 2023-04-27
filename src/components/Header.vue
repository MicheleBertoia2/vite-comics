
<script>
export default {
  
}
</script>

<template>
  <header>
    <div class="top-bar container">
      <img src="../assets/img/dc-logo.png" alt="">
      <nav>
        <ul>
          <li><a href="#">characters</a></li>
          <li><a href="#" class="active">comics</a></li>
          <li><a href="#">movies</a></li>
          <li><a href="#">tv</a></li>
          <li><a href="#">games</a></li>
          <li><a href="#">collectibles</a></li>
          <li><a href="#">videos</a></li>
          <li><a href="#">fans</a></li>
          <li><a href="#">news</a></li>
          <li><a href="#">shop</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
  @use '../scss/general' as *;
  @use '../scss/utils' as *;
  @use '../scss/vars' as *;
  @use '../scss/mixin' as *;

  .top-bar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 81px;
      img{
        height: 55px;
        margin: 10px 0 0 10px;
      }
      li{
        display: inline-block;
        height: 100%;
        font-size: 10px;
        margin: 0 10px;
        
        
        a{
          height: 100%;
          color: $color-black;
          border-bottom: 4px solid transparent;
          padding: 29px 0;
          &.active{
            border-bottom-color: $color-blue;
            color: $color-blue;
          }
        }
      }
  }
</style>