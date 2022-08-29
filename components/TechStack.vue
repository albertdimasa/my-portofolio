<template>
  <b-badge id="item-tech" class="mr-1 mb-1 font-weight-normal p-2">{{
    techstack
  }}</b-badge>
</template>

<script>
export default {
  name: 'TechStackItem',
  props: ['techstack'],
}
</script>

<style scoped>
#item-tech {
  background-color: #f66767;
  text-transform: uppercase;
  font-size: 0.7rem;
}
</style>
