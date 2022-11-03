<template>
    <nav class="navbar navbar-expand-lg shadow" style="background-color: Plum;">
        <div class="container-fluid">
          <RouterLink class="nav-link active" to="/">Vue.js</RouterLink>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <RouterLink class="nav-link active" to="/">Home</RouterLink>

              </li>
              <li class="nav-item">
                <RouterLink class="nav-link active" to="/about">About</RouterLink>
                </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    Contact
                </a>
                <ul class="dropdown-menu">
                  <li><router-link class="dropdown-item" to="/profile">Profile</router-link></li>
                  <li><a class="dropdown-item" href="#">Map</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">History</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>
</template>

<script>
    export default{}
</script>

<style lang="en">

</style>