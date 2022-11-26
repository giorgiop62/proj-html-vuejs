<script>
export default {
  name:'AppMain'

}
</script>

<template>
  <div class="mContainer">
    <div class="content_1">
      <h2>Music Is Life</h2>

      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores,   veniam!</p>
    </div>

      <div class="content_2">
        <h2>Latest Band News</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur repudiandae quas error et beatae! Placeat.</p>

        <div class="box">    
        </div>

        <div class="content_3">
          <h3>VIEW ALL LATEST NEWS</h3>
        </div>

        <div class="content_4">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi voluptatum repellat veritatis, sunt voluptas porro aspernatur possimus facere nemo nobis doloribus labore dicta accusantium similique nulla aperiam fugit recusandae asperiores reprehenderit dignissimos. Sapiente iusto soluta quas placeat voluptatum error illo! Dolores maiores ex perspiciatis voluptas rem eos ea autem sint!</p>
          <button class="play">x</button>

        </div>
        
        

      </div>


   
    

   
  </div>
  
</template>



<style lang="scss" scoped>

.mContainer {
  text-align: center;
  .content_1{
    background-color: #323843 ;
    padding: 20px;
    
  
  }
  .content_2 {
    background-color: #272b34 ;

    .box {
      width: 80%;
      display: flex;
      margin: 0 auto;
      height: 500px;
      background-color: green;
    }

    
  
   
  }
  .content_3{
    width: 100%;
    height: 100px;
    background-color: #ea4a56 ;
  }
  h3{
    line-height:100px
    
  }

  .content_4{
    background-image: url(../assets/home-testimonial-parallax.jpg);
    height: 400px; 
    background-size: 100%;

  }
}

</style>