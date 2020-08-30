<template>
  <div class="education">
    <div class="wrapper">
      <div class="title">
        <h3>Education</h3>
        <p>Where i`am studied</p>
      </div>
      <el-timeline>
        <el-timeline-item
          timestamp="September 2013 / June 2017"
          placement="top"
        >
          <el-card>
            <h2>Poltava Technical College</h2>
            <span>junior bachelor's diploma</span>
            <p>software development</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item
          timestamp="September 2017 / June 2019"
          placement="top"
        >
          <el-card>
            <h2>Simon Kuznets Kharkiv National University of Economics</h2>
            <span>Bachelor's degree</span>
            <p>Computer Science</p>
          </el-card>
        </el-timeline-item>
        <el-timeline-item
          timestamp="September 2019 / December 2020"
          placement="top"
        >
          <el-card>
            <h2>Simon Kuznets Kharkiv National University of Economics</h2>
            <span>Master's degree</span>
            <p>Cyber security</p>
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
.education {
  padding: 30px;
}
</style>
