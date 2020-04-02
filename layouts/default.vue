<template>
  <div class="layout">
    <header class="layout__header">
      <navbar />
    </header>
    <div class="layout__body">
      <aside class="layout__login-form">
        <login-form />
      </aside>
      <main class="layout__content">
        <nuxt />
      </main>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import LoginForm from "@/components/LoginForm.vue";

export default {
  components: {
    Navbar,
    LoginForm
  }
};
</script>

<style scoped>
.layout{
  width: 100%;
}
.layout__header{
  width: 100%;
}
.layout__body {
  display: flex;
}

.layout__login-form {
  width: 33%;
  margin-right: 10px;
}

.layout__content {
  widows: 66%;
}
</style>
