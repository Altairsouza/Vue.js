<template>
    <div class="container-fluid">
    <div class="row row-cols-4">
    <div class="col immage">
     <img src="./rodapte.png" alt="rodape">
    
    </div>
    <div class="col color">
        <p>Site Profissional</p>
        <p>Email Profissional</p>
        </div>
        <div class="col color right">
            <p> Ajuda  </p>
            <p>Área do cliente  </p>
            <p> Entre em Contato  </p>
            <p> Termos de Utilizacão  </p>
        </div>
        <div class="col padding">
        <p>Este site foi totalmente desenvolvido com nosso construtor de sites Site.com.br. Gostaria de ter um parecido?</p>
        <p class="maior">SITE.COM.BR | SEU SITE PROFISSIONAL </p>
        <p>Todos direitos reservados</p>
        </div>
    </div>
    </div>
</template>

<script>
export default {
    name: "footerComponent.vue"
}
</script>

<style scoped>
.container-fluid {
    padding-top: 100px;
    background-color: black;
  padding-bottom: 100px;
    
   
}

.immage{
    
    padding-left: 140px;
}

    img{
        background-color: black;
       
    }
    .color {
        color:rgb(70, 160, 192);
    }
    .padding {
        
        
        margin-left: -80px;
    }
    .right{
        
        margin-left: -90px;
       
    }
    .maior{

        color: #470000;
    }
</style>