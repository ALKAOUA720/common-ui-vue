<script setup lang="ts">
const gotoGithub = () => {
  window.open('https://github.com/ALKAOUA720/common-ui-vue');
};
</script>

<template>
  <div class="top-box">
    <div class="top-box-title">Common UI - Vue</div>
    <img class="github-enter" src="../assets/github.png" @click="gotoGithub" />
  </div>
</template>

<style scoped lang="less">
.top-box {
  display: flex;
  justify-content: space-between;
  align-items: center;

  &-title {
    margin: 10px;
    margin-bottom: 0;
    font-size: 28px;
    font-weight: bold;
    color: rgba(0, 0, 0, 0.8);
  }

  .github-enter {
    width: 50px;
    height: 50px;
    cursor: pointer;
  }
}

&-content {
  display: flex;
  justify-content: space-between;
}

&-line {
  width: 100%;
  margin: 10px;
}
</style>
