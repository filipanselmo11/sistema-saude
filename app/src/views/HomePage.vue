<template>
  <div>
    <Navbar />
    <div class="container d-flex justify-content-around mt-5">
      <div class="card shadow-lg mr-5 mt-5" style="width: 18rem">
        <div class="card-body d-flex justify-content-center">
          <h5 class="card-title">SGEMBB</h5>
        </div>
        <a
          href="https://dapp-uea-v0-0-1-filipanselmo11.vercel.app/"
          class="btn btn-primary"
          >Acessar</a
        >
      </div>
      <div class="card shadow-lg mt-5"  style="width: 18rem;">
        <div class="card-body d-flex justify-content-center">
          <h5 class="card-title">Carteira de Vacina Digital</h5>
        </div>
        <a href="https://www.google.com/" class="btn btn-primary">Acessar</a>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "../components/Navbar";
export default {
  components: {
    Navbar,
  },
};
</script>

<style>
</style>