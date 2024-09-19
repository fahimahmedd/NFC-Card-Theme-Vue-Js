<template>
  <q-page>
    <Header/>
    <Hero/>
    <Introduce/>
    <Mobile/>
    <Buy/>
    <Dark/>
    <Testimonial/>
    <Footer/>
    <!-- class="flex flex-center" -->
  </q-page>
</template>

<script>
import Header from 'src/components/Header.vue';
import Buy from 'src/components/IndexComponent/Buy.vue';
import Dark from 'src/components/IndexComponent/Dark.vue';
import Footer from 'src/components/IndexComponent/Footer.vue';
import Hero from 'src/components/IndexComponent/Hero.vue';
import Introduce from 'src/components/IndexComponent/Introduce.vue';
import Mobile from 'src/components/IndexComponent/Mobile.vue';
import Testimonial from 'src/components/IndexComponent/Testimonial.vue';
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'IndexPage',
    components: { Header, Hero, Introduce, Mobile, Buy, Dark, Testimonial, Footer }
})
</script>
