<template>
<main>
  <div class="container-max">
      <div class="container">
          <div class="main-sx">
              <div class="title">
                  <h1>Build tools and</h1> 
                  <h1>extensive documention</h1>
              </div>
              <div class="subtitle">
                  <span>
                      You can combine all the landrick templates into a single one, you can take a component fromthe Application theme and use it in the Website.
                  </span>
              </div>
              <div class="checkcircle">
                  
                <div class="option">
                    <i class="far fa-check-circle light"></i>
                    <span> Digital Marketing Solutions for tomorrow</span>

                </div>
                <div class="option">
                    <i class="far fa-check-circle light"></i>
                    <span> Our talented & experienced marketing agency</span>

                </div>
                <div class="option">
                    <i class="far fa-check-circle light"></i>
                    <span> Create your own skin to match your brand</span>

                </div>
              </div>
              <a class="button" href="">Read more <i class="fas fa-arrow-right"></i></a>
              
          </div> 
          <div class="main-dx">
              <img src="../assets/img/1.png" alt="">
          </div>
      </div>
  </div>
  <div class="container-max">
      <div class="container-bottom">
          <h1>Our rates for developer from landrick team</h1>
          <div class="subtitle">
            <span class="grigio">start working with <span class="light">Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.</span>

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
    display: flex;
    justify-content: center;
}

.container {
    margin-top: 5em;
}

.main-sx {
    width: 60%;
    display: flex;
    flex-direction: column;
    justify-content: center;

    .subtitle, .checkcircle {
        margin-top: 1em;
    }

    .subtitle {
        color: $grigio;
    }

    .option {
        margin-bottom: 0.3em;
    }

    .button {
        width: 120px;
        margin-top: 1em;
        padding: 0.5em;
        border-radius: 5px;
        text-align: center;
        color: $bianco-2;
        background-color: $blu;

        i {
            font-size: 60%;
        }

    }

}

.main-dx {
    width: 40%;
    img {
        width: 100%;
    }
}

.container-bottom {
    width: 50%;
    margin-top: 3em;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    .subtitle {
        width: 60%;
    }
}
</style>