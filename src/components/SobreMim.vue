<template>
    <section class="sobre">
        <div class="interface">
            <div class="flex">
                <div class="img-sobre efeito-img">
                    <img src="../assets/IMG_20220727_173712587.jpg" alt="" id="juju">
                </div>
                <div class="txt-sobre efeito-txt">
                    <h2>Muito prazer, <span>Sou Juliano Calixto</span></h2>
                    <p>Meu nome é Juliano Calixto, tenho 22 anos e sou estudante de Engenharia Civil. Recentemente, decidi embarcar em um projeto pessoal com o objetivo de agregar conhecimento na área de programação, mesmo não tendo experiência prévia nesse campo. Estou determinado a expandir minhas habilidades e explorar novos horizontes acadêmicos, buscando integrar a programação ao meu repertório de conhecimentos. Acredito que essa iniciativa não apenas complementará minha formação em Engenharia Civil, mas também abrirá portas para inovações e oportunidades no futuro.</p>
                    <div class="btn-social">
                        <a href="https://github.com/JuJurubeba"><button><img src="../assets/github.svg" alt="" h></button></a>
                        <a href="https://www.linkedin.com/in/juliano-calixto-95148a1a2/"><button><img src="../assets/linkedin.svg" alt=""></button></a>
                        <a href="#"><button><img src="../assets/envelope-fill.svg" alt=""></button></a>
                    </div>

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
section.sobre{
    padding: 40px 4%;
    margin-top: 200px;

    
  }
  section.sobre .flex{
    align-items: center;
    gap: 60px;

  }
  .sobre .txt-sobre{
    color: white;
  }
  .sobre .txt-sobre h2{
    font-size: 40px;
    line-height: 40px;
  }
  .sobre .txt-sobre h2 span{
    color: #7ffef5 ;
    display: block;
  }
  .sobre .txt-sobre p {
    margin: 20px 0;
  }

 .btn-social button{
    width: 60px;
    height: 60px;
    border-radius: 50%;
    border: none;
    background-color: #7ffef5;
    font-size: 22px;
    cursor: pointer;
    margin: 0 5px;
   
  }
  #juju{
    border-radius: 10%;
  }


</style>