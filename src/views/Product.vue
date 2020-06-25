<template>
  <div class="product">
    <Header/>
    <Konten/>
  </div>
</template>
<script>
  import Header from '@/components/includes/Header.vue'
  import Konten from '@/components/pages/Product_Konten.vue'

  export default {
  components: {
    Header,
    Konten
  }
}
</script>
