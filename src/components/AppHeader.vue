<script>
import AppMenu from './AppMenu.vue';
export default {
  name: 'AppHeader',

  components:{
    AppMenu
  }
}
</script>


<template>
  <div class="hContainer">
    <header>
      <img src="/avada-music-logo.png" alt="logo">
      <i class="fa-sharp fa-solid fa-bars"></i>
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
  height: 500px;
  background-image: url(../assets/home_slider.jpg);
  background-size: 100%;
  text-align: center;

  .fa-sharp {
    color: white;
    font-size: 30px;
  }

  .album,
  .date {
    height: 50px;
    margin: 6px;
    width: 130px;

    a {
      text-decoration: none;
      color: white;
    }

  }

  .album {
    background-color: #ea4a56;
  }

  .date {
    background-color: transparent;
  }



  header {
    padding: 30px;
    display: flex;
    justify-content: space-between;
  }


}
</style>