<template>
  <div class="skill-title">Skills</div>
  <div class="skill-box">
    <skills imgTitle="Vue js" id="skills">
      <img src="./vue.svg" alt="" />
    </skills>

    <skills imgTitle="Vue js" id="skills">
      <img src="./vue.svg" alt="" />
    </skills>

    <skills imgTitle="Vue js" id="skills">
      <img src="./vue.svg" alt="" />
    </skills>

    <skills imgTitle="Vue js" id="skills">
      <img src="./vue.svg" alt="" />
    </skills>
  </div>
</template>



<script>
import skills from "./skills.vue";

export default {
  name: "skillBox",
  components: {
    skills,
  },
};
</script>



<style lang="scss" scoped>
.skill-title {
  height: 70px;
  width: 500px;
  background: #85848f;
  border-radius: 10px;
  box-shadow: 3px 3px 9px #54535a, -3px -3px 11px #b6b5c4;
  box-sizing: border-box;
  margin-bottom: 30px;
  margin-left: 50%;
  transform: translate(-50%);
  color: #f4f2db;
  font-family: "Manrope", sans-serif;
  font-size: 40px;
  letter-spacing: 5px;
  text-align: center;
}
.skill-box {
  height: 300px;
  width: 80vw;
  background: #85848f;
  border-radius: 10px;
  box-shadow: 3px 3px 9px #54535a, -3px -3px 11px #b6b5c4;
  box-sizing: border-box;
  display: grid;
  box-sizing: border-box;
  padding-top: 20px;
  grid-template-columns: repeat(4,1fr);
  grid-template-rows: repeat(2, 1fr);
  // grid-template-columns: repeat(4,1fr);
  // grid-template-rows: repeat(2, 1fr);

  @media screen and (max-width: 750px) {
    #skills{
      height: 220px;
      width: 180px;
    }
  }
}
</style>