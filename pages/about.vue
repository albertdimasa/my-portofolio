<template>
  <div class="px-md-5">
    <h1 class="text-center pb-3 font-weight-bold">About</h1>
    <div class="mx-md-5 text-justify content">
      <p>
        Salam kenal👋 Aku Albert, seorang <i>fresh graduate</i> dari prodi
        informatika Universitas Internasional Semen Indonesia. Saat ini tengah
        menggeluti bidang <b>Web Developer</b>, baik itu <i>Backend</i> maupun
        <i>Frontend</i>.
      </p>
      <p>
        Saya pernah mengikuti studi independen kampus merdeka selama 6 bulan di
        Alterra Academy dengan program bernama
        <i>Understand Everything about Vue JS Front-End Engineer</i> untuk
        mempelajari <b>Vue Js</b>. Selain itu, saya mendapatkan pengalaman
        bekerja secara individu ataupun tim.
      </p>
      <p>
        Teknologi yang saya kuasai saat ini adalah <b>HTML</b>, <b>CSS</b>,
        <b>Javascript</b>, <b>JQuery</b>, dan <b>Laravel</b>. Selain itu, saya
        sedang mempelajari <b>Node Js</b> & <b>Vue Js</b>, begitu pula dengan
        <i>framework</i>-nya yaitu <b>Express Js</b> dan <b>Nuxt Js</b>.
        Database yang saya kuasai yaitu <b>MySQL</b> dan <b>MongoDB</b>.
      </p>
      <p>
        Saat ini, saya sedang mencari kesempatan untuk menjadi
        <i>Full-time</i> ataupun <i>Part-time Web Developer</i>. Berikut adalah
        <a href="https://s.id/AlbertCV" target="_blank">resume</a> mengenai
        saya.
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
