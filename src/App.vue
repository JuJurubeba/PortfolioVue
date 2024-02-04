<template>
  <HelloWorld></HelloWorld>
  <ApresentacaoJu></ApresentacaoJu>
  <SobreMim></SobreMim>
  <TrabalhosJu></TrabalhosJu>
  <FormJu></FormJu>
  <RodapeJu></RodapeJu>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ApresentacaoJu from './components/ApresentacaoJu.vue'
import SobreMim from './components/SobreMim.vue'
import TrabalhosJu from './components/TrabalhosJu.vue'
import FormJu from './components/FormJu.vue'
import RodapeJu from './components/RodapeJu.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    ApresentacaoJu,
    SobreMim,
    TrabalhosJu,
    FormJu,
    RodapeJu
    
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
body{
  background-color: black;
  height: 100vh;
}
.interface{
  max-width: 1280px;
  margin: 0 auto;
  

}
.flex{
  display: flex;
}
h2.titulo{
  color: #fff;
  font-size: 38px;
  text-align: center;
}
h2 span{
  color: #7ffef5;
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
button:hover{
  box-shadow: 0px 0px 10px #7ffef5;
  transform: scale(1.05);
  
}

.btn-contato button{
  padding: 10px 40px;
  font-size: 18px;
  font-weight: 600;
  background-color: #7ffef5;
  border: 0;
  border-radius: 30px;
  cursor: pointer;
  transition: .2s;
}
.btn-contato button:hover{
  box-shadow: 0px 0px 10px #7ffef5;
  transform: scale(1.05);
  
}
</style>
