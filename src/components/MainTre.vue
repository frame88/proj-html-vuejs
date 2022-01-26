<template>
  <main>
      <div class="container-max">
          <div class="container">
              <div class="box laterale">
                <div class="skill">
                   <span class="type light">Basic</span>
                </div>
                <div class="title"><h1>$9.00</h1></div>
                <div class="sub"><span>{{period}}</span></div>
                <div class="sub-2"><span>{{sub}}</span></div>
                <div class="box-maintwo">
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Full Access</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Enanched Security</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Source Files</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> 1 Domain Free</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Enanched Security</span>
                    </div>
                </div>
                <div class="button-maintwo">
                    <a class="button" href="">Buy Now</a>
                </div>
                <div class="sub">
                    <span class="grigio" >{{card}}</span>
                </div>
              </div>

              <div class="box centrale">
                <div class="skill">
                   <span class="type light">Business</span>
                </div>
                <div class="title"><h1>$39.00</h1></div>
                <div class="sub"><span>{{period}}</span></div>
                <div class="sub-2"><span>{{sub}}</span></div>
                <div class="box-maintwo">
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Full Access</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Enanched Security</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Source Files</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> 1 Domain Free</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Enanched Security</span>
                    </div>
                </div>
                <div class="button-maintwo">
                    <a class="button" href="">Buy Now</a>
                </div>
                <div class="sub">
                    <span class="grigio" >{{card}}</span>
                </div>
              </div>

              <div class="box laterale">
                <div class="skill">
                   <span class="type light">Enterprise</span>
                </div>
                <div class="title"><h1>$79.00</h1></div>
                <div class="sub"><span>{{period}}</span></div>
                <div class="sub-2"><span>{{sub}}</span></div>
                <div class="box-maintwo">
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Full Access</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Enanched Security</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Source Files</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> 1 Domain Free</span>
                    </div>
                    <div class="option">
                        <i class="far fa-check-circle light"></i>
                        <span> Enanched Security</span>
                    </div>
                </div>
                <div class="button-maintwo">
                    <a class="button" href="">Buy Now</a>
                </div>
                <div class="sub">
                    <span class="grigio" >{{card}}</span>
                </div>
              </div>
          </div>

      </div>
      <div class="container-max-short">
          <div class="container-short">
              <div class="title">
                  <h1>Want to be among the first to find out?</h1>
              </div>
              <div class="sub">
                <span class="grigio">Start working with <span class="light">Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.</span>
              </div>
              <input class="barra" type="text" placeholder="Email Address">
          </div>

      </div>
    
  </main>
</template>

<script>


export default {
    name: 'MainTre',
    components: {

    },
    props: {
        Mainskill:Array,
    },
    data() {
        return{
            period: "Per month",
            sub: "All the basic for business that are just getting started",
            card: "*No credit card required",
    }
}}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";

.container-max {
    margin-bottom: 5em;
}

.container {
    justify-content: center;
    align-items: center;
    height: 45vh;
}


.box {
    height: 95%;
}

.box {
    &:hover,
    &:active {
        box-shadow: 1px 1px 5px 5px $grigio;
        height: 100%;
        border-bottom: 5px solid $blu;
    }                                                 
}


.box {
    width: 25%;
    border: 2px solid $grigio;
    border-radius: 8px;
    padding: 1em;
    margin: 1em;

    .skill {
        margin-bottom: 1em;
    }

    .type {
        background-color: #007bff34;
        color: $blu;
        padding: 5px 10px;
        border-radius: 15px;
    }

    title {
        margin-bottom: 1em;
    }

    .sub, .sub-2 {
        margin-bottom: 1em;       
        span {
            color: $grigio;
        }
    }

    .sub-2 {
        padding-bottom: 1em;
        border-bottom: 2px solid $grigio;
    }
    
    .box-maintwo {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        height: 12vh;
        margin-bottom: 1em;
    }

    .option span {
        color: $grigio;
    }

    .button {
    display: block;
    padding: 0.5em;
    margin-bottom: 1em;
    border-radius: 5px;
    text-align: center;
    color: $bianco-2;
    background-color: $blu;
    &:hover,
    &:active {
        background-color: $notte;
    }
    }

    .centrale {
        box-shadow: 5px 5px blue, 10px 10px red, 15px 15px green;
    }
}

.container-max-short {
    display: flex;
    justify-content: center;
}

.container-short {
    width: 60%;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    margin-bottom: 5em;

    .title, .sub {
        margin-bottom: 1em;
        align-self: center;
    }

    .sub {
        width: 50%;
    }

    .barra {
        width: 60%;
        height: 30px;
        border-radius: 30px;
        border: 2px solid $grigio;
        padding: 2em;
        
    }

    ::placeholder {
        color: $grigio;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 120%;
    }

}

</style>