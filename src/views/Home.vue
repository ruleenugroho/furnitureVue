<template>
  <div class="home">
    <HeaderHijrah/>
    <HeroHijrah/>
    <ProductSlide/>
    <InstaPhoto/>
    <PartnerLogo/>
    <FooterHijrah/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderHijrah from '@/components/HeaderHijrah.vue'
import HeroHijrah from '@/components/HeroHijrah.vue'
import ProductSlide from '@/components/ProductSlide.vue'
import InstaPhoto from '@/components/InstaPhoto.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import FooterHijrah from '@/components/FooterHijrah.vue'

export default {
  name: 'Home',
  components: {
    HeaderHijrah,
    HeroHijrah,
    ProductSlide,
    InstaPhoto,
    PartnerLogo,
    FooterHijrah
  }
}
</script>
