<template>
  <b-card
    :title="project.name"
    img-src="https://picsum.photos/600/300/?image=25"
    img-alt="Image"
    img-top
    tag="article"
    class="mb-2 project-card"
  >
    <b-card-text class="text-description text-justify">
      {{ project.description }}
    </b-card-text>

    <b-button
      v-if="project.link_demo"
      :href="project.link_demo"
      target="_blank"
      variant="primary"
      pill
      >Demo
    </b-button>
    <b-button
      v-if="project.link_github"
      :href="project.link_github"
      target="_blank"
      variant="dark"
      pill
      >Github
    </b-button>
  </b-card>
</template>

<script>
export default {
  name: 'ProjectItem',
  props: ['project'],
}
</script>

<style scoped>
.text-description {
  font-family: sans-serif;
}

.project-card {
  max-width: 30rem;
  margin-top: 20px;
}
</style>
