<template>
  <div class="progress">
    <div class="wrapper">
      <div class="title">
        <h3>Progress</h3>
        <p>My work progress</p>
      </div>
      <el-row :gutter="30">
        <el-col :span="6" :xs="24" :sm="12" :md="6">
          <div class="item_progress">
            <el-card shadow="hover">
              <div class="progress__skill">
                <el-progress type="circle" :percentage="65" color="#30BAE7" />
                <span>JavaScript</span>
              </div>
            </el-card>
          </div>
        </el-col>
        <el-col :span="6" :xs="24" :sm="12" :md="6">
          <div class="item_progress">
            <el-card shadow="hover">
              <div class="progress__skill">
                <el-progress type="circle" :percentage="85" color="#D8567F" />
                <span>html+css</span>
              </div>
            </el-card>
          </div>
        </el-col>
        <el-col :span="6" :xs="24" :sm="12" :md="6">
          <div class="item_progress">
            <el-card shadow="hover">
              <div class="progress__skill">
                <el-progress type="circle" :percentage="60" color="#EB7D4B" />
                <span>node.js</span>
              </div>
            </el-card>
          </div>
        </el-col>
        <el-col :span="6" :xs="24" :sm="12" :md="6">
          <div class="item_progress">
            <el-card shadow="hover">
              <div class="progress__skill">
                <el-progress type="circle" :percentage="85" color="#5AC8A9" />
                <span>vue.js</span>
              </div>
            </el-card>
          </div>
        </el-col>
      </el-row>
    </div>
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
  p {
    padding: 20px;
  }
  span {
    padding-top: 20px;
  }
}
.item_progress {
  margin-top: 20px;
}
</style>
