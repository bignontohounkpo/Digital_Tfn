<script>
import AnimeSection from "./AnimeSection.vue";
import CardSection from "./CardSection.vue";

export default {
  components: {
    AnimeSection,
    CardSection,
  },
};
</script>

<template>
  <div class=" border-1 border-start ps-0 container">

    <!-- Debut du Header -->
    
      <div class="container ">
        <nav class="navbar navbar-expand-lg container justify-content-between">
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

                  <a class="nav-link fw-bold" href="#">
                    |
                    <button class="btn btn-dark fw-bold rounded-5 fs-5">
                      Connect Wallet
                    </button>
                  </a>
                </p>
              </li>
            </ul>
          </div>

        </nav>

      </div>

      <div class="border border-bottom-"></div>
   

    <section class="Hero-section container py-4">
      <div class="row justify-content-center">
        <div class="col-lg-6 col-md-10">
          <span class="display-2">See the NFT</span> <br />
          <span class="display-2"> new world</span>

          <div class="text-ligth">
            Vorem ipsum dolor sit amet, consectetur adipiscing <br />elit. Etiam
            eu turpis molestie, di
          </div>
          <div class="d-flex pt-3 gap-3">
            <p class="text-ligth">
              Discover Vow
            </p>
            <span> <img src="../assets/Images/circlef.svg" alt="" class="img-fluid w-50" />
            </span>

          </div>
        </div>
        <div class="col-lg-6 col-md-10">
          <div class="d-flex">
            <div class="">
              <img src="../assets/Images/circle.svg " class="img-fluid w-50 px-auto" />
              <img src="../assets/Images/Rectangle 3.svg" class="img-fluid w-75" />
            </div>
            <div class="">
              <img src="../assets/Images/Rectangle 4.svg" class="img-fluid" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- collections -->
    <section class="collections-section container py-4">
      <p class="fw-bold fs-4">Our Collections</p>
      <div class="d-flex justify-content-md-between fw-semibold align-items-end flex-wrap">
        <p class=" d-flex align-items-end flex-wrap mb-3">

          <button class="btn btn-dark px-lg-3 px-2 me-lg-2 me-1 mt-2 mt-md-2 " style="background: #0e1218">
            All categories
          </button>
          <button className="btn  px-lg-3 px-2 mx-lg-2 mx-1 mt-2 mt-md-2 back rounded-3">Art</button>
          <button class="btn  px-lg-3 px-2 mx-lg-2 mx-1 mt-2 mt-md-2 back rounded-3">Collections</button>
          <button class="btn  px-lg-3 px-2 mx-lg-2 mx-1 mt-2 mt-md-2 back rounded-3">Gaming</button>
          <button class="btn  px-lg-3 px-2 mx-lg-2 mx-1 mt-2 mt-md-2 back rounded-3">Sport</button>
        </p>
        <p class="text-end text-decoration-underline line link-offset-2-hover d-none d-md-inline">Views more </p>
      </div>

    </section>
    <section class="container py-4">
      <div class="row justify-content-center pt-2 pb-5 justify-content-lg-between">
        <div class="col-lg-3 col-md-5 col-sm-6 col-10 py-3">
          <AnimeSection imageSrc="./ethereum-ellipse.svg" title="CyberPunk" bottomImageSrc="./image3.svg" />
        </div>
        <div class="col-lg-3 col-md-5 col-sm-6 col-10 py-3 ">
          <div class="border p-2 rounded-4 border-secondary ">
            <img src="../assets/Images/image4.svg " alt="" class="img-fluid py-1 rounded-4 " style="height: 100%;">
            <div class="d-flex justify-content-between align-items-center py-2  pt-5">
              <p class="card-title fw-bold">Boll - Upper</p>
              <p class="fw-bold"><img src="../assets/Images/ethereum-ellipse.svg" alt="" class="img-fluid "> 68 </p>
            </div>

            <div class="border p-2 text-center rounded-3 border-dark fw-ssemibold">
              Place a Bid
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-5 col-sm-6 col-10 py-3">
          <AnimeSection imageSrc="./ethereum-ellipse.svg" title="Space X Wiper" bottomImageSrc="./image5.svg" />
        </div>
        <div class="col-lg-3 col-md-5 col-sm-6 col-10 py-3">
          <AnimeSection imageSrc="./ethereum-ellipse.svg" title="Snoop Dogg" bottomImageSrc="./image6.svg" />
        </div>
      </div>
    </section>

    <section class="container">
      <p class="fw-bold fs-5">Create and Sell Now</p>

      <div class="row justify-content-center">
        <div class="col-lg-3 col-md-5 col-sm-6 col-10 py-3">
          <CardSection backgroundImage="./sale-tag-02.svg" title="Set up your wallet
">
          </CardSection>
        </div>
        <div class="col-lg-3 col-md-5 col-sm-6 col-10 py-3">
          <CardSection backgroundImage="./cloud-download.svg" title="Add your NFT’s">
          </CardSection>
        </div>

        <div class="col-lg-3 col-md-5 col-sm-6 col-10 py-3">
          <CardSection backgroundImage="./wallet-02.svg" title="Promote your NFT’s">
          </CardSection>
        </div>

        <div class="col-lg-3 col-md-5 col-sm-6 col-10 py-3">
          <CardSection backgroundImage="./bitcoin-ellipse.svg" title="Sell your NFT’s
">
          </CardSection>
        </div>
      </div>
    </section>
    <section class=" container">
      <div class=" p1 py-4 rounded-4">
        <div class="text-center">
            <p class="text-white display-4">Build your NFT profile</p>
            <p class="text-white">Join almost 10k NFT profiles on Digit !</p>
            <button class="btn rounded-4" style="background-color: white">
              Sign up now
            </button> 
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

  </div>
</template>

<style scoped>
.back {
  background: #b8babe;
}

.p1{
  background-image: url(../assets/Images/image.svg);

  
}
</style>
