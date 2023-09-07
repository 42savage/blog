<template>
  <footer>
    <div class="footerContent">
      <p class="title">
        Chcesz abym poruszył jakiś temat? Skontaktuj się ze mną!
      </p>
      <div class="buttons">
        <button class="mail">Kontakt e-mail</button>
        <button class="form">Formularz</button>
      </div>
      <theLogo color="#ffffff" />
    </div>
  </footer>
</template>
<style scoped lang="scss">
footer {
  display: flex;
  place-items: center;
  flex-direction: column;
  margin-bottom: 24px;
  position: relative;
}
.footerContent {
  border-radius: 24px;
  background: #1a1a1a;
  width: 345px;
  height: 672px;
  padding: 80px 24px;
}
.title {
  font-size: 24px;
  color: white;
  text-align: center;
}
.mail,
.form {
  font-size: 14px;
  color: white;
  background: none;
  border: 1px solid #eeeeee;
  padding: 8px 12px;
  border-radius: 8px;
  margin: 0 8px;
}
.buttons {
  width: 100%;
  margin-top: 56px;
  display: flex;
  place-content: center;
}
.logo {
  position: absolute;
  bottom: 24px;
  left: 50%;
  transform: translate(-50%, 0);
}
</style>
