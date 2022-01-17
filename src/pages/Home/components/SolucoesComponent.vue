<template>
    <div class="container">
    <h2 class="primo">OFERECEMOS</h2>
    <h2 class="primo"><span>SOLUÇÕES COMPLETAS</span></h2>
    <p class="primo">Além de sites profissionais, oferecemos também serviços de hospedagem, e-mail e loja virtual, confira!</p>
    <div class="row row-cols-3">
    <div class="col">
    <i class="far fa-list-alt naruto"></i>
    <h4 class="segundo">HOSPEDAGEM PROFISSIONAL</h4>

    <p>Hospedagem de sites profissional de alta performance com cPanel. Confira a melhor solução para sua demanda!</p>
    <a href="#aba-servicos">Conhcer</a>
    </div>

    <div class="col">
    <i class="far fa-envelope naruto"></i>
    <h4 class="segundo">E-MAIL PROFISSIONAL</h4>

    <p>Você pode iniciar com o plano mínimo e ampliar o serviço sempre que precisar, quando precisar! É muito fácil, confira!</p>
    <a href="#aba-servicos">Conhcer</a>
    </div>

    <div class="col">
   <i class="fas fa-globe-americas naruto"></i>
    <h4 class="segundo">REGISTRO DE DOMÍNIOS</h4>

    <p>Registre seu domínio pela Site.com.br e ele já estará configurado para ser usado no site que hospedar conosco.</p>
    <a href="#aba-servicos">Conhcer</a>
    </div>
    </div>
    
    </div>
</template>

<script>
export default {
    name: 'SolucoesComponent'
}
</script>

<style scoped>
.primo {
    
    margin-left: 100px;
   
}
.segundo {
    font-size: 20px;
    color:rgb(70, 160, 192) ;
}
.segundo:hover{
    cursor: pointer;
    color: orange;
}
.row{
    margin-right: 10px;
      margin-left: 100px;
}

  .col{
     
      padding: 20px 50px;
  }
  .naruto{
       width: 60px;
       height: 50px;
     margin-left: 80px;
      color: red;
      
  }
  a{
     text-decoration: none;
  }
  a:hover{
      cursor: pointer;
      color: orange;
  }
</style>