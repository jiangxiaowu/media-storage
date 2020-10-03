<template>
  <div>
    <Header />
    <Lists />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/home/Header.vue'
import Lists from '@/components/home/Lists.vue'
import Footer from '@/components/home/Footer.vue'

export default {
  components: {
    Header,
    Lists,
    Footer
  }
}
</script>
