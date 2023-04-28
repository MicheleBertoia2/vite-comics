
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

          <div class="card">
            <img src="https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg" alt="American Vampire 1976">
            <h4>american vampire 1976</h4>
          </div>

          <div class="card">
            <img src="https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg" alt="American Vampire 1976">
            <h4>american vampire 1976</h4>
          </div>

          <div class="card">
            <img src="https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg" alt="American Vampire 1976">
            <h4>american vampire 1976</h4>
          </div>

          <div class="card">
            <img src="https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg" alt="American Vampire 1976">
            <h4>american vampire 1976</h4>
          </div>

          <div class="card">
            <img src="https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg" alt="American Vampire 1976">
            <h4>american vampire 1976</h4>
          </div>

          <div class="card">
            <img src="https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg" alt="American Vampire 1976">
            <h4>american vampire 1976</h4>
          </div>

          <div class="card">
            <img src="https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg" alt="American Vampire 1976">
            <h4>american vampire 1976</h4>
          </div>

        </div>

      </div>

      <div class="load-more">
        <button>LOAD MORE</button>
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

    .container{
      position: relative;
      top: -25px;
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

      .cards-container{        
        display: flex;
        flex-wrap: wrap;
        padding: 10px 0;
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
      }

      .load-more{
        @include centerFlex;
        padding-bottom: 20px;
        button{
          border: none;
          color: $color-white;
          background-color: $color-blue;
          font-weight: 700;
          padding: 10px 50px;
        }
      }
    }
  }
</style>