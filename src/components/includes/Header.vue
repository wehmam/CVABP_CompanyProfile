<template>
  <div>
    <nav class="navbar fixed-top navbar-expand-lg" style="background-color: green">
      <div class="container">
        <img src="../../assets/cvABPlogo.png" width="50" height="40" alt="">
        <button class="navbar-toggler" type="button" data-toggle="collapse" aria-label="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end py-3" id="navbarNavAltMarkup">
          <ul class="navbar-nav">
            <li class="nav-item mr-3">
              <!-- <a class="nav-link" style="color: white" href="#">Home</a> -->
              <router-link to="/" class="nav-link" style="color: white">Home</router-link>
            </li>
            <li class="nav-item mr-3">
                <router-link to="/product" class="nav-link" style="color: white">Product</router-link>
            </li>
            <li class="nav-item mr-3">
                  <router-link to="/client" class="nav-link" style="color: white">Client</router-link>
            
            </li>
            <li class="nav-item mr-3">
                  <router-link to="/contact" class="nav-link" style="color: white">Contact Us</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
  export default {
    name: 'Header'
  }
</script>