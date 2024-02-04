<template>
    <footer>
            <div class="line-footer">
                <div class="logo-footer">
                    <div class="flex">
                    <img src="../assets/logo.png" alt=""> 
                <div class="btn-social">
                    <a href="https://github.com/JuJurubeba"><button><img src="../assets/github.svg" alt="" h></button></a>
                    <a href="https://www.linkedin.com/in/juliano-calixto-95148a1a2/"><button><img src="../assets/linkedin.svg" alt=""></button></a>
                    <a href="#"><button><img src="../assets/envelope-fill.svg" alt=""></button></a>
                </div>
                </div>
                <div class="line-footer borda">
                    <p><img src="images/envelope-fill.svg" alt="" srcset=""><a href="mailto:julianopedrosa1@gmail.com">julianopedrosa1@gmail.com</a></p>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default{

}
</script>

<style>
footer{
    padding: 60px 4%;
    box-shadow: 0 0 40px 10px #525151;
  }
  footer .flex{
    justify-content: space-between;
  }
  footer .line-footer{
    padding: 20px 0;
  }
  .borda{
    border-top: 2px solid #7ffef5;
  }
  footer .line-footer p img{
    color:#7ffef5;
  }
  footer .line-footer p a{
    color: #fff;
  }
  
</style>