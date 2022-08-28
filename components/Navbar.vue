<template>
  <b-navbar toggleable="lg" class="pt-4 pb-5">
    <b-navbar-brand to="/">Home.</b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-navbar-nav>
          <b-nav-item to="/blog">Blog</b-nav-item>
          <b-nav-item to="/about">About</b-nav-item>
          <b-nav-item to="/projects">Projects</b-nav-item>
          <b-nav-item to="/contact">Contact Me</b-nav-item>
        </b-navbar-nav>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
  name: 'NavbarItem',
}
</script>

<style></style>
