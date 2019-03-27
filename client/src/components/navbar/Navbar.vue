<template>
<div>
  <nav class="navbar fixed-top navbar-expand-sm navbar-light bg-white mb-3">
      <a class="navbar-brand text-uppercase text-expanded font-weight-bold d-lg-none" href="#"><img src="../../assets/img/blo-em_logo.png" width="30%"  alt=""></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
    <div class="container">
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item active px-lg-4">
            <a class="nav-link text-uppercase text-expanded" href="index.html"><router-link to="/">Home</router-link>
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item px-lg-4">
            <a class="nav-link text-uppercase text-expanded" href="about.html"><router-link to="/about">About</router-link></a>
          </li>
          <li class="nav-item px-lg-4">
            <a class="nav-link text-uppercase text-expanded" href="products.html"><router-link to="/shop">Shop</router-link></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</div>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style scoped>
nav {
  opacity: .99;
  background-color:darkgrey;
  border-bottom: 1px solid;
  border-bottom-color: darkgrey;
  /* margin-top: -80px; */
}

</style>
