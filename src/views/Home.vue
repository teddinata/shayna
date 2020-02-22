<template>
  <div class="home">
   <HeaderShayna />
   <CarouselShayna />
   <ProductShayna />
    <InstaShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import CarouselShayna from '@/components/CarouselShayna.vue'
import ProductShayna from '@/components/ProductShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'


export default {
  name: 'Home',
  components: {
    HeaderShayna,
    CarouselShayna,
    ProductShayna,
    InstaShayna,
    FooterShayna
}
}
</script>
