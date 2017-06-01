<template>
  <div id="app">
      <tou></tou>
      <dh></dh>
      <zhu></zhu>
      <zu></zu>

  </div>
</template>

<script>
import zhu from './component/main.vue'
import tou from './component/head.vue'
import dh from './component/nav.vue'
import zu from './component/footer.vue'
export default {
    components: { zhu, tou, dh, zu }
}

</script>

<style>


</style>
