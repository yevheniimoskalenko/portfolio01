<template>
  <div>
    <app-header />
  </div>
</template>

<script>
import appHeader from '@/components/header.vue'
export default {
  components: {
    appHeader
  },
  data() {
    return {}
  },
  head() {
    return {
      title: 'Yevhenii Moskalenko'
    }
  }
}
</script>

<style lang="scss" scoped></style>
