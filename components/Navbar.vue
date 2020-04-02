<template>
  <nav class="Navbar__container">
    <div class="Navbar__container__left">
      <nuxt-link to="/">NodeBrid</nuxt-link>
    </div>
    <div class="Navbar__container__right">
      <div>
        <img class="Navbar__icon" src="@/assets/search-solid.svg" alt="search icon" />
        <input placeholder="검색" type="text" />
      </div>
      <nuxt-link to="/signup">회원가입</nuxt-link>
      <nuxt-link to="/profile">프로필</nuxt-link>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.Navbar__container {
  background: #827397;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 50px;
  font-weight: 600;
}

.Navbar__container a {
  text-decoration: none;
  color: #d8b9c3;
}
.Navbar__container__left,
.Navbar__container__right {
  padding: 10px;
}

.Navbar__container__right {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 400px;
}

.Navbar__container__right input {
  border: none;
  background-color: #827397;
  border-bottom: 1px solid #d8b9c3;
}

.Navbar__container__right input::placeholder {
  color: #d8b9c3;
}

.Navbar__icon {
  width: 20px;
  height: 20px;
  margin-right: 10px;
  fill: #d8b9c3;
}
</style>
