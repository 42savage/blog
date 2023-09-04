<template>
  <main>
    <p class="title">Ostatnie posty</p>
    <div class="content">
      <singlePostCard />
      <button class="loadMoreButton">Załaduj więcej postów</button>
    </div>
  </main>
</template>

<script>
export default {};
</script>
<style scoped lang="scss">
main {
  padding: 54px 24px 24px 24px;
}
.title {
  font-size: 24px;
  font-weight: bold;
  margin: 24px 0;
}
.loadMoreButton {
  background: #333333;
  padding: 12px;
  margin-top: 80px;
  border: none;
  border-radius: 8px;
  color: white;
}
.content {
  display: flex;
  flex-direction: column;
  place-items: center;
}
</style>
