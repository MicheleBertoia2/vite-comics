
<script>
export default {
  
}
</script>

<template>
  <section>

    <div class="jumbo">
      <img src="../assets/img/jumbotron.jpg" alt="dc heroes">
    </div>

    <div class="content">

      <div class="container">

        <div class="label">
          <span>current series</span>
        </div>

        <div class="cards-container">

        </div>

      </div>

      <div class="load-more">
        <button></button>
      </div>

    </div>

  </section>
</template>

<style lang="scss" scoped>
  @use '../scss/general' as *;
  @use '../scss/utils' as *;
  @use '../scss/vars' as *;
  @use '../scss/mixin' as *;

  section{
    .jumbo{
      height: 300px;
      overflow: hidden;
    }

    .content{
      background-color: $color-black;
      .label{
        height: 50px;
        width: 180px;
        background-color: $color-blue;
        text-align: center;
        span{
          text-transform: uppercase;
          color: white;
          line-height: 50px;
          font-size: 16px;
          font-weight: 700;
        }
      }
    }
  }
</style>