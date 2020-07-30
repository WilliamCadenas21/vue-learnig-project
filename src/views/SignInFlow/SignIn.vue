<template>
  <div class="container">
    <div class="login">
      <img src="@/assets/logoOne.png" />
      <h4>Sign into Design+Code HQ</h4>
    </div>
  </div>
</template>

<script>
export default {
  name: "Signin"
};
</script>

<style lang="scss" scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;

  min-height: 100vh;
}
.login {
}

h4 {
  margin: 0;
  font-size: 24px;
  line-height: 34px;
  /* identical to box height */
  text-align: center;
  /* white */
  color: #ffffff;
}
</style>