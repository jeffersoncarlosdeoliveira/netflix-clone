<template>
    
    <div id="home">
        <div id ="header">
            <img src="./../assets/NetflixLogo.svg" alt="">
            <button id ="entrar" type="button" class="btn btn-danger btn-sm active float-right" active>Entrar</button>
        </div>
        <div id="promocao">
            <h1><strong>100% diversão.<br> R$1,90 nos primeiros 30 <br>dias.</strong></h1>
            <p class="text-center">Assista onde quiser. Cancele quando quiser.</p>
            <p class="text-center">Pronto para assistir? Informe seu email para criar ou reiniciar sua assinatura..</p>
        </div>
        <div>
            <input type="text" placeholder="Email" class="experimente">
            <button class="btnExp" type="button" ><strong> EXPERIMENTE JÁ POR R$ 1,90 ></strong></button>
        </div>
        <p class="text-center">Esta oferta está disponível somente para não assinantes.</p>
    </div>
  
</template>

<style scoped>

#home{
    height: 812px;
    background-image: linear-gradient(to top,rgba(0,0,0,.1) 0,rgba(0,0,0,.6) 10%,rgba(0,0,0,.7) 20%),
    url('./../assets/BackGroundInicial.jpg');
    
}
#entrar{
    margin-right: 5%;
    margin-top: 2%;
    background-color: #e60000;
}
h1{
    color:white;
    font-size: 3.1em;
    text-align: center;
    width: 1000px;
    margin: auto;
    font-family: Netflix Sans,Helvetica Neue,'Helvetica Neue',Helvetica,Arial,sans-serif;

}
.text-center{
    color:white;
    font-size: 1.6em;
    font-family: 'Netflix Sans','Helvetica Neue',Helv'Netflix Sans','Helvetica Neue',Helvetica,Arial,sans-serif;

}
#promocao{
    padding-top: 220px;
}

body{
    -webkit-font-smoothing: antialiased
}
img{
    height: 42px;
    width: 140px;
    float: left;
    margin-left: 4%;
    margin-top: 2%;
    color: #e60000;
}
.experimente{
    margin: auto;
    height: 60px;
    width: 400px;
}
.btnExp{
    margin: auto;
    height: 60px;
    background-color:#e60000;
    color: white;
    padding-left: 10%;
    text-align: center;
    vertical-align: middle;
}
</style>