<template>
  <div class="container">
    <div class="row">
      <div class="col-4 offset-4 card">
        <h2>Login Usuarios</h2>
        <form>
            <div class="mb-3">
                <label for="exampleInputEmail1" class="form-label leftText">Email</label>
                <input type="email" class="form-control " id="exampleInputEmail1" aria-describedby="emailHelp">
            </div>
            <div class="mb-3">
                <label for="exampleInputPassword1" class="form-label leftText">Contraseña</label>
                <input type="password" class="form-control" id="exampleInputPassword1">
            </div>
            <button type="submit" class="btn btn-primary">Ingresar</button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Login'
};
</script>

<style>
.leftText{
    text-align: left;
}
.row{
    padding: 2rem;
}
.card{
    padding: 1rem;
}


</style>