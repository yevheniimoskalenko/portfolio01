<template>
  <div class="header">
    <div class="background">
      <div class="profile">
        <div class="avatar">
          <el-avatar :size="150" :src="url" />
        </div>
        <div class="name">
          <span>Yevhenii Moskalenko</span>
          <small>Full stack vue.js & node.js</small>
          <p>
            Hi, my name is Yevhenii, I`am from Ukraine, I live in city Kharkiv,
            I`am 23 years old, I like web development, namely vue.js and node.js
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      url:
        'https://res.cloudinary.com/dmrpkseez/image/upload/v1598355171/image_ahstla.png'
    }
  }
}
</script>

<style lang="scss" scoped>
.avatar {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px 0;
}
.header {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;
  background: url('~assets/header.jpg') no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  .background {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    background: #29292a48;
  }
  .profile {
    .name {
      color: #fff;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      span {
        font-size: 72px;
        font-family: 'Bebas Neue', cursive;
        line-height: 73px;
        &::after {
          content: '';
          display: flex;
          margin: auto;
          width: 150px;
          height: 2px;
          background: #192624;
        }
      }
      small {
        line-height: 50px;
        font-size: 36px;
        font-family: 'Quicksand', sans-serif;
      }
    }
  }
}
</style>
