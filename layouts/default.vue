<template>
  <b-container>
    <Navbar />
    <Nuxt />
    <!-- <Footer /> -->
  </b-container>
</template>

<script>
export default {
  name: 'DefaultView',
}
</script>

<style>
body {
  background-color: #fff4cf;
  height: 100vh;
  width: 100%;
  font-family: 'Poppins', 'Inter', sans-serif;
}

#footer {
  font-size: 13px;
  font-family: 'Inter';
  /* position: fixed;
  bottom: 0; */
}
</style>
