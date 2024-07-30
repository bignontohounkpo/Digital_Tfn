<script>
import card from './card.vue';
import Column from './column.vue';

export default {
  components: {
    card,
    Column
  }
}

</script>

<template>
  <!-- Debut du Header -->
  <section class="navbar">
    <div class="container py-5">
      <nav class="navbar navbar-expand-lg fixed-top container justify-content-between">
        <a class="navbar-brand" href="#">
          <img src="../assets/Images/Frame.svg" alt="Logo" class="" />
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse align-items-center" id="navbarNav ">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link fw-bolder" href="Home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link fw-bolder" href="Top Sales">Top sales</a>
            </li>
            <li class="nav-item">
              <a class="nav-link fw-bolder" href="Collections">Collections</a>
            </li>
            <li class="nav-item">
              <a class="nav-link fw-bolder" href="Our Blog">Our Blog</a>
            </li>
            <li class="nav-item">
              <a class="nav-link fw-bolder" href="About us">About us</a>
            </li>
          </ul>
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <p class="">
                <a class="nav-link fw-bold pt-3" href="#">Sign up</a>
              </p>
            </li>
            <li class="nav-item">
              <p class="">
                <a class="nav-link" href="#">
                  <button class="btn btn-dark fw-bold rounded-5 fs-5">
                    Connect Wallet
                  </button>
                </a>
              </p>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="fas fa-shopping-cart"></i></a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
  </section>
  <section class="Hero-section container py-4">
    <div class="row justify-content-between">
      <div class="col-lg-6 lh-1">
        <span class="display-2">See the NFT</span> <br />
        <span class="display-2"> new world</span>

        <div class="text-ligth">
          Vorem ipsum dolor sit amet, consectetur adipiscing <br />elit. Etiam
          eu turpis molestie, di
        </div>
        <div class="d-flex pt-3 gap-3">
          <p class="text-ligth">
            Discover Vow
            <img src="../assets/Images/circlef.svg" alt="" class="img-fluid" />
          </p>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="d-flex">
          <img src="../assets/Images/circle.svg" class="img-fluid w-25" />
          <img src="../assets/Images/image2.svg" alt="" class="img-fluid w-50 rounded" />
        </div>
      </div>
    </div>
  </section>
  <section class="collections-section container py-4">
    <p class="fw-bold fs-4">Our Collections</p>
    <div class="row justify-content-between text-center">
      <div class="col-lg-7">
        <div class="row ">
          <div class="col-lg-3">
            <button class="btn text-white rounded-3" style="background: #0e1218">
              All categories
            </button>
          </div>
          <div class="col-lg-1">
            <button class="btn back rounded-3">Art</button>
          </div>
          <div class="col-lg-3">
            <button class="btn rounded-3 back">All categories</button>
          </div>
          <div class="col-lg-3">
            <button class="btn rounded-3 back">Gaming</button>
          </div>
          <div class="col-lg-2">
            <button class="btn rounded-3 back">Sport</button>
          </div>
        </div>
      </div>
      <div class="col-lg-3 justify-content-end">
        <a href="#" class="text-dark">views more </a>
      </div>
    </div>
  </section>
  <section class=" container py-4">
    <div class="row">
      <div class="col-lg-3">
        <card imageSrc="" title="CyberPunk" bottomImageSrc="./image3.svg" />

      </div>
      <div class="col-lg-3">
        <card imageSrc="" title="CyberPunk" bottomImageSrc="./image4.svg" />

      </div>
      <div class="col-lg-3">
        <card imageSrc="" title="CyberPunk" bottomImageSrc="./image5.svg" />

      </div>
      <div class="col-lg-3">
        <card imageSrc="" title="CyberPunk" bottomImageSrc="./image6.svg" />

      </div>

    </div>
  </section>

  <section class="container ">
    <p class="fw-bold fs-5">
      Create and Sell Now
    </p>

    <div class="row justify-content-center">
      <div class="col-lg-3">
        <column 
        backgroundImage="./cloud-download.svg" 
        title="Mon Titre"
        >
        
        </column>
      </div>
    </div>
  </section>
  <!-- Footer -->
  <section class="container py-5">
    <footer class="">
      <div>
        <img src="../assets/Images/Frame.svg" alt="" class="img-fluid" />
        <hr />
      </div>
      <div class="row justify-content-between">
        <div class="col-lg-6 col-sm-10 py-2">
          <p class="fw-bolder fs-3">Create Explore & Collect Digital NFTs</p>
        </div>
        <div class="col-lg-5 justify-content-lg-end">
          <div class="d-flex justify-content-evenly">
            <p class="">Privacy</p>
            <p class="">Terms & Conditions</p>
            <p class="">About Us</p>
          </div>
        </div>
      </div>
    </footer>
  </section>
</template>

<style scoped>
.back {
  background: #e8e9ea;
}
</style>
