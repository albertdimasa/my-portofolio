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
            'Website kasir sederhana dengan 3 user yaitu pemilik, supplier, dan kasir. Beberapa fitur yang dimiliki yaitu fitur kasir, pencatatan barang keluar/masuk, print struk, dan export data ke excel. Projek dikerjakan kurang lebih 1 bulan.',
          link: '',
          tech_stack: [
            'jquery',
            'laravel',
            'bootstrap',
            'mysql',
          ],
        },
        {
          id: 2,
          name: 'PSB Fatchul Ulum Pacet',
          img: 'project-2.png',
          description:
            'Website digunakan untuk pendaftaran santri baru dengan 2 user yaitu santri baru dan admin. Beberapa fitur yang dimiliki pendaftaran santri (CRUD) dan pembuatan surat keputusan daftar ulang berupa pdf. Projek dikerjakan kurang lebih 2 minggu.',
          link_demo: '//psb.fatchululumpacet.net',
          link_github: '',
          tech_stack: [
            'jquery',
            'laravel',
            'bootstrap',
            'mysql',
          ],
        },
        {
          id: 3,
          name: 'Barter Book',
          img: 'project-3.png',
          description:
            'Website yang dibuat ketika mengikuti studi independen kampus merdeka tahun 2022 yang memiliki beberapa fitur yaitu autentikasi, pinjam-meminjam buku, dan mengelola buku. Projek ini dikerjakan kurang lebih 2 minggu.',
          link_demo: '//miniproject-albert.netlify.app/',
          link_github: '//github.com/albertdimasa/mini-project',
          tech_stack: [
            'bootstrap-vue',
            'nuxtjs',
            'hasura',
            'graphql',
          ],
        },
        {
          id: 4,
          name: 'Tukerin',
          img: 'project-4.png',
          description:
            'Website yang digunakan untuk barter barang yang dimiliki user. Fitur yang ada yaitu autentikasi, CRUD barang, barter, dan dashboard. Projek ini dikerjakan kurang lebih 2 minggu.',
          link_demo: '',
          link_github: '',
          tech_stack: [
            'jquery',
            'laravel',
            'bootstrap',
            'mysql'
          ],
        },
        {
          id: 5,
          name: 'Buku Kas Sederhana',
          img: 'project-5.png',
          description:
            'Website yang digunakan untuk buku kas pada perusahaan yang ada di Jakarta Barat dengan fitur sederhan yang ada yaitu CRUD pekerja, pemasukan, pengeluaran, tagihan, dan laporan. Projek ini dikerjakan kurang lebih 2 minggu.',
          link_demo: '',
          link_github: '',
          tech_stack: [
            'jquery',
            'laravel',
            'bootstrap',
            'mysql'
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
