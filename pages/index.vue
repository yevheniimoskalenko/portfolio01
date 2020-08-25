<template>
  <div>
    <app-header />
    <app-progress />
    <app-education />
  </div>
</template>

<script>
import appHeader from '@/components/header.vue'
import appProgress from '@/components/progress.vue'
import appEducation from '@/components/education.vue'

export default {
  components: {
    appHeader,
    appProgress,
    appEducation
  },
  head() {
    return {
      title: 'Yevhenii Moskalenko'
    }
  }
}
</script>

<style lang="scss" scoped></style>
