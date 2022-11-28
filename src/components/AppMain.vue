<script>
import AppPhotoCardsVue from './AppPhotoCards.vue';

export default {
  name: 'AppMain',
  components: {
    AppPhotoCardsVue
  }
}
</script>

<template>
  <div class="mContainer">
    <div class="content_1">
      <h2>Music Is Life</h2>

      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores, veniam!</p>
    </div>

    <div class="content_2">
      <h2>Latest Band News</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur repudiandae quas error et beatae! Placeat.
      </p>

      <div class="box">
        <div class="column1">
          <AppPhotoCardsVue />
        </div>
        <div class="column2">
          <div class="row1">
            <div class="ccc">
              <img src="../assets/blog-post1.jpg" alt="" class="img_full_width" />
              <div class="card_text">
                <h4>Taking it back to the old school</h4>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Commodi, corporis.</p>
              </div>
            </div>
          </div>
          <div class="row2">
            <div class="ccc">
              <img src="../assets/blog-post2.jpg" alt="" class="img_full_width" />
              <div class="card_text">
                <h4>Sharing the stage with a legend</h4>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Commodi, corporis.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="content_3">
        <h3>VIEW ALL LATEST NEWS</h3>
      </div>

      <div class="content_4">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi voluptatum repellat veritatis, sunt voluptas
          porro aspernatur possimus facere nemo nobis doloribus labore dicta accusantium similique nulla aperiam fugit
          recusandae asperiores reprehenderit dignissimos. Sapiente iusto soluta quas placeat voluptatum error illo!
          Dolores maiores ex perspiciatis voluptas rem eos ea autem sint!</p>
        <img src="../assets/band_interview_play_icon.png" alt="play">

      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.mContainer {
  text-align: center;

  .content_1 {
    background-color: #323843;
    padding: 20px;


  }

  .content_2 {
    background-color: #272b34;


    .box {
      width: 60%;
      height: 100%;
      display: flex;
      margin: 0 auto;
      padding: 16px;
    }

    .column1 {
      width: 70%;
    }

    .column2 {
      width: 30%;
    }
  }

  h3 {
    line-height: 100px
  }

  .content_4 {
    background-image: url(../assets/home-testimonial-parallax.jpg);
    height: 400px;
    background-size: 100%;

    img {
      width: 40px;
      height: 40px;
      border-radius: 50%;

    }

  }

  .img_full_width {
    object-fit: cover;
    width: 100%;
    height: 100%;
  }
}
</style>