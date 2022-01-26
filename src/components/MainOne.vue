<template>
  <main>
      <div class="container-max MainOne-1">
          <div class="container title">
              <div class="features">
                <h1>Key Features</h1>
              </div>
              <div class="subtitle">
                <span>Start working with <span class="blu">Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.</span>
              </div>
          </div>
          <div class="container boxe">

              <div class="box-skill left">
                  <i class="fas fa-layer-group fondo"></i>
                  <span class="ex-h1">Modular</span>
                  <span>Composed in a pseudo-Latin language which more or less corresponds.</span>
                  <div class="link-read">
                    <a class="button" href="">Read more <i class="fas fa-arrow-right"></i></a>
                  </div>
              </div>

              <div class="box-skill ">
                    <i class="fas fa-tv fondo"></i>
                  <span class="ex-h1">Responsive</span>
                  <span>Composed in a pseudo-Latin language which more or less corresponds.</span>
                  <div class="link-read">
                    <a class="button" href="">Read more <i class="fas fa-arrow-right"></i></a>
                  </div>
              </div>

              <div class="box-skill  ">
                  <i class="fab fa-codepen fondo"></i>
                  <span class="ex-h1">Customizable</span>
                  <span>Composed in a pseudo-Latin language which more or less corresponds.</span>
                  <div class="link-read">
                    <a class="button" href="">Read more <i class="fas fa-arrow-right"></i></a>
                  </div>
              </div>
              
              <div class="box-skill right">
                  <i class="fas fa-expand-arrows-alt fondo"></i>
                  <span class="ex-h1">Scalable</span>
                  <span>Composed in a pseudo-Latin language which more or less corresponds.</span>
                  <div class="link-read">
                    <a class="button" href="">Read more <i class="fas fa-arrow-right"></i></a>
                  </div>
              </div>

          </div>
      </div>



    <div class="container-max MainOne-2">
        <div class="container MainOne-2">
            <div class="quickstart">
                <span class="blu">Quickstart</span>
                <h1>Awesome isn't it? Let's dive in!</h1>
                <span>Start working with <span class="blu">Landrick</span> that can provide everything you need to geenerate awareness, drive traffic, connect.</span>
            </div>
        </div>
        <div class="container illustration">
            <div class="forma">
                <div class="npm">
                    <span>npm</span>                    
                </div>
                <div class="skill">
                    <span>nuget</span>                    
                </div>
                <div class="skill">
                    <span>spm</span>                    
                </div>
                <div class="skill">
                    <span>github</span>                    
                </div>
            </div>
            <div class="sub-forma">
                <span><span class="green">$</span> npm install <span class="green">-g</span> claps.js</span>
            </div>
        </div>
        <div class="container-max-subforma">
            <div class="container-sub-forma">
                <i class="far fa-check-circle green"></i>
                <span>  Organize your data</span>
                <i class="far fa-check-circle green"></i>
                <span>  Work with any team</span>

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
    .MainOne-1 {
        height: 60vh;
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

    .subtitle {
        span {
            color: $grigio;
        }

        .blu {
            color: $blu;
        }
    }

    .boxe {
        height: 40vh;
        align-items: flex-end;
    }

    .box-skill {
        width: 25%;
        height: 27vh;
        border: 2px solid $bianco-2;
        padding: 1.5em;
        border-radius: 5px;
        margin: 0.5em;
        margin-bottom: 3em;

        // position: relative;

        &:hover,
        &:active {
            margin-bottom: 5em;
        }

        i {
            margin-bottom: 10px;
        }

        .ex-h1 {
            margin-bottom: 10px;
            font-size: 150%;
            display: block;
            font-weight: bold;
        }

        .link-read {
            margin-top: 10px;
        }

        .fondo {
            background-color: $azure;
            color: $blu;
            padding: 0.5em;
            border-radius: 5px;
            font-size: 150%;
        }
    }

    // .box-skill:after {
    //     position: absolute;
    //     font-family: 'FontAwesome';
    //     top: 0;
    //     left: 10px;
    //     content: "\f005"; //non funziona ??????????? chiedere
    // }

    .left {
        margin-left: 0;
    }

        .button {
        width: 120px;
        margin-top: 1em;
        border-radius: 5px;
        text-align: center;
        color: $blu;

        i {
            font-size: 60%;
        }

        &:hover,
        &:active {
            padding: 0.5em;
            background-color: $blu;
            color: $bianco-1;
        }

    }




    // .link-read {
    //     &:hover,
    //     &:active {
    //         }


    //     i {
    //         background-color: $bianco-1;
    //         font-size: 80%;
    //     }

    //     a {
    //         padding: 0.3em;
    //         color: $blu;
    //         &:hover,
    //         &:active {
    //             color: $bianco-1;
    //             background-color: blue;
    //             border-radius: 10px;
    //         }
    //     }
    // }    

    .MainOne-2 {
        justify-content: center;
    }

    .quickstart {
        display: flex;
        width: 70%;
        flex-direction: column;
        text-align: center;

        h1 {
            margin: 1em;
        }
    }

    .quickstart {
        span {
        align-self: center;
        color: $grigio;
        }

        .blu {
            color: $blu;
        }
    }   

    .illustration {
        width: 40%;
        height: 15vh;
        background-color: $grigio-2;
        display: flex;
        justify-content: center;
        flex-direction: column;
        margin-top: 4em;
        margin-bottom: 1em; //da cancellare !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
        border-radius: 10px;
    }
        
    .forma {
        align-self: center;
        width: 90%;
        display: flex;
        justify-content:center;
        border: 2px solid $grigio;
        border-radius: 7px;
        .skill {
            width: 25%;
            text-align: center;
            background-color: $grigio;

            }
            span {
                color: white;
                font-size: 140%;
            }
        }

        .npm {
            background-color: $grigio-2;
            width: 25%;
            text-align: center;
            span {
                color: white;
                font-size: 140%;
            }
    }  
    .sub-forma {
        width: 90%;
        margin-top: 1em;
        align-self: center;       
    }
    
    .green {
        color: $verde-1;
    }

    .container-max-subforma {
        display: flex;
        justify-content: center;

    }

    .container-sub-forma {
        width: 40%;
        span {
            margin-right: 2em;
        }
    }


</style>