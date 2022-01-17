<template>
  <header class="header">
    <div class="header__logo">
      <img src="@/images/logo.png" alt="" />
    </div>
    <div
      class="header__menu"
      @click="openMenu"
      :class="[this.burgerState ? 'active' : '']"
    >
      <span></span>
    </div>
    <nav class="header__nav" ref="nav">
      <ul class="header__list">
        <li class="header__item"><a href="#">Главная</a></li>
        <li class="header__item"><a href="#">Библиотека</a></li>
        <li class="header__item"><a href="#">Музыка</a></li>
        <li class="header__item"><a href="#">Файлы</a></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped src="@/styles/header.css" />

<script>
export default {
  name: "App",
  data() {
    return {
      burgerState: false,
    };
  },
  methods: {
    openMenu() {
      this.$refs.nav.style.top = this.burgerState ? "-100%" : "0%";
      this.burgerState = !this.burgerState;
    },
  },
};
</script>
