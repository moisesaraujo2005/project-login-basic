<template>

<div class="box-login">

<div class="form-left">
<h1 class="tituloLogin">Faça o login</h1>
<div class="box-email">
<h4>E-mail:</h4>
<input type="text" placeholder="  seuemail@.com"></div>

<div class="box-senha">
    <div class="alinhamentoTexto">
    <span>Esqueceu sua senha?</span>
<h4>Senha:</h4></div>
<input type="text" placeholder="  Digite sua senha"></div>

<button class="buttonLogin">Entrar</button>

<div class="line"></div>

<button class="buttonDontHaveAccount">Não tenho conta</button>


</div>

<div class="img-right">
    <img src="../assets/Login-rafiki.png" alt="">
</div>


</div>



</template>


<style>

*{
    margin: 0;
    padding: 0;
}

.box-login{
    height: 100vh;
    width: 100vw;
    display: flex;
    align-items: center;
    justify-content: center;
  
    

}

.form-left{
 
    width: 50%;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    gap: 3vh;
    background-color: #F2F2F2;
    height: 100%;
}

.img-right{
    width: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
}
.box-email{
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    gap: 2vh;
    }

    .box-senha{
        display: flex;
    align-items: flex-start;
    flex-direction: column;
    gap: 2vh;
    }

    .line{
        border: 1px solid rgb(214, 214, 214);
        width:17vw;
    }


    .tituloLogin{
        margin-bottom: 5vh;
    }

    .box-login input{
        width: 20vw;
        height: 4.5vh;
        border-radius: 3px;
        border: none;
    
    }

    .box-login h4{
        font-weight: 100;
        font-size: 1.2rem;
        margin-top: 0vh
    }

    .alinhamentoTexto{
        display: flex;
        flex-direction: row-reverse;
       gap: 15vh;
    }

    .box-login span{
        font-size: 1rem;
        color: rgb(65, 114, 203);
    }
    .buttonLogin{
        width: 20vw;
       height: 4.5vh;
        background-color: rgb(16, 129, 222);
        color: white;
        font-size: 1rem;
        border-radius: 2px;
       
        cursor: pointer;
    }
    .buttonDontHaveAccount{ 
        width: 20vw;
       height: 4.5vh;
        background-color: rgb(225, 225, 225);
        color: rgb(62, 62, 62);
        font-size:1rem;
        border-radius: 2px;
        
        cursor: pointer;
}


.img-right img{
    width: 35vw;
}
</style>