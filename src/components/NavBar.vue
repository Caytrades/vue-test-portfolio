<template>
    <nav class="navbar navbar-expand-lg bg-primary">
  <div class="container">
    <a class="navbar-brand text-white" href="#">Cay</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Cay</h5>
        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
          <li class="nav-item">
            <a class="nav-link text-white" aria-current="page" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</nav>
</template>

<script>
// Import Bootstrap and BootstrapVue CSS files (order is important)
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap/dist/js/bootstrap.bundle.js'
import 'bootstrap-vue/dist/bootstrap-vue.css'
export default {
    
}
</script>


<style scoped>
    
</style>