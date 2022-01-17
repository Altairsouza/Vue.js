<template>
    <header>
        <div class="container" id="nav-container">
        <nav class="navbar navbar-expand-lg fixed-top background">
            <a href="#" class="navbar-brand">
                <img id="logo" src="@/assets/logo.png" alt="site.com.br">
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar-links" 
            aria-controls="navbar-links" aria-expanded="false" aria-label="toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbar-links">
            <div class="navbar-nav">





                <ul>
                <li><a class="nav-item nav-link" id="inicio">INICIO</a></li>
                
                <li> <a class="nav-item nav-link" id="servicos">SERVIÇOS</a>
                    <ul>
                        <li><a href="">MONTAGEM</a></li>
                        <li><a href="">SITE PROFISSIONAL</a></li>
                        <li><a href="">EMAIL PROFISSIONAL</a></li>
                        <li><a href="">SITE GRÁTIS</a></li>
                        <li><a href="">LOJA VIRTUAL</a></li>
                        <li><a href="">HOSPEDAGEM DE SISTES</a></li>
                        <li><a href="">REGISTRO DE DOMINIO</a></li>
                    </ul>
                    </li>
                  <li> <a class="nav-item nav-link" id="cliente">ÁREA DO CLIENTE</a>
                    <ul>
                        <li><a href="">AUTO-AJUDA EM FORUM</a></li>
                        <li><a href="">LOGIN NA AREA DO CLIENTE</a></li>
                    </ul>
                </li>
            </ul>
            </div>
            </div>
        </nav>
        </div>
    </header>
</template> 

<script>
export default {
    name: 'navBarComponent',
}
</script>


<style scoped>
/* barra de navegação */
ul {
    position: relative;
    background: transparent;
    margin: 0px;
    padding: 0px;
}

ul li {
    display: inline-block;
}

ul li a {
    text-decoration: none;
    color: white;
    padding: 15px;
    display: block;
}



ul ul{
    position: absolute;
    min-width: 200px;
    display: none;
    background: black;
}
ul ul li {
    display: block;
    background: black;
}

ul li:hover ul{
    display: block;
}


#nav-container {
    padding-top: 0;
    padding-bottom: 0;
    
    
}

 #logo {
     width: 100px;
     
     
 } 

 .navbar-brand {
     padding-top: 10px;
     padding-left: 125px;
    color: #fff;
    
 }
 .background{
     background-color: white;
 }

 .navbar-brand:hover {
     color: coral;
 }
 #navbar-links {
     padding-top: 10px;
     padding-right: 220px;
     font-size: 12px;
 }

 #navbar-links a {
     color: cornflowerblue;
 }


 #navbar-links a:hover {
     color: coral;
     cursor: pointer;
 }

 .navbar-expand-lg .navbar-nav .nav-link {
     padding: 1rem .8rem;
 }
</style>

