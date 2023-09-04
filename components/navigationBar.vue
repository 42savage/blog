<template>
  <div class="navWrapper">
    <button><icons-searchIcon /></button>
    <p class="logo"><b>dev</b>blog</p>
    <button><icons-hamburgerIcon /></button>
  </div>
</template>
<script>
export default {};
</script>
<style scoped lang="scss">
button {
  border: none;
  background: #222222;
  border-radius: 50px;
  width: 32px;
  height: 32px;
}
.navWrapper {
  padding: 40px 24px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.logo {
  font-size: 24px;
}
</style>
