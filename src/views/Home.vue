<template>
  <div class="main">
    <Header />
    <div class="limit">
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
      <div class="aboutUs">
        <div class="aboutUs__title">About Us</div>
        <div class="aboutUs__content">
          <div class="aboutUs__image">
            <img src="@/images/picture.jpeg" alt="" />
          </div>
          <div class="aboutUs__text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Perspiciatis fuga ea ab id rerum exercitationem provident fugit,
            necessitatibus delectus optio architecto earum laborum sunt nobis
            unde porro, reiciendis voluptatibus alias, sint temporibus. Eligendi
            fuga impedit nulla, similique ullam officia voluptatum assumenda
            quaerat id commodi neque cumque temporibus consequuntur voluptas
            ipsam reiciendis laborum totam expedita eum odio doloremque error
            soluta explicabo est. Praesentium dolore sapiente quam, perferendis
            ipsam possimus, dolor veritatis eligendi id odio exercitationem
            deserunt quod explicabo accusantium? Id totam odio delectus, illo,
            exercitationem laudantium hic fugiat error corrupti architecto
            aspernatur maiores officiis officia optio ea quidem, ut praesentium
            quas!
          </div>
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
