<template>
  <b-container>
    <Navbar />
    <div class="wrapper">
      <Nuxt />
    </div>
    <Footer />
  </b-container>
</template>

<script>
export default {
  name: 'DefaultView',
}
</script>

<style>
body {
  background-color: #F2E8C6;
  /* color: #F5F5DC; */
  min-height: 100vh;
  width: 100%;
  font-family: 'Poppins', 'Inter', sans-serif;
}
.wrapper {
  min-height: calc(100vh - 11rem);
}
</style>
