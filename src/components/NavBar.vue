<template>
  <div class="pos-f-t">
  <div class="collapse" id="navbarToggleExternalContent">
    <div class="bg-dark p-4">
      <h4 class="text-white">Collapsed content</h4>
      <span class="text-muted">Toggleable via the navbar brand.</span>
    </div>
  </div>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
    <a class="navbar-brand" href="#">Hidden brand</a>
    <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
    <li class="nav-item active">
      <router-link class="nav-link" to="/" exact>Home</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/about">About</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/rooms">Rooms</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/facilities">Facilities</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/contact">Contact</router-link>
    </li>
  </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
</div>
</template>

<script>
export default {

}
</script>

<style>
.pos-f-t {
  background-image: url(/src/assets/Background.jpg); /* Replace with your image path */
  background-size: cover; /* This will cover the entire area */
  background-position: center; /* Center the image */
  height: 100vh; /* Set the height as needed */
}
</style>