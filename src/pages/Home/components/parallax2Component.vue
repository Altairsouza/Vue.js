<template>
    <div class="container-fluid p1">
  <div class="row row-cols-3">
    <div class="col">
    <i class="fas fa-tv naruto"></i>
    <h4>RECOMENDADO PARA</h4>
<h4>AGÊNCIAS E DESIGNERS</h4>
    <p>Recomendado fortemente para agências, designers e sites com muitos acessos ou que necessitem flexibilidade de instalação de recursos.</p>
    
    </div>
    <div class="col">
     <i class="fas fa-sliders-h naruto"></i>
    <h4> AMPLIAÇÃO DE RECURSOS
QUANDO PRECISAR  </h4>
    <p>  Você tem total liberdade para ampliar seus recursos como precisar, se precisar.  </p>
    
    </div>
    <div class="col">
     <i class="fas fa-lock naruto"></i>
    <h4> SSL GRÁTIS</h4><h4>PARA TODOS OS DOMÍNIOS</h4>
  
    <p>  Tenha grátis o selo SSL em todos os seus domínios. Segurança para você, seus clientes e suas lojas virtuais.  </p>
    
    
    </div>
    <div class="col">
    <i class="fas fa-recycle naruto"></i>
    <h4> TRÁFEGO DE DADOS</h4>
      <h4>   LIVRE  </h4>
    <p> Todos seus sites sem limites de dados, use sem surpresas.   </p>
    
    </div>
     
    <div class="col">
    <i class="fas fa-check naruto"></i>
    <h4> PLATAFORMA WORDPRESS</h4>
            <h4>COM ACESSO COMPLETO  </h4>
    <p> Utilize nossa plataforma WordPress com acesso administrativo completo para instalação de novos plugins ou temas quando quiser.   </p>
    
    </div>
    <div class="col">
    <i class="far fa-star naruto"></i>
    <h4> MODELOS DE SITES</h4>
       <h4>PREMIUM </h4> 
    <p>   Modelos profissionais, instale todos que desejar, editor arrasta-e-solta, clone seus sites existentes criando novos sites. </p>
    
    </div>
    
  </div>
</div>
</template>

<script>
export default {
    name: 'parallax2Component'
}
</script>

<style scoped>
.container-fluid{

    padding-top: 100px;
    padding-bottom: 50px;
    background-attachment: fixed;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
  transform: scale(1.05);
}
  .row {
      margin-right: 200px;
      margin-left: 200px;

  }
  .col{
     
      padding: 2px 40px;
  }
  h4{
      font-size: 17px;
  }
  p{

      font-size: 14px;
  }
   .naruto{
       width: 60px;
       height: 50px;
     margin-left: 80px;
      color: red;
      
  }
  .p1 {
  background-image: url('parallax2.jpg')
}
</style>