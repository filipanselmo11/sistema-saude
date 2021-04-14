<template>
  <div id="app">
    <router-view />
    <div class="d-flex justify-content-center">
      <div
        class="spinner-border"
        style="
          width: 10rem;
          height: 10rem;
          position: fixed;
          top: 40%;
          left: 45%;
        "
      ></div>
    </div>
  </div>
</template>

<style>
body {
  background-image: url("../public/images/background.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
}
</style>
