<template>
  <main>
      <div class="container-max">
          <div class="container title">
              <div class="features">
                <h1>Key Features</h1>
              </div>
              <div class="subtitle">
                <span>Start working with <span id="light">Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.</span>
              </div>
          </div>
          <div class="container">
              <div class="box-skill left">
                  <i class="fas fa-layer-group"></i>
                  <h1>Modular</h1>
                  <span>Composed in a pseudo-Latin language which more or less corresponds.</span>
                  <div class="link-read">
                      <a href="">Read More</a>
                      <i class="fas fa-chevron-right"></i>
                  </div>
              </div>
              <div class="box-skill ">
                    <i class="fas fa-tv"></i>
                  <h1>Responsive</h1>
                  <span>Composed in a pseudo-Latin language which more or less corresponds.</span>
                  <div class="link-read">
                      <a href="">Read More</a>
                      <i class="fas fa-chevron-right"></i>
                  </div>
              </div>
              <div class="box-skill ">
                  <i class="fab fa-codepen"></i>
                  <h1>Customizable</h1>
                  <span>Composed in a pseudo-Latin language which more or less corresponds.</span>
                  <div class="link-read">
                      <a href="">Read More</a>
                      <i class="fas fa-chevron-right"></i>
                  </div>
              </div>
              <div class="box-skill right">
                  <i class="fas fa-expand-arrows-alt"></i>
                  <h1>Scalable</h1>
                  <span>Composed in a pseudo-Latin language which more or less corresponds.</span>
                  <div class="link-read">
                      <a href="">Read More</a>
                      <i class="fas fa-chevron-right"></i>
                  </div>
              </div>
          </div>
      </div>
  </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
    .container-max {
        height: 80vh;
        background-color: $bianco-1;
    }

    .title {
        display: flex;
        flex-direction: column;
        padding-top: 5em;
        .features, .subtitle {
            padding-bottom: 2em;
        }
    }

    .subtitle span {
        color: $grigio;
    }

    .box-skill {
        width: 25%;
        height: 27vh;
        border: 2px solid $grigio;
        padding: 1.5em;
        border-radius: 5px;
        margin: 1em;

        i, h1 {
            margin-bottom: 10px;
        }

        .link-read {
            margin-top: 10px;
        }

        i {
            background-color: $azure;
            color: $blu;
            padding: 0.5em;
            border-radius: 5px;
            font-size: 150%;
        }
    }

    .left {
        margin-left: 0;
    }


    .link-read {
        i {
            background-color: $bianco-1;
            font-size: 80%;
        }

        a {
            color: $blu;
        }
    }    



</style>