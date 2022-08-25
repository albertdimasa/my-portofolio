<template>
  <div>
    <h1 v-if="error.statusCode === 404">Coming Soon!</h1>
    <h1 v-else>Something Error?</h1>
  </div>
</template>

<script>
export default {
  name: 'ErrorView',
  props: ['error'],
}
</script>

<style></style>
