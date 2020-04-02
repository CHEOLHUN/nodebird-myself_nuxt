<template>
  <form class="LoginForm__container">
    <input placeholder="Email" type="email" />
    <input placeholder="Password" type="password" />
    <input type="button" value="로그인" />
  </form>
</template>

<script>
export default {};
</script>

<style scoped>
.LoginForm__container {
  width: 100%;
  height: 300px;
  padding: 10px;
  display: flex;
  flex-direction: column;
  background-color: #f8eeee;
}
</style>
