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
  background-color: #f9d5bb;
  min-height: 100vh;
  width: 100%;
  font-family: 'Poppins', 'Inter', sans-serif;
}
.wrapper {
  min-height: calc(100vh - 11rem);
}
</style>
