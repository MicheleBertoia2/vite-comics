
<script>
export default {
  
}
</script>

<template>
  <section id="actions">

    <ul class="cards container">

      <li class="card">
        <a href="#">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">
          <span>digital comics</span>
        </a>
      </li>

      <li class="card">
        <a href="#">
          <img src="../assets/img/buy-comics-merchandise.png" alt="digital comics">
          <span>dc merchandise</span>
        </a>
      </li>

      <li class="card">
        <a href="#">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="digital comics">
          <span>subscriptions</span>
        </a>
      </li>

      <li class="card">
        <a href="#">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="digital comics">
          <span>comic shop locator</span>
        </a>
      </li>

      <li class="card">
        <a href="#">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="digital comics">
          <span>dc power visa</span>
        </a>
      </li>
      
    </ul>

  </section>
</template>

<style lang="scss" scoped>
  @use '../scss/general' as *;
  @use '../scss/utils' as *;
  @use '../scss/vars' as *;
  @use '../scss/mixin' as *;

  #actions {
    background-color: $color-blue;
    color: $color-white;
    height: 120px;
    .cards{
      @include centerFlex(vertical);
      justify-content: space-around;
      height: 100%;
      padding: 40px 0;
      .card{
        height: 100%;
        &:last-child{
            img{
              width: 40px;
            }
          }
        a{
          display: inline-block;
          color: $color-white;
          height: 40px;
          img{
          height: 40px;
          vertical-align: middle;
          
          }
          span {
            text-transform: uppercase;
            margin-left: 10px;
            font-size: 9px;
          }
        }
        
      }
    }
  }
</style>