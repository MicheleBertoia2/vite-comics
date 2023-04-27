
<script>
export default {
  
}
</script>

<template>
  <footer>

    <div class="f-top container">

      <div class="f-left">

        <ul>
          <li><a href="#">dc comics</a></li>
          <li><a href="#">characters</a></li>
          <li><a href="#">comics</a></li>
          <li><a href="#">movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">videos</a></li>
          <li><a href="#">news</a></li>          
        </ul>
        
        <ul>
          <li><a href="#">shop</a></li>          
          <li><a href="#">shop DC</a></li>          
          <li><a href="#">shop DC collectibles</a></li>                    
        </ul>
        
        <ul>
          <li><a href="#">DC</a></li>          
          <li><a href="#">terms of use</a></li>          
          <li><a href="#">privacy policy(new)</a></li>          
          <li><a href="#">ad choices</a></li>          
          <li><a href="#">advertising</a></li>          
          <li><a href="#">jobs</a></li>          
          <li><a href="#">subscriptions</a></li>          
          <li><a href="#">talent workshop</a></li>          
          <li><a href="#">CPSC certificates</a></li>          
          <li><a href="#">ratings</a></li>          
          <li><a href="#">shop help</a></li>          
          <li><a href="#">contact us</a></li>          
        </ul>
        
        <ul>
          <li><a href="#">sites</a></li>          
          <li><a href="#">DC</a></li>          
          <li><a href="#">MAD magazine</a></li>          
          <li><a href="#">DC kids</a></li>          
          <li><a href="#">DC universe</a></li>          
          <li><a href="#">dDC power visa</a></li>                    
        </ul>

      </div>

      <div class="f-right">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>

    </div>

    <div class="f-social">
      <div class="container">

        <button>sign up now!</button>

        <div class="icons">
          <span>FOLLOW US</span>
          <img src="../assets/img/footer-facebook.png" alt="">
          <img src="../assets/img/footer-twitter.png" alt="">
          <img src="../assets/img/footer-youtube.png" alt="">
          <img src="../assets/img/footer-pinterest.png" alt="">
          <img src="../assets/img/footer-periscope.png" alt="">
        </div>

      </div>
    </div>

  </footer>
</template>

<style lang="scss" scoped>
  @use '../scss/general' as *;
  @use '../scss/utils' as *;
  @use '../scss/vars' as *;
  @use '../scss/mixin' as *;

  footer{
    height: 360px;
    background-image: url('../assets/img/footer-bg.jpg');
    .f-top{
      overflow: hidden;
      height: calc(100% - 80px);
      display: flex;
      justify-content: space-between;
      .f-left{
        height: 100%;
        padding: 20px 0;
        width: 35%;
        display: flex;
        flex-flow: column wrap;
        ul{
          margin-bottom: 10px;
          li{
          &:first-child{
             a{
               color: $color-white;
               text-transform: uppercase;      
               font-weight: 500;
               font-size: 12px;      
             }
           }
           a {
             color: lighten($color-darkgray, 10%);
             font-size: 8px;  
             text-transform: capitalize;        
             }
          }
          
        }
        
      }
      .f-right{
        width: 40%;
        img{
          transform: translateY(-10%);
        }
      }
    }

    .f-social{
      height: 80px;
      background-color: $color-black;
      .container{
        height: 100%;
        @include centerFlex(vertical);
        justify-content: space-between;
      }
      button{
        background-color: transparent;
        color: $color-white;
        text-transform: uppercase;
        font-size: 10px;
        font-weight: 700;
        padding: 10px;
        border-color: $color-blue;        
        cursor: pointer;
      }
      .icons{
        span{
          color: $color-blue;
        }
        img{
          width: 30px;
          vertical-align: middle;
          margin-left: 10px;
        }
      }
    }
    
  }


</style>