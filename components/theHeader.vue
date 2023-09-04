<template>
  <header>
    <div class="featuredContent">
      <div class="content">
        <p class="featured">Featured</p>
        <p class="title">
          Rozbijamy programowanie na czynniki pierwsze: Rady od doświadczonych
          seniorów
        </p>
        <p class="textContent">
          Zanurz się w świat doświadczonych programistów, którzy codziennie
          spędzają dużo czasu przed komputerem. Mają wypracowane swoje
          “know-how” i chętnie się w tym artykule z wami o tym podzielą.
        </p>
      </div>
    </div>
  </header>
</template>
<script></script>
<style scoped lang="scss">
header {
  display: flex;
  flex-direction: column;
  place-items: center;
}
.featuredContent {
  width: 345px;
  height: 635px;
  background: #d9d9d9;
  border-radius: 24px;
  display: flex;
  place-items: flex-end;
}
.content {
  margin: 0 16px 72px 16px;
}
.featured {
  font-size: 16px;
}
.title {
  font-size: 24px;
  font-weight: bold;
  margin: 8px 0;
}
.textContent {
  font-size: 12px;
}
</style>
