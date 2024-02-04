<template>
    <section class="topo-do-site">
        <div class="interface">
            <div class="flex">
                <div class="txt-topo-site">
                    <h1 id="txt-apresentação">Olá eu sou o Juliano <span>.</span></h1>
                    <p>Tenho 22 anos, sou estudante de programação e futuro engenheiro.</p>
                    
                    <div class="btn-contato">
                        <a href="#"><button>Entre em contato</button></a>
                    </div>
                    
                </div>
                <div class="img-topo-site">
                    <img src="../assets/juliano.png" alt="">
                </div>
            </div>
        </div>
    </section>

</template>
<script>
export default{
    name:'ApresentacaoJu',
}

</script>

<style>
section.topo-do-site{
    padding: 40px 4%;
}
section.topo-do-site .flex{
    align-items: center;
    justify-content: center;
    gap: 90px;
    
}
.topo-do-site h1{
    color: white;
    font-size: 45px;
    line-height: 40px;
}
.topo-do-site .txt-topo-site h1 span{
    color: aquamarine;
}
.topo-do-site .txt-topo-site p{
    color: white;
    margin: 40px 0;
}
.topo-do-site .img-topo-site img{
    position: relative;
    animation: flutuar 2s ease-in-out infinite alternate;
}
@keyframes flutuar{
    0%{
        top: 0;
    }
    100%{
        top: 30px;
    }
}
#txt-apresentação{
    width: 22ch;
    animation: typing 2s steps(22), blink .5s step-end infinite alternate;
    white-space: nowrap;
    overflow: hidden;
    border-right: 3px solid;
    font-size: 2em;
  }

  @keyframes typing {
    from {
      width: 0
    }
  }
      
  @keyframes blink {
    50% {
      border-color: transparent
    }
  }



</style>