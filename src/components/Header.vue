<template>
  <header>
      <div class="container-max">
          <div class="container">
              <nav>
                  <div class="nav-sx">
                      <img src="../assets/img/logo-dark.png" alt="">
                  </div>
                  <div class="nav-center">
                      <ul>
                          <li><a href="">Home</a></li>
                      </ul>
                      <ul>
                          <li><a href="">Landing <i class="fas fa-chevron-down"></i></a></li>
                      </ul>
                      <ul>
                          <li><a href="">Page <i class="fas fa-chevron-down"></i></a></li>
                      </ul>
                      <ul>
                          <li><a href="">Docs <i class="fas fa-chevron-down"></i></a></li>
                      </ul>
                  </div>
                  <div class="nav-dx">
                      <!-- 3 icone -->
                      <i class="fas fa-search"></i>
                      <i class="fab fa-github"></i>
                      <i class="fab fa-stack-overflow"></i>
                      <i class="far fa-user"></i>
                  </div>
              </nav>
          </div>
      </div>
  </header>
</template>

<script>
export default {
    name: 'Header',
    data() {

    }     
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";

.container-max, .container {
    background-color: $bianco-2;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-sx {
  display: flex;
  align-items: center;
  width: 20%;
  img {
    width: 50%;
    display: flex;
  }
}

.nav-center {
  display: flex;
  align-items: center;
  width: 40%;
  justify-content: space-around;
  a {
    color: $grigio-2;
    text-transform: uppercase;
  }
}

.nav-dx {
  width: 20%;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  
  i {
      margin: 0.5em;
  }

  .fab, .far{
      background-color: $azure;
      color: $blu;
      padding: 0.5em;
      border-radius: 5px;
  }

}





</style>