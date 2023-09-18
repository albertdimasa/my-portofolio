<template>
  <div class="px-md-5">
    <h1 class="text-center pb-3 font-weight-bold">About</h1>
    <div class="mx-md-5 text-justify content">
      <p>
        Salam kenal👋 Aku Albert, seorang <i>fresh graduate</i> dari prodi
        informatika, Universitas Internasional Semen Indonesia. Saat ini tengah
        menggeluti bidang <b>Web Developer</b>, baik itu <i>Backend</i> maupun
        <i>Frontend</i>. Saat ini aku sedang bekerja di bidang <i>SAP</i>. 
      </p>
      <p>
        Pelatihan yang pernah aku ikuti yaitu studi independen kampus merdeka 
        selama 6 bulan di Alterra Academy dengan program bernama
        <i>Understand Everything about Vue JS Front-End Engineer</i> yang bertujuan
        untuk mempelajari <b>Vue Js</b> dan <b>Nuxt Js</b>. Setelah pembelajaran selesai,
        diberikan case yang dikerjakan secara berkelompok dengan bagian lainnya.
      </p>
      <p>
        Teknologi yang aku kuasai saat ini adalah <b>HTML</b>, <b>CSS</b>,
        <b>Javascript</b>, <b>JQuery</b>, <b>PHP Laravel Livewire</b>, <b>ABAP</b>, dan <b>SQL</b>. 
        Selain itu, aku juga sedang belajar <b>Node Js</b> & <b>Vue Js</b>, 
        beserta dengan <i>framework</i>-nya yaitu <b>Express Js</b> dan <b>Nuxt Js</b>.
      </p>
      <p> 
        Berikut adalah <a href="https://s.id/AlbertCV" target="_blank">resume</a> mengenai diriku.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutView',
}
</script>

<style scoped>
p {
  font-family: 'Inter';
}

.content {
  padding: 0 5rem;
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
