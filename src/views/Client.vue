<template>
  <div class="client">
    <Header/>
    <Konten/>
  </div>
</template>
<script>
  import Header from '@/components/includes/Header.vue'
  import Konten from '@/components/pages/Client_Konten.vue'

  export default {
  components: {
    Header,
    Konten
  }
}
</script>
