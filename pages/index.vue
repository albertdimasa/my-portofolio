<template>
  <div class="px-3 py-md-5">
    <b-row align-v="center">
      <b-col md="4" sm="12">
        <b-img
          thumbnail
          fluid
          src="~/static/home.jpg"
          alt="Me"
          rounded="circle"
          width="300"
          height="300"
        ></b-img>
      </b-col>
      <b-col md="8" sm="12">
        <p class="text-muted">Web Developer | SAP ABAP Programmer</p>
        <h3 class="font-weight-bold">Dimas Albert Abraham</h3>
        <p id="desc" class="text-justify">
          Seorang yang suka mengulik tentang website dan saat ini tengah
          mendalami Laravel, VueJS dan Bun. Selain itu pernah magang di
          startup maupun freelance. Bekerja secara tim ataupun individu juga
          tidak masalah.
        </p>
        <div id="sosmed" class="d-flex">
          <a
            href="https://www.linkedin.com/in/dimas-albert-abraham/"
            target="_blank"
            class="text-primary"
            >Linkedin</a
          >
          <a
            href="https://www.instagram.com/albertdimasa"
            target="_blank"
            class="text-danger"
            >Instagram</a
          >
          <a
            href="https://twitter.com/nyosjes"
            target="_blank"
            class="text-info"
            >Twitter</a
          >
        </div>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  head() {
    return {
      title: 'Albert - My Portfolio',
    }
  },
}
</script>
<style scoped>
#sosmed {
  gap: 10px;
}

#desc {
  font-size: 15px;
  line-height: 27px;
}
</style>
