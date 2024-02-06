<template>
  <b-container class="row-md">
    <div>
      <div class="tittle">
        <h1 class="text">Editar Factura</h1>
      </div>

      <div class="row-md-6">
        <div class="col-md-6">
          <input type="text" class="form-control" placeholder="First name" aria-label="First name">
        </div>
        <div class="col-md-6">
          <input type="text" class="form-control" placeholder="Last name" aria-label="Last name">
        </div>
      </div>
    </div>
    <form class="row-md">
      <div class="col-md-6">
        <label for="inputEmail4" class="form-label">Email</label>
        <input type="email" class="form-control" id="inputEmail4">
      </div>
      <div class="col-md-6">
        <label for="inputPassword4" class="form-label">Password</label>
        <input type="password" class="form-control" id="inputPassword4">
      </div>
      <div class="col-md-6">
        <label for="inputAddress" class="form-label">Dirección</label>
        <input type="text" class="form-control" id="inputAddress" placeholder="">
      </div>

      <div class="col-md-6">
        <label for="inputCity" class="form-label">Ciudad</label>
        <input type="text" class="form-control" id="inputCity">
      </div>

      <div class="col-md-6">
        <label for="inputState" class="form-label">Departamento</label>
        <select id="inputState" class="form-select">
          <option selected>Choose...</option>
          <option>...</option>
        </select>
      </div>

      <div class="col-md-6">
        <label for="inputState" class="form-label">Pais</label>
        <select id="inputState" class="form-select">
          <option selected>Choose...</option>
          <option>...</option>
        </select>
      </div>


      <div class="col-12">
        <button type="submit" href="/Fact" class="btn">Crear</button>
      </div>
      <div class="col-md-12">
        <button class="back"><i class="bi bi-box-arrow-in-up-left"></i></button>
      </div>
    </form>
  </b-container>
</template>
<style scoped>
.tittle {
  padding: 20px;
  margin: auto;
  width: 1440px;
  height: 217px;
  border-radius: 20px 20px 0px 0px;
  background: linear-gradient(0deg, #FF7900 0%, #FF7900 100%), #212328;
}

.text {
  color: #0F2C55;
  font-family: Gilroy;
  font-size: 30px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  margin: 20px;
}

.btn {
  color: white;
  background: #0F2C55;
}

.row {
  margin: 20px;
}
</style>