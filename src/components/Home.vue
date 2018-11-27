z<template>
  <div class="container home">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Buddha Quotes</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Quotes</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="row quote my-2">
      <div class="col-10 offset-1 d-flex justify-content-center align-items-center">
        <img class="rounded-circle" src="https://www.lionsroar.com/wp-content/uploads/2017/02/5-DP297456r4_61A-1-1-600x343.jpg">
        <div class="content w-100">
          <h4 class="ml-2">The mind is everything. What you think you become</h4>
        </div>
        <h6 class="text-right align-self-end">Buddha</h6>
      </div>
    </div>
    <div class="row quote my-2">
      <div class="col-10 offset-1 d-flex justify-content-center align-items-center">
        <img class="rounded-circle" src="https://images.fineartamerica.com/images/artworkimages/mediumlarge/1/incense-buddha-daniel-hagerman.jpg">
        <div class="content w-100">
          <h4 class="ml-2">In the end, only three things matter: how much you loved, how gently you lived, and how gracefully you let go of things not meant for you.</h4>
        </div>
        <h6 class="text-right align-self-end">Buddha</h6>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.home {
  .quote {
    padding-bottom: 10px;
    background:
      linear-gradient(
        to left, 
        #ffffff 0%,
        #ffffff 10%,
        #000 50%,
        #ffffff 90%,
        #ffffff 100%
      )
      left 
      bottom
      no-repeat; 
    background-size:100% 1px;

    img {
      width: 80px;
      height: 80px;
      object-fit: cover;
    }

    h4 {
      font-size: 25px;
    }

    p {
      font-weight: 700;
    }
  }
}
</style>
