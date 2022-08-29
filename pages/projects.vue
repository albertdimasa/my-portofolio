<template>
  <div class="px-3">
    <h1 class="text-center pb-3 font-weight-bold">Projects</h1>
    <b-row class="d-flex justify-content-around">
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
          img: 'project-1.png',
          description:
            'Website kasir sederhana dengan 3 user yaitu pemilik, supplier, dan kasir. Beberapa fitur yang dimiliki yaitu fitur kasir, pencatatan barang keluar/masuk, print struk, dan export data ke excel.',
          link: '',
          tech_stack: [
            'html',
            'css',
            'javascript',
            'jquery',
            'php',
            'laravel',
            'bootstrap',
          ],
        },
        {
          id: 2,
          name: 'PSB Fatchul Ulum Pacet',
          img: 'project-2.png',
          description:
            'Website digunakan untuk pendaftaran santri baru dengan 2 user yaitu santri baru dan admin. Beberapa fitur yang dimiliki pendaftaran santri (CRUD) dan pembuatan surat keputusan daftar ulang berupa pdf.',
          link_demo: '//psb.fatchululumpacet.net',
          link_github: '',
          tech_stack: [
            'html',
            'css',
            'javascript',
            'jquery',
            'php',
            'laravel',
            'bootstrap',
          ],
        },
        {
          id: 3,
          name: 'Barter Book',
          img: 'project-3.png',
          description:
            'Website yang dibuat ketika mengikuti studi independen kampus merdeka tahun 2022 yang memiliki beberapa fitur yaitu autentikasi, pinjam-meminjam buku, dan mengelola buku.',
          link_demo: '//miniproject-albert.netlify.app/',
          link_github: '//github.com/albertdimasa/mini-project',
          tech_stack: [
            'html',
            'css',
            'javascript',
            'bootstrap-vue',
            'vuejs',
            'hasura',
            'graphql',
            'nuxtjs',
          ],
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
