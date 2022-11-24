<script>
export default {
  name:'AppHeader'
}
</script>


<template>
  <div class="hContainer">
    <header>
      <img src="/avada-music-logo.png" alt="logo">
      <button id="menu">X</button>
    </header>
    <h1>Untold Stories</h1>
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <button class="album"><a href="#">Latest Album</a></button>
    <button class="date"><a href="#">Live Dates</a></button>

  </div>


  
  
</template>



<style lang="scss" scoped>
.hContainer {
  width: 100%;
  height: 100vh;
  background-image: url(../assets/home_slider.jpg);
  background-size: cover;
  object-fit: cover;
  text-align: center;

    .album, .date {
      height: 50px;
      margin: 6px;
      width: 130px;

      a{
        text-decoration: none;
        color: white;
      }

    }
    .album {
      background-color: #ea4a56;
    }
   


    header {
    padding: 30px;
    display: flex;
    justify-content: space-between;
  }


}


</style>