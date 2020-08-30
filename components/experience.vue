<template>
  <div class="experience">
    <div class="wrapper">
      <div class="title">
        <h3>Experience</h3>
        <p>where i`am taken experience</p>
      </div>
      <el-timeline>
        <el-timeline-item
          timestamp="January 2016 / February 2016"
          placement="top"
        >
          <el-card>
            <h2>Beetroot</h2>
            <span>Front end</span>
            <p>Front end Developer</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item timestamp="October / December" placement="top">
          <el-card>
            <h2>Microsoft IT Academy at KNUE</h2>
            <span>Courses</span>
            <p>Passed the course Programming with C#</p>
          </el-card>
        </el-timeline-item>
      </el-timeline>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.experience {
  padding: 20px;
}
</style>
