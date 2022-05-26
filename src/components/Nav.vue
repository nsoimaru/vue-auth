<template>
  <header class="p-3 bg-dark text-white">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
        <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
          <li><router-link to="/" href="#" class="nav-link px-2 text-white">Home</router-link></li>
        </ul>
        <div class="text-end">
          <router-link to="/login" type="button" class="btn btn-outline-light me-2">Login</router-link>
          <router-link to="/register" type="button" class="btn btn-outline-light me-2">Register</router-link>
        </div>
      </div>
    </div>
  </header>
</template>

<script lang="ts">
export default {

}
</script>

<style>

</style>