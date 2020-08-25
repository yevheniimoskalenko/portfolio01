<template>
  <div class="progress">
    <div class="header">
      <h3>Progress</h3>
      <span>My work progress</span>
    </div>
    <el-row :gutter="30">
      <el-col :span="8">
        <el-card shadow="hover">
          <div class="progress__skill">
            <el-progress type="circle" :percentage="65" />
            <span>JavaScript</span>
          </div></el-card
        >
      </el-col>
      <el-col :span="8"
        ><el-card shadow="hover">
          <div class="progress__skill">
            <el-progress type="circle" :percentage="85" />
            <span>html+css</span>
          </div>
        </el-card></el-col
      >
      <el-col :span="8"
        ><el-card shadow="hover">
          <div class="progress__skill">
            <el-progress type="circle" :percentage="60" />
            <span>node.js</span>
          </div></el-card
        ></el-col
      >
    </el-row>
    <p>It's not my maximum, i don't know how many, I`am have</p>
  </div>
</template>

<style lang="scss" scoped>
.progress {
  padding: 30px;
  text-align: center;
}
.progress__skill {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  span {
    padding: 20px;
  }
}
</style>
