<template>
  <div id="menu">
<nav class="navbar navbar-expand-lg navbar-light ">
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
   <a class="nav-item nav-link active" href="#home">HOME</a>
      </li>
      <li class="nav-item">
  <a class="nav-item nav-link" href="#menu">ACERCA DE MI</a>
      </li>
      <li class="nav-item">
         <a class="nav-item nav-link" href="#proyectos">PROYECTOS</a>
      </li>
      <li class="nav-item">
        <a class="nav-item nav-link" href="#contacto">CONTACTO</a>
      </li>
    </ul>
  </div>
</nav>
  
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Quicksand&display=swap");


.nav-item {
  color: rgb(255, 244, 244);
  font-size: 15pt;
  margin-left: 30px;
  font-family: "Quicksand", sans-serif;
}
.nav-item:hover {
  color: rgb(2, 2, 2);
}
</style>
