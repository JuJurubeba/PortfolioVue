<template>
  <header>
    <div class="interface">
      <div class="logo">
          <a href="#"><img src="../assets/logo.png" alt=""></a>
      </div>
      <nav class="menu-desktop">
          <ul>
              <li><a href="#">inicio</a></li>
              <li><a href="#">Sobre</a></li>
              <li><a href="#">Projetos</a></li>
          </ul>
      </nav>

      <div class="btn-contato">
          <a href="#">
              <button>Contato</button>
          </a>
      </div>
  </div>
    

  </header>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


<style scoped>
header{
  padding: 40px 4%;
 
  
}
header > .interface{
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  padding: 60px 4%;
}
header a{
  color: #5c5c5c;
  text-decoration: none;
  display: inline-block;
}
header a:hover{
  color: white;
  transform: scale(1.05);

}
header nav ul{
  list-style-type: none;

}
header nav ul li {
  display: inline-block;
  padding: 0 40px;
}
/* Estilod o topo do site*/
button:hover{
  box-shadow: 0px 0px 10px #7ffef5;
  transform: scale(1.05);
}

</style>
