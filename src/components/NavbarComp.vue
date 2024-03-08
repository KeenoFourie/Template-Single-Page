<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-transparent">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <img class="business_logo" src="https://i.postimg.cc/gJ9VyTVh/add-square-icon-2048x2046-oeui0bde.png" alt="business_logo">
        </li>
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.business_logo {
    height: 60px;
    padding: 5px;
    padding-right: 20px;
}
.navbar-expand-lg .navbar-nav {
    flex-direction: row;
    padding: 15px;
    margin: auto;
    display: flex;
    align-items: center;
}
.nav-link {
    padding-left: 25px !important;
    font-weight: 500 !important;
    color: #6b6b6b !important;
}
.nav-link.active {
    color: black !important;
}

@media (width< 991px) {
  .nav-link {
    padding-left: 0px !important;
    font-weight: 500 !important;
    color: #6b6b6b !important;
  }
  img {
    display: none;
  }
  .navbar-expand-lg .navbar-nav {
    flex-direction: column;
    padding-left: 0px;
    margin: auto;
    display: flex;
    align-items: center;
  }    
  .navbar-toggler {
    font-size: var(--bs-navbar-toggler-font-size);
    line-height: 1;
    color: black !important;
    background-color: transparent;
    border: none !important;
    border-radius: var(--bs-navbar-toggler-border-radius);
    transition: var(--bs-navbar-toggler-transition);
  }
}
</style>