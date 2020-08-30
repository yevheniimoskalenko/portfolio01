<template>
  <div class="footer">
    <div class="wrapper">
      <div class="footer__list">
        <div class="footer__item">
          <a
            href="https://www.linkedin.com/in/yevhenii-moskalenko"
            target="_blank"
            ><i class="el-icon-link"></i>linkedin</a
          >
        </div>
        <div class="footer__item">
          <a
            href="https://www.facebook.com/profile.php?id=100010074134221"
            target="_blank"
            ><i class="el-icon-link"></i>facebook</a
          >
        </div>
        <div class="footer__item">
          <a
            href="https://www.instagram.com/yevhenii.moskalenko/"
            target="_blank"
            ><i class="el-icon-link"></i>instagram</a
          >
        </div>
        <div class="footer__item">
          <a
            href="https://drive.google.com/file/d/12I-9o0tzaTxyA2cbNUhO5LOzZwHxk_l_/view?usp=sharing"
            target="_blank"
            ><i class="el-icon-link"></i>CV</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.footer {
  display: flex;
  justify-content: center;
  height: 150px;
  background: linear-gradient(183.41deg, #67c3f3 -8.57%, #5a98f2 82.96%);
}
.footer__list {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  .footer__item {
    a {
      color: #fff;
      text-decoration: none;
    }
  }
}
@media (max-width: 576px) {
  .footer__item {
    padding: 0px 5px;
    a {
      font-size: 14px;
    }
  }
}
@media (min-width: 576px) {
  .footer__item {
    padding: 0px 5px;
  }
}
</style>
