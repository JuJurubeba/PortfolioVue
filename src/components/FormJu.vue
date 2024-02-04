<template>
    <section class="formulario">
        <div class="interface">
            <h2 class="titulo">Fale <span>Comigo.</span></h2>

            <form id="form" action="https://formspree.io/f/meqyagne" method="post">
                <input type="text" name="name" id="name" placeholder="Seu nome" required>
                <input type="email" name="email" id="email" placeholder="Seu e-mail" required>
                <input type="text" name="telefone" id="telefone" placeholder="Seu telefone">
                <textarea name="mensagem" id="message" placeholder="Sua mensagem" ></textarea>
                <div class="btn-enviar"><input type="submit" id="submit" value="Enviar" style="background-color: transparent;"></div>
            </form>
        </div>
    </section>

</template>

<script>
export default{
    name:'FormJu'
    
}
</script>
<style>
section.formulario{
    padding: 80px 4%;
  }
  form{
    max-width: 500px;
    margin:auto;
    display: flex;
    justify-content: center;
    flex-direction: column;
    gap: 10px;
  }
  form input, form textarea{
    width: 100%;
    background-color: rgba(190, 190, 190, 0.438);
    border: 0;
    outline: 0;
    padding: 20px 15px;
    border-radius: 15px;
    color: #fff;
    font-size: 18px;
  }
  form textarea{
    resize: none;
    max-height: 300px;
  }
  /*botão enviar*/
  .btn-enviar {
    padding: 10px 20px;
    margin: 40px 0;
    color: #03e9f4;
    text-decoration: none;
    text-transform: uppercase;
    transition: 0.5s;
    letter-spacing: 200px;
    overflow: hidden;
    cursor: pointer;
  }
  
  .btn-enviar:hover { 
    background: black;
    color: #03e9f4;
    box-shadow: 0 0 5px rgba(3, 233, 244, 0.5),
                0 0 25px rgba(3, 233, 244, 0.5),
                0 0 50px rgba(3, 233, 244, 0.5),
                0 0 200px rgba(3, 233, 244, 0.5);
    -webkit-box-reflect: below 20px linear-gradient(transparent, #03e9f4 );
    
  }
</style>