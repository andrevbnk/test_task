<template>
  <div class="home">
    <Header />
    <Banner />
    <Laptop />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '../components/Banner.vue';
import Laptop from '../components/Laptop.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Banner,
    Laptop,
  }
}
</script>
