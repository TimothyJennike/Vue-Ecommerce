<template>
    <nav class="navbar navbar-expand-lg container-fluid">
        <div class="container-fluid ">
          <a class="navbar-brand text-white" href="#">Tim's Florist</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav mx-auto">
              <li class="nav-item p-3">
                <router-link to="/">Home</router-link>
              </li>
              <li class="nav-item p-3">
                <router-link to="/about">About</router-link>
              </li>
              <li class="nav-item p-3 text-black">
                <router-link to="/products">Products</router-link>
              </li>
              <li class="nav-item p-3 text-black">
                <router-link to="/contact">Contact</router-link>
              </li>
            </ul>
          </div>
        </div>
      </nav>
</template>
<script>
export default {
    
}
</script>
<style>
.navbar {
    background-color: gray
}


.navbar-nav {
    color: black;
    text-decoration: none;
}

</style>