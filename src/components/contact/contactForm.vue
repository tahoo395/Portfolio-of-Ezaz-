<template>
  <form class="form">
    <input type="text" class="name" placeholder="Name" />
    <textarea class="text" placeholder="Text...."></textarea>
    <input type="submit" class="button" >
    <i class="fab fa-facebook fb"></i>
    <i class="far fa-envelope email"></i>
  </form>
</template>



<style lang="scss">
.form {
  width: 350px;
  height: 450px;
  background: #85848f;
  border-radius: 10px;
  box-shadow: 5px 5px 10px #54535a, -5px -5px 22px #b6b5c4;
  box-sizing: border-box;
  display: grid;
  justify-content: center;
  font-family: "Manrope", sans-serif;
  .name,
  .text {
    width: 320px;
    border: none;
    border-radius: 5px;
    box-sizing: border-box;
    padding-left: 10px;
    font-size: 20px;
    box-shadow: inset 5px 5px 10px #6c6b74, inset -5px -5px 10px #9e9daa;
    background: #85848f;
    color: #f4f9fc;
    &:focus {
      border: none;
      outline: none;
    }
  }
  .name {
    height: 40px;
    font-size: 17px;
    margin-top: 50px;
  }
  .text {
    height: 140px;
    resize: none;
    margin-top: -40px;
    padding-top: 10px;
  }
  .button{
    // position: absolute;
    width: 120px;
    border: none;
    border-radius: 5px;
    box-sizing: border-box;
    padding-left: 10px;
    font-size: 20px;
    box-shadow: inset 5px 5px 10px #6c6b74, inset -5px -5px 10px #9e9daa;
    background: #85848f;
    color: #f4f9fc;
    height: 40px;
    font-size: 17px;
    margin-top: -20px;
    cursor: pointer;
  }
  .fb,.email{
    position: absolute;
    font-size: 36px;
    margin-top: 330px;
    cursor: pointer;
  }
  .fb{
    color: #64b4ff;
    margin-left: 200px;
  }
  .email{
    color: #e8ff64;
    margin-left: 270px;
  }
}
::placeholder {
  color: #dfe6e9;
  opacity: 1; 
}
</style>