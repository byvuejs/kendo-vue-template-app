<template>
  <div id="root">
      <div class="content">
          <Header :project-name="'Kendo UI'" />
          <router-view></router-view>
    </div>
    <div class="footer">
      <Footer />
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header';
import Footer from '@/components/Footer';

export default {
  name: 'app',
  components: {
    Header,
    Footer
  }
}
</script>

<style lang="scss">
@import '@/assets/styles/app.scss';
</style>
