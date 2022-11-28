
<script>
export default {
  name: 'AppFooter',

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
      <li>Copyright 2012-2020</li>
      <li>AVADA THEME BY THEMEFUSION</li>
      <li>ALL RIGHTS RESERVED</li>
      <li>POWERED BY WORDPRESS</li>
    </ul>

    <div class="social">
      <ul>
        <li><a href="#"><i class="fa-brands fa-square-facebook"></i></a></li>
        <li><a href="#"><i class="fa-brands fa-square-twitter"></i></a></li>
        <li><a href="#"><i class="fa-brands fa-square-instagram"></i></a></li>
        <li><a href="#"><i class="fa-brands fa-square-youtube"></i></a></li>
      </ul>

    </div>

  </div>



</template>



<style lang="scss" scoped>
.content {
  background-color: #272b34;
  text-align: center;
  padding: 20px;
}

.content_3 {
  text-align: center;

  h3 {
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
    color: #787787;

    &:hover {
      color: white;
    }
  }

}

.footer2 {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  align-items: center;
  background-color: #323843;

  ul {
    display: flex;

  }

  li {
    list-style-type: none;
    padding-left: 20px;
    color: #787787;
  }

  a {
    text-decoration: none;
    color: #787787
  }

  .fa-brands {
    font-size: 20px;
  }

}
</style>