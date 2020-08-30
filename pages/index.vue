<template>
  <div>
    <app-header />
    <app-progress />
    <app-education />
    <app-experience />
    <app-project />
    <app-footer />
  </div>
</template>

<script>
import appHeader from '@/components/header.vue'
import appProgress from '@/components/progress.vue'
import appEducation from '@/components/education.vue'
import appExperience from '@/components/experience.vue'
import appProject from '@/components/project.vue'
import appFooter from '@/components/footer.vue'

export default {
  components: {
    appHeader,
    appProgress,
    appEducation,
    appExperience,
    appProject,
    appFooter
  },
  head() {
    return {
      title: 'Yevhenii Moskalenko'
    }
  }
}
</script>

<style lang="scss" scoped></style>
