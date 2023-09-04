<template>
  <div class="wrapper">
    <div class="image"></div>
    <p class="title">Jak skutecznie wypozycjonować stronę internetową</p>
    <p class="content">
      Dowiedz się co zrobić, aby strona internetowa wyświetliła się w pierwszych
      wynikach wyszukiwania Google.
    </p>
    <div class="author">
      <div class="avatar"></div>
      <p class="name">Grażyna Żarko</p>
      <p class="date">18 Kwietnia 2023</p>
    </div>
  </div>
</template>
<script></script>
<style scoped lang="scss">
.image {
  width: 345px;
  height: 280px;
  background: #d9d9d9;
  border-radius: 24px;
}
.title {
  font-size: 16px;
  margin: 16px 0;
}
.content {
  font-size: 12px;
}
.author {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  margin-top: 32px;
  p {
    font-size: 12px;
  }
}

.avatar {
  width: 32px;
  height: 32px;
  border-radius: 50px;
  background: #d9d9d9;
  margin-right: 8px;
}
.date {
  position: relative;
  margin-left: 24px;
  &::before {
    content: "";
    width: 8px;
    height: 8px;
    background-color: #d9d9d9;
    border-radius: 40px;
    position: absolute;
    left: -16px;
    top: 50%;
    transform: translate(0, -50%);
  }
}
</style>
