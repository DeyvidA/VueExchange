<template>
  <div class="container">

    <header-bar/>

    <router-view/>

    <footer-bar/>

  </div>
</template>

<script>

import HeaderBar from '../components/HeadeBar/Index.vue'
import FooterBar from '../components/FooterBar/index.vue'

export default {

  name: 'MainLayout',

  components: {
    HeaderBar,
    FooterBar
  }

}
</script>
