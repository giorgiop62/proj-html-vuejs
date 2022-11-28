<script>
export default {
  name: 'AppPhotoCard'

}
</script>

<template>
  <div class="row1">
    <div class="ccc">
      <img src="../assets/blog_music_techo.jpg" alt="blog music techno" class="img_righe_pari" />
      <div class="card_text">
        <h4>Tecnology and music</h4>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Commodi, corporis.</p>
      </div>
    </div>
  </div>
  <div class="row2">
    <div class="column1">
      <div class="ccc">
        <img src="../assets/blog-post3.jpg" alt="" class="img_righe_dispari" />
        <div class="card_text">
          <h4>While my guitar gently weeps</h4>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Commodi, corporis.</p>
        </div>
      </div>
    </div>
    <div class="column2">
      <div class="ccc">
        <img src="../assets/blog-post4.jpg" alt="" class="img_righe_dispari" />
        <div class="card_text">
          <h4>It just sounds better</h4>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Commodi, corporis.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="row3">
    <div class="ccc">
      <img src="../assets/blog_flavor_rock.jpg" alt="" class="img_righe_pari" />
      <div class="card_text">
        <h4>The flavor of rock</h4>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Commodi, corporis.</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.row2 {
  display: flex;
  text-align: unset;

  .column1 {
    width: 60%;
  }

  .column2 {
    width: 40%;
  }
}

.img_righe_pari {
  object-fit: cover;
  width: 100%;
  height: 256px;
}

.img_righe_dispari {
  object-fit: cover;
  width: 100%;
  height: 512px;
}
</style>