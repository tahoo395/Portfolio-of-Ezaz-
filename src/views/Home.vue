<template>
  <Vectors></Vectors>

  <div class="home">
    <img class="logo-home" src="../assets/image/logo/logo-home.jpg" alt="" />
    <neumoBox class="home-box">
      <template v-slot:HeadText>MD. Ezaz Mahumd</template>
      <template v-slot:ParagraphText>I am Android Developer</template>
    </neumoBox>
  </div>

  <div class="about">
    <img class="logo-about" src="../assets/image/logo/logo-about.svg" alt="" />
    <neumoBox class="about-box">
      <template v-slot:HeadText>About me</template>
      <template v-slot:ParagraphText>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nihil ducimus
        natus accusantium saepe ipsa minima veritatis sapiente. Ipsum quae optio
        assumenda fuga, iste cum nobis asperiores quis laboriosam facilis ad?
      </template>
    </neumoBox>
  </div>

  <div class="skill">
    <skillBox></skillBox>
  </div>

  <div class="contact">
    <contactForm class="form"></contactForm>
    <neumoBox class="contact-box">
      <template v-slot:HeadText>Contact me</template>
      <template v-slot:ParagraphText>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad ab
        voluptatibus sit in, accusamus, voluptas impedit, autem molestiae earum
        qui laudantium quam beatae porro ipsum a deleniti!
      </template>
    </neumoBox>
  </div>

  <div class="last">
    <p>Thanks !</p>
  </div>
</template>


<script>
import Vectors from "../components/all/vector.vue";
import neumoBox from "../components/all/neumoBox.vue";
import skillBox from "../components/skill/skillBox.vue";
import contactForm from "../components/contact/contactForm.vue";


export default {
  components: {
    Vectors,
    neumoBox,
    skillBox,
    contactForm,
  },
};
</script>



<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Manrope:wght@300&display=swap");
@import '../scss/home.scss';
@import '../scss/about.scss';
@import '../scss/contact.scss';
@import '../scss/last.scss';

* {
  overflow-x: hidden;
  margin: 0;
  padding: 0;
  font-family: "Manrope", sans-serif;
}


.skill {
  height: 100vh;
  width: 100vw;
  display: grid;
  align-content: center;
  justify-content: center;
}
</style>