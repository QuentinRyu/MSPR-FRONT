<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary" style="margin-bottom: 20px;">
    <div class="container-fluid" style="margin-left: 10px; margin-right: 50px;">
        <a class="navbar-brand" href="file:///C:/MSPR%20FRONT/MSPR-FRONT/vue.html">
            <img src="C:\MSPR FRONT\MSPR-FRONT\image\plante.png"> 
            <span>Plant B</span>
          </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="City" aria-label="Search">
          <button class="btn btn-outline-success " type="submit">Search</button>
        </form>
      </div>
      <div class="d-flex justify-content-center ml-5 mr-5">
        <button class="btn btn-outline-success mx-2" @click="gotoKeepingPage">Keeping</button>
        <button class="btn btn-outline-success mx-2" @click="gotoBeingKeptPage">Being Kept</button>
        <button class="btn btn-outline-success mx-2" @click="gotoAddPlantPage">Add Plant</button>
      </div>
    </div>
  
    <div class="ml-50 mr-5">
      <ul class="navbar-nav me-auto ">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            <img src="C:\MSPR FRONT\MSPR-FRONT\image\connection.png">
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Login</a></li>
            <li><a class="dropdown-item" href="#">Register</a></li>
          </ul>
        </li>
      </ul>
    </div>
  
  </nav>
</template>
<script>
new Vue({
  el: "#navbar",
  methods: {
    navigateToKeeping() {
      window.location.href = "file:///C:/MSPR%20FRONT/MSPR-FRONT/keeping.html";
    },
    navigateToBeingKept() {
      window.location.href = "file:///C:/MSPR%20FRONT/MSPR-FRONT/beingkept.html";
    },
    navigateToAddPlant() {
      window.location.href = "file:///C:/MSPR%20FRONT/MSPR-FRONT/addplant.html";
    }
  }
})
</script>

