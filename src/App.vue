<template>
<!-- 全局header -->
<nv-head></nv-head>
 <!-- main view -->
    <router-view
      class="view"
      keep-alive
      transition
      transition-mode="out-in">
    </router-view>
<nv-footer></nv-footer>
</template>
<script>
  export default {
    components: {
      "nvHead":require('./components/header.vue'),
      "nvFooter":require('./components/footer.vue')
    }
  }
</script>
