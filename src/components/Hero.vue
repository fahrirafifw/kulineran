<template>
  <div class="row mt-4">
    <div class="col">
      <div class="d-flex h-100">
        <div class="justify-content-center align-self-center">
          <h2><strong>Delicious Food Menu, </strong> <br />in Your Gadget</h2>
          <p>Ayo Segera Pilih dan Pesan Makanan Favorit Anda</p>
          <router-link
            to="/"
            class="btn btn-lg btn-success d-flex align-items-center justify-content-center"
          >
          <b-icon-check-circle-fill size="sm" class="me-2"></b-icon-check-circle-fill>
        
            Pesan
            
          </router-link>
        </div>
      </div>
    </div>
    <div class="col">
      <img src="../assets/images/hero.png" width="100%" />
    </div>
  </div>
</template>

<script>
export default {
  name: "HeroTemp",
};
</script>

<style>
</style>