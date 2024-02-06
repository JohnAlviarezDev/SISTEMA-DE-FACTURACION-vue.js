<template>
  <b-container>
    <nav class="navbar navbar-expand-md bg-body-tertiary">
    <div class="container-fluid">
      <router-link class="navbar-brand" to="/">Navbar</router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link active" aria-current="page" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/crear">Crear</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/factura">Facturas</router-link>
          </li>          
        </ul>
      </div>
    </div>
  </nav>
  </b-container>
  
  
  
</template>
<style>
.container-fluid{
  width: 1440px;
height: 217px;
border-radius: 20px 20px 0px 0px;
background: linear-gradient(0deg, #FF7900 0%, #FF7900 100%), #212328;
}
.navbar-brand{
  color: #0F2C55;
  font-family: Gilroy;
  font-size: 60px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  }
  .nav-link{
    color: #0F2C55;
    font-family: Gilroy;
    font-size: 80px;
    font-style: normal;
    font-weight: 300;
    line-height: normal;
  }
</style>

<script>
export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>
