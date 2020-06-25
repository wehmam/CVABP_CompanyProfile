<template>
  <div class="home">
    <Header/>
    <Konten/>
    <!-- <Footer/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/includes/Header.vue'
import Konten from '@/components/pages/Home_Konten.vue'

// import Footer from '@/components/includes/Footer.vue'


export default {
  name: 'Home',
  components: {
    Header,
    Konten,
    // Footer
  }
}
</script>
