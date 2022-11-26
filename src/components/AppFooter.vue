
<script>
export default {
name:'AppFooter',

}



</script>

<template>
  <div class="content">
    <h2>Live Dates</h2>

    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi, ullam.</p>

    <div class="listLuoghi">
      <ul>
        <li>ciao mi chiamo giorgio</li>
        <li>ciao mi chiamo giorgio</li>
        <li>ciao mi chiamo giorgio</li>
        <li>ciao mi chiamo giorgio</li>

      </ul>
     

    </div>



  </div>

  <div class="content_3">
    <h3>Lorem, ipsum dolor.</h3>

  </div>

  <div class="footer">
    <div class="logo">
      <img src="logo_footer.png" alt="">
    </div>
    <div class="menu">
      <ul>
        <ul><a href="#">Home</a></ul>
        <ul><a href="#">Meet The Band</a></ul>
        <ul><a href="#">Live Dates</a></ul>
        <ul><a href="#">Latest News</a></ul>
        <ul><a href="#">Albums</a></ul>
        <ul><a href="#">Fans</a></ul>
      </ul>

    </div>


  </div>

  <div class="footer2">
    <ul>
      <li>1</li>
      <li>2</li>
      <li>3</li>
      <li>4</li>
    </ul>

    <div class="social">
      <ul>
        <li><a href="#">F</a></li>
        <li><a href="#">T</a></li>
        <li><a href="#">I</a></li>
        <li><a href="#">Y</a></li>
      </ul>

    </div>

  </div>

 
  
</template>



<style lang="scss" scoped>
.content{
  background-color:#272b34 ;
  text-align: center;
  padding: 20px;
}
.content_3 {
  text-align: center;

  h3{
    line-height: 100px;
  }

}
.footer {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  background-color: #272b34;
  align-items: center;

  ul {
    display: flex;
  }
  a {
    text-decoration: none;
    color: white;
  
  &:hover{
    color: green;
  }
}

}

.footer2 {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  align-items: center;
  background-color: #323843;

  ul{
    display: flex;
 
  }
  
  li{
   list-style-type: none;
   padding-left: 20px;
   color: white;
  }
  a{
    text-decoration: none;
    color: white;
  }

}




</style>