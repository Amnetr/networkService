<template>
  <div class="main-containt">
    <div class="swipper-content">
      <swipper></swipper>
    </div>
  </div>
</template>

<script>
import swipper from '@/components/swipper.vue'
export default {
  name: 'login',
  data () {
    return {
    }
  },
  methods: {
  },
  components: {
    swipper
  }
}
</script>

<style lang="stylus">
.main-containt
  height: 96%
  width: 100%
  border: 1px solid blue
  margin: 0 auto
</style>
