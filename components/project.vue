<template>
  <div class="project">
    <div class="wrapper">
      <div class="title">
        <h3>Project</h3>
        <p>My projects</p>
      </div>
      <div class="content_project">
        <div class="list_project">
          <el-row :gutter="10">
            <el-col :span="8" :xs="24">
              <div class="item_project">
                <el-card shadow="always" :body-style="{ padding: '0px' }">
                  <el-image
                    src="https://res.cloudinary.com/dmrpkseez/image/upload/v1598702062/3_wuymyz.png"
                    lazy
                    class="image"
                  ></el-image>
                  <div class="project__title">
                    <h2>My fake portfolio</h2>
                    <p>My first staps in vue</p>
                  </div>
                </el-card>
              </div>
            </el-col>
            <el-col :span="8" :xs="24">
              <div class="item_project">
                <el-card shadow="always" :body-style="{ padding: '0px' }">
                  <el-image
                    src="https://res.cloudinary.com/dmrpkseez/image/upload/v1598702063/2_dfu1gr.jpg"
                    lazy
                    class="image"
                  ></el-image>
                  <div class="project__title">
                    <h2>My statistic covid 19</h2>
                    <p>Statistic for Ukraine covid 19</p>
                  </div>
                </el-card>
              </div>
            </el-col>
            <el-col :span="8" :xs="24">
              <div class="item_project">
                <el-card shadow="always" :body-style="{ padding: '0px' }">
                  <el-image
                    src="https://res.cloudinary.com/dmrpkseez/image/upload/v1598702063/1_p6p1fs.jpg"
                    lazy
                    class="image"
                  ></el-image>
                  <div class="project__title">
                    <h2>My template covid 19</h2>
                    <p>Template covid 19</p>
                  </div>
                </el-card>
              </div>
            </el-col>
          </el-row>
        </div>
        <div class="footer_project">
          <a href=" https://github.com/yevheniimoskalenko">
            <el-button type="primary" plain round>View all</el-button>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.footer_project {
  margin: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  a {
    margin-top: 50px;
  }
}
.project__title {
  padding: 20px;
  h2 {
    font-weight: bold;
  }
  p {
    color: #7d7987;
  }
}
.item_project {
  margin-top: 20px;
}
.el-card {
  display: flex;
  max-height: auto;
  .image {
    height: 300px;
    overflow: hidden;
  }
}
.el-row {
  display: block;
  justify-content: center;
  align-items: center;
}
</style>
