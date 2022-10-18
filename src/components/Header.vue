<template>
  <nav id="nav" class="navbar navbar-expand-lg navbar-dark mb-3">
    <div class="container">
      <div class="col-md-2">
          <img src="@/assets/logo.jpg" class="card-img">
        </div>
      <router-link to="/" class="navbar-brand">{{siteTitle}}</router-link>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <router-link to="/" class="nav-link">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link">About</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/login" class="nav-link">Login</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/signup" class="nav-link">Signup</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      siteTitle: "Share Book !  "
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar {
 
  background-image: linear-gradient(to right, #1675ac , #36d6c3);
}
.navbar-nav a {
  color: #fff;
  padding: 0 15px;
  display: block;
  font-size: 20px;

}
.navbar-dark .navbar-brand {
    color: #fff;
    font-size: 25px;
}


</style>
