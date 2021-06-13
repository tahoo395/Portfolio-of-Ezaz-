<template>
  <div class="vectors">
    <img src="../../assets/image/vectors/c-1.svg" alt="" />
    <img src="../../assets/image/vectors/c-2.svg" alt="" />
    <img src="../../assets/image/vectors/c-4.svg" alt="" />
    <img src="../../assets/image/vectors/c-6.svg" alt="" />
    <img src="../../assets/image/vectors/r-1.svg" alt="" />
    <img src="../../assets/image/vectors/r-3.svg" alt="" />
    <img src="../../assets/image/vectors/r-5.svg" alt="" />
    <img src="../../assets/image/vectors/s-3.svg" alt="" />
    <img src="../../assets/image/vectors/s-6.svg" alt="" />
    <img src="../../assets/image/vectors/t-1.svg" alt="" />
    <img src="../../assets/image/vectors/t-3.svg" alt="" />
    <img src="../../assets/image/vectors/t-6.svg" alt="" />
  </div>
</template>


<script>
export default {
  name: "Vectors",
};
</script>




<style lang="scss">
body{
    background: #85848F;
    .vectors{
        img{
            position: absolute;
            height: 200px;
            width: auto;
        }
        img:nth-child(1){
            left: 0;
            top: 250px;
        }
        img:nth-child(2){
            left: 100px;
            top: 650px;
        }
        img:nth-child(3){
            left: 0;
            top: 2300px;
        }
        img:nth-child(4){
            right: 150px;
            top: 3100px;
        }
        img:nth-child(5){
            right: 0;
            top: 550px;
        }
        img:nth-child(6){
            left: 300px;
            top: 1250px;
        }
        img:nth-child(7){
            left: 500px;
            top: 1950px;
        }
        img:nth-child(8){
            left: 0;
            top: 1700px;
        }
        img:nth-child(9){
            top: 2600px;
            left: 200px;
        }
        img:nth-child(10){
            top: 0;
            left: 50%;
            transform: translate(-50%);
        }
        img:nth-child(11){
            right: 0;
            top: 1500px;
        }
        img:nth-child(12){
            top: 3000px;
            left: 150px;
        }




        @media screen and (max-width: 800px) {
            img{
                height: 150px;
            }
        }

        @media screen and (max-width: 530px) {
            img{
                height: 120px;
            }
        }

        @media screen and (max-width: 390px) {
            img{
                height: 80px;
            }
        }

        @media screen and (max-width: 300px) {
            img{
                height: 50px;
            }
        }

        @media screen and (max-width: 230px) {
            img{
                height: 40px;
            }
        }
    }
}
</style>