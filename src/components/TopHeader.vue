<template>
    <div class="text-top-header">
      <a>VENDA AQUI SEUS DESAPEGOS!!!</a>
    </div>

    <header class="p-3 text-bg-dark">
      <div class="container-fluid">
        <div class="d-flex flex-wrap align-items-center justify-content-center">
          <a href="/" class="col-2 d-flex align-items-center pb-3 text-white text-decoration-none">
            <img src="../assets/tempIcon.jpg" height="100" alt="IconShop">
          </a>
          <form class="col-6 col-lg mb-3 mb-lg-0 me-lg-3 text-bg-dark" role="search">
            <input type="search" class="form-control form-control-dark text-bg-dark" placeholder="Digite aqui o que deseja buscar" aria-label="Search">
          </form>
  
          <div class="col-3">
            <button type="button" class="btn btn-outline-dark me-2">Entrar</button>
            <button type="button" class="btn btn-outline-dark me-2">Atendimento</button>
            <a href="/" class="text-align-center text-white text-decoration-none">
              <img src="../assets/shopping-cart.png" height="30" alt="IconShop">
            </a>
          </div>
        </div>
      </div>
    </header>

    <nav class="navbar navbar-expand-lg bg-light justify-content-center">
      <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-center" id="navbarNavDropdown">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#">PROMOÇÃO</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">NOVIDADES DO DIA</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">FEMININO</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">MASCULINO</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">ACESSÓRIO</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">CALÇADOS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">MARCAS</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

  </template>
  
  <script>
  export default {
    name: 'App',
    props: {
      msg: String
    }
  }
  </script>
  
  <style scoped>
  .text-top-header{
    background-color: black;
    color: white;
    padding: 5px;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: black;
  }
  </style>
  