<template>

<!--Header-->

<header id="Cabeza">
<nav class="navbar navbar-expand-lg bg-dark navbar-dark ">
  <div class="container-fluid">
    <a class="navbar-brand fst-italic" href="#">Grupo-1 - Practica </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon fs-6"></span>
    </button>
    <div class="collapse navbar-collapse text-center my-0" id="navbarSupportedContent">
      <div class="navbar-nav ms-auto fs-6 ">
                <a class="nav-link active my-2 fst-italic" aria-current="page" href="Home">Inicio</a>
                <a class="nav-link active my-2 fst-italic" aria-current="page" href="Home">Nosotros</a>
             <!--   <a class="nav-link active" aria-current="page">
                   <button type="button" class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#exampleModal2">
                     Registrarse
                    </button></a> 
              -->  
           </div>
            
    </div>
  </div>
</nav>
</header>
<!--Modal2 Registrarse

<div class="modal fade" id="exampleModal2" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title text-danger" id="exampleModalLabel">Login form</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <form>
          <div class="mb-3">
            <label for="primerNombre" class="form-label">Primer Nombre</label>
            <input type="text" class="form-control" id="primerNombre" name="primerN">
            <label for="segundoN" class="form-label">Segundo Nombre</label>
            <input type="text" class="form-control" id="segundoN" name="segundoN">
            <label for="exampleInputEmail1" class="form-label">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <div id="emailHelp" class="form-text">No se compartirá su contraseña con alguien extraño xd.</div>
          </div>
          <div class="mb-3">
            <label for="exampleInputPassword1" class="form-label">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
          </div>
          <button type="submit" class="btn btn-primary">Login</button>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-warning" data-bs-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
-->


<div class="container-fluid text-center my-5">
 <h2><strong>Proyecto Programado</strong></h2>
</div><br>
<h4>Pasos a seguir:</h4>
<ul>
  <li>Instalar NodeJs</li>
  <li>Instalar Vue</li>
  <li>Instalar boostrap 5 </li>
  <li>Crear un boton modal en el navbar</li>
  <li>Crear un formulario</li>
  <li>Importar un modal de vue</li>
  <li>Importar las clases de boostrap</li>
</ul>
<div class="slider">
  
</div>

<div class="container-fl">
<footer class="bg-light text-center text-lg-start my-5">
  <!-- Copyright -->
  <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
    © 2022 Derechos reservados:
    <strong class=" fst-italic" >Grupo-1</strong>
    
  </div>
  <!-- Copyright -->
</footer>
</div>


</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      open : false
    }
  }
}

</script>

<style>
 @media screen and (min-width: 1200px){
  .btn{
    margin: 0%;
    
    font-style: italic;
  }
}
#exampleModalLabel{
  text-align: center;
  margin-left: 160px;
}

.container-fl{
  margin-top: 115px;
}
 
</style>
