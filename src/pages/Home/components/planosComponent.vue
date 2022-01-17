<template>
    <div class="container-fluid">
    <div class="row">

    <div class="col-md-6 " >
    <div class="primeiro">
    <h2 class="cinza">PRECISA DE APENAS 1 SITE?</h2>
    <h2>TEMOS O PLANO IDEAL!</h2>
    <p>Com o nosso plano individual você terá os mesmos recursos dos planos maiores por um valor mais em conta!</p>
    
    <button class="btn btn-primary boxxx" type="submit">CONHECER PLANO INDIVIDUAL</button>
   </div>
   </div>
   <div class="col-md-6">
     <img src="./monitor.jpg">
   </div>
  

    </div>
    </div>
</template>


<script>
export default {
    name: 'planosComponent'
}
</script>

<style scoped>
.container-fluid {
    background-color: #eef0f3;
    padding-top: 50px;
    padding-bottom: 70px;
    
    
}
.primeiro{
    padding-left: 180px;
    margin-top: 60px;
}

p{
   padding-right: 10px;
}
img{
    margin-top: 5px;
    height: 320px;
}
button{
    margin-top:5px ;
    padding: 17px 15px;
    background-color:white ;
    color: black;
    border:solid black;
}
button:hover{
    margin-top:5px ;
    padding: 17px 15px;
    background-color:black ;
    color: white;
    border:solid black;
}
.cinza {
    font-family: 'Roboto', sans-serif;
    color: rgb(22, 17, 17);
}

</style>