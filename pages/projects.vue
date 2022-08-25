<template>
  <div>
    <h1 class="text-center pb-3">Project</h1>
    <b-row class="d-flex justify-content-around">
      <!-- Card Biasa Aja deh -->
      <Project
        v-for="(project, index) in projects"
        :key="project.id"
        :project="project"
        :index="index"
      />
    </b-row>
  </div>
</template>

<script>
export default {
  name: 'ProjectsView',
  data() {
    return {
      projects: [
        {
          id: 1,
          name: 'Alter Admin',
          img: '',
          description:
            'Website kasir sederhana dengan 3 user yaitu pemilik, supplier, dan kasir. Beberapa fitur yang dimiliki yaitu fitur kasir, pencatatan barang keluar/masuk, print struk, dan export data ke excel.',
          link: '',
        },
        {
          id: 2,
          name: 'PSB Fatchul Ulum Pacet',
          img: '',
          description:
            'Website digunakan untuk pendaftaran santri baru dengan 2 user yaitu santri baru dan admin. Beberapa fitur yang dimiliki pendaftaran santri (CRUD) dan pembuatan surat keputusan daftar ulang berupa pdf.',
          link_demo: '//psb.fatchululumpacet.net',
          link_github: '',
        },
        {
          id: 3,
          name: 'Barter Book',
          img: '',
          description:
            'Website yang dibuat ketika mengikuti studi independen kampus merdeka tahun 2022 yang memiliki beberapa fitur yaitu autentikasi, pinjam-meminjam buku, dan mengelola buku.',
          link_demo: '//miniproject-albert.netlify.app/',
          link_github: '//github.com/albertdimasa/mini-project',
        },
      ],
    }
  },
  head() {
    return {
      title: 'Projects - Albert',
    }
  },
}
</script>

<style></style>
