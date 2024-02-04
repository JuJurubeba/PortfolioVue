<template>

<section class="portfolio">
    <div class="interface">
        <h2 class="titulo">Meu <span>portfolio</span></h2>
        <div class="flex">
            <div class="img-port" >
                <div class="overlay">Projeto 1</div>
            </div>
            <div class="img-port" >
                <div class="overlay">Projeto 2</div>
            </div>
            <div class="img-port">
                <div class="overlay">Projeto 3</div>
            </div>
        </div>
    </div>

</section>


</template>

<script>
export default{

}

</script>


<style>
section.portfolio{
    padding: 80px 4%;
    box-shadow: 0 0 40px 10px #525151;
    justify-content: center;
  }
  section.portfolio .flex {
    justify-content: space-around;
    margin-top: 60px;
  }
  .img-port{
    width: 360px;
    height: 460px;
    background-color: #7ffef5;
    background-size: cover;
    background-position: 100% 0%;
    transition: 5s;
    cursor: pointer;
    border-radius: 40px;
    position: relative;
  }
  .img-port:hover{
    background-position: 100% 100%;
  }
  .img-port{
    background-image: url(../assets/comp.jpg);
}
  .portfolio .interface h2 span{
    color: #7ffef5;
  }
  .overlay{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #55555594;
    border-radius: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    font-weight: 600;
    color: #fff;
    opacity: 0;
    transition: .5s;
  }
  .overlay:hover{
    opacity: 1;
  }

</style>