<template>
  <div class="px-md-5">
    <h1 class="text-center pb-3 font-weight-bold">Contact Me</h1>
    <div class="mx-md-5 text-justify content">
        <b-form>
            <b-form-group
            id="input-group-1"
            label="Nama"
            label-for="input-1"
        >
            <b-form-input
            id="input-1"
            type="text"
            placeholder="Nama"
            required
            ></b-form-input>
        </b-form-group>
        <b-form-group
            id="input-group-2"
            label="Email"
            label-for="input-2"
        >
            <b-form-input
            id="input-2"
            type="email"
            placeholder="Email"
            required
            ></b-form-input>
        </b-form-group>
        <b-form-group
            id="input-group-3"
            label="Pesan"
            label-for="input-3"
        >
            <b-form-textarea
            id="input-3"
            type="text"
            placeholder="Pesan"
            rows="3"
            max-rows="6"
            required
            ></b-form-textarea>
        </b-form-group>
        <b-button type="submit" variant="primary">Submit</b-button>
        </b-form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
}
</script>

<style scoped>
p {
  font-family: 'Inter';
}

.content {
  padding: 0 10rem;
  line-height: 1.7;
}

@media only screen and (max-width: 990px) {
  .content {
    padding: 0 0.5rem;
  }
}

@media only screen and (max-width: 767px) {
  .content {
    padding: 0 1.5rem;
  }
}
</style>