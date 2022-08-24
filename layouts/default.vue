<template>
  <b-container>
    <div class="pt-4 pb-5">
      <Navbar />
    </div>
    <div class="px-3 py-5">
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
  background-color: #fff4cf;
  height: 100vh;
  width: 100%;
  font-family: 'Poppins', 'Inter', sans-serif;
}

#footer {
  position: fixed;
  font-size: 13px;
  font-family: 'Inter';
  left: 50%;
  bottom: 5px;
  transform: translate(-50%, -50%);
  margin: 0 auto;
}
</style>
