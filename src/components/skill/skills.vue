<template>
  <div class="skills">
      <slot></slot>
      <p class="imgTitle">{{imgTitle}}</p>
  </div>
</template>


<script>
export default {
    name:"skills",
    props:{
        image:String,
        imgTitle:String
    }
}
</script>




<style lang="scss">
.skills {
  height: 250px;
  width: 200px;
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
  img{
      margin-top: 50px;
      z-index: 100;
  }
  .imgTitle{
      font-size: 20px;
      letter-spacing: 0;
  }
}
</style>