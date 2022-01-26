<template>
  <footer>
      <div class="container-max">
          <div class="container">
              <div class="foot-sx">
                  <div class="logo">
                    <img src="../assets/img/logo-light.png" alt="">
                  </div>
                  <div class="sub">
                    <span class="grigio">start working with <span class="light">Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.</span>
                  </div>
                  <div class="social">
                      <i class="fab fa-facebook-square"></i>
                      <i class="fab fa-instagram"></i>
                      <i class="fab fa-twitter"></i>
                      <i class="fab fa-linkedin-in"></i>
                  </div>
              </div>

              <div class="foot-center-one">
                  <h1>Company</h1>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
              </div>

              <div class="foot-center-two">
                  <h1>Usefull Links</h1>
                  <ul>
                    <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>
                  <ul>
                      <li><a href="">link</a></li>
                  </ul>

                  </ul>
              </div>

              <div class="foot-dx">
                  <h1>Newsletter</h1>

              </div>
          </div>
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";

.container-max {
    background-color: $notte;
    padding-bottom: 30vh;
}

.container {
    h1 {
        color: $bianco-1;
    }
}

.foot-sx, .foot-dx, .foot-center-one, .foot-center-two {
    display: flex;
    flex-direction: column;
}

.foot-sx {
    .logo {
        width: 50%;
        margin-bottom: 1em;
        img {
            width: 70%;
        }
    }

    .sub {
        margin-bottom: 1em;
    }

    .social {
        i {
            color: $grigio;
            padding: 0.7em;
            border: 1px solid $grigio;
            border-radius: 10px;
            margin-right: 2px;
        }
    }
}

.foot-center-one, .foot-center-two {
    li {
        a {
            color: $grigio;
        }
    }
}


.foot-dx {
}

</style>