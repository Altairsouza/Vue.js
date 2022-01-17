<template>
  <div class="container-fluid  p1">
    <div class="row">
    
      <div class="col-md-6">
        <h2>
          PRECISANDO DE UM SITE MAS NÃO TEM TEMPO PARA MONTÁ-LO? VENHA CONHECER
          O NOSSO <font color="#f69522">SERVIÇO DE MONTAGEM!</font>
        </h2>
      </div>
      <div class="col-md-6">
        Quer criar um site mas não tem tempo para editar e deixá-lo pronto?
        Agora você poderá contar com nosso serviço de montagem. É muito simples,
        basta contratar o serviço, escolher o modelo que servirá de base para
        seu site e enviar o seu conteúdo. O resto você pode deixar com nossa
        equipe!
        <br><br>
        <p>Venha conhecer melhor sobre este serviço!</p>

           <button class="btn btn-primary boxxx" type="submit">  SERVIÇO DE MONTAGEM</button>
      </div>
     
     
    </div>
   
  </div>
  
</template>

<script>

export default {
  name: "paralaxComponent",

}




</script>

<style scoped>

.container-fluid {
  margin-top: 22px;
  width: 95%;
  height: 60vh;
  background-attachment: fixed;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
  transform: scale(1.05);
   border-top: solid orange;
   color: white;
}
.p1 {
  background-image: url('parallax.jpg')
}
.col-md-6{
  padding-top: 80px;
  width: 50%;
  padding-right: 150px;
  font-size:15px;
}
.col-md-6 h2 {
  font-size: 29px;
  padding-left: 150px;
 
}
button{
  background-color: transparent;
  padding: 20px 20px;
  border: solid ;
}
button:hover{
  padding-top: 10px;
  background-color: white;
  color: black;
  border: none;
  padding: 20px 20px;
}
</style>
