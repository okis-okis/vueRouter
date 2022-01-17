<template>
  <div>
    <Header />
    <div class="limit main">
      <div class="image">
        <img src="@/images/hiImage.jpg" alt="" />
      </div>
      <div class="imageText">
        <div class="imageText__title">TITLE</div>
        <div class="imageText__text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam ullam
          et at dolorem? Blanditiis, nobis ducimus vitae modi aspernatur dolor
          nulla magni ratione repellendus consectetur eum unde nostrum id aut?
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped src="@/styles/home.css" />

<script>
import Header from "@/components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>
