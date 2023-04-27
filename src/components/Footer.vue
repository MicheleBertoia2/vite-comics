
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
          <li><a href="#">dc comics</a></li>
          <li><a href="#">dc comics</a></li>
          <li><a href="#">dc comics</a></li>
          <li><a href="#">dc comics</a></li>
          <li><a href="#">dc comics</a></li>
          <li><a href="#">dc comics</a></li>
          <li><a href="#">dc comics</a></li>          
        </ul>
        
        <ul>
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>                    
        </ul>
        
        <ul>
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
        </ul>
        
        <ul>
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
          <li><a href="#">dc comics</a></li>          
        </ul>

      </div>

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
    height: 280px;
    background-image: url('../assets/img/footer-bg.jpg');
    overflow: hidden;
    .f-top{
      height: 100%;
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
               font-size: 14px;      
             }
           }
           a {
             color: lighten($color-darkgray, 10%);
             font-size: 9px;           
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
    
  }


</style>