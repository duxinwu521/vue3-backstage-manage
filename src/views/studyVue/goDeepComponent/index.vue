<!-- 深入组件 -->
<template>
  <RouteContents :route-obj="goDeepComponent" />
</template>

<script>
import { defineComponent } from 'vue'
import RouteContents from '@/components/routeContents.vue'
import goDeepComponent from '@/router/modules/studyVue/goDeepComponent.js'

export default defineComponent({
  name: 'GoDeepComponent',

  components: {
    RouteContents
  },

  setup() {
    return {
      goDeepComponent
    }
  }
})
</script>

<style lang="scss" scoped></style>
