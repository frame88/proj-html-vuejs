<template>
        <div class="container-max jumbo">
          <div class="container ">
              <div class="jumbo-sx">
                  <div class="top-jumbo-sx">
                    <span id="development">Development</span>
                    <h1>a complete</h1>
                    <h1>developer toolset</h1>
                    <span>Launch your campaign and benefit from our experties on designing and managing coversion centered bootstrap4 html page.</span>
                  </div>
                  <div class="choise">
                      <a id="getstart" href="">Get Started</a>
                      <a id="docu" href="">Documentation</a>
                  </div>
                  <div class="version">
                        <span>Current version: v2.6.0</span>                  
                  </div> 
              </div>
              <div class="jumbo-dx">
                  <img src="../assets/img/about.png" alt="">
              </div>
          </div>
      </div>
</template>

<script >
export default {

}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";

.container-max, .container {
    background-color: $bianco-2;
}

.jumbo {
    padding-bottom: 3em;
    border-bottom: 2px solid $grigio;
}

.jumbo-sx {
    width: 45%;
    height: 100%;
    margin-top: 3em;
    display: flex;
    flex-direction: column;
    align-self: center;

        h1 {
            text-transform: capitalize;
            margin-top: 0.4em;
            margin-bottom: 0.4em;
        }
        
        span {
            color: $grigio;
        }

    .top-jumbo-sx {
        padding-top: 1em;
        padding-bottom: 1em;
        #development {
            background-color: #007bff34;
            color: $blu;
            padding: 5px 10px;
            border-radius: 15px;
            
        }
    
        
    }

    .choise {
        margin-top: 0.4em;
        padding-bottom: 0.4em;
        a {
            padding: 0.2em 0.8em;
            background-color: $blu;
            margin-right: 0.4em;
            border-radius: 8px;
        }

        #getstart {
            color: $bianco-1;
            border: 2px solid $blu;
        }

        #docu {
            color: $blu;
            border: 2px solid $blu;
            background-color: $bianco-1;
        }
    }
    .version {
        padding-top: 0.4em;
    }
}

.jumbo-dx {
    width: 55%;
    margin-top: 3em;
    display: flex;
    justify-content: flex-end;
    img {
        width: 80%;
    }  
}

</style>