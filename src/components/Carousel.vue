T<template>
  <div>
    <marquee
      behavior=""
      direction=""
      class="red-text"
      onmouseover="this.stop();"
      onmouseout="this.start();"
    >
    Congratulations! The proceedings of the 2024 Third International Conference on Power, Control, and Computing Technologies (ICPC<sup>2</sup>T) have been published and are now available on the IEEE Xplore digital library as of 2024-03-25 : <a href="https://ieeexplore.ieee.org/xpl/conhome/10474598/proceeding">Click Here</a>. ICPC2T is now accepting papers in the approved special sessions and papers can be submitted on <a
            href="https://cmt3.research.microsoft.com/ICPC2T2025/Submission/Index"
            >paper submission portal</a
          ></marquee
    >
    <div id="carousel-main-div-for-spacing">
      <!-- Carousel Wrapper -->
      <!-- Second ieee Icpc2t Hybrid conference - schedule | All accepted & presented papers will be published in IEEE Xplore (Proceedings indexed in Scopus) | Fully Hybrid presentations -->
      <div
        id="carousel-example-1z"
        class="carousel slide carousel-fade"
        data-ride="carousel"
      >
        <carousel
          :per-page="1"
          :mouse-drag="true"
          :loop="true"
          :autoplay="true"
        >
          <slide>
            <!--First slide-->
            <div class="carousel-item active">
              <div class="row">
                <div class="col-md-4 clearfix d-none d-md-block">
                  <div class="card mb-2">
                    <img
                      class="card-img-top"
                      src="@/assets/nitfront.jpg"
                      alt="Card image cap"
                    />
                  </div>
                </div>
                <div class="col-md-4 clearfix d-none d-md-block">
                  <div class="card mb-2">
                    <img
                      class="card-img-top"
                      src="@/assets/GateNIT.jpg"
                      alt="Card image cap"
                    />
                  </div>
                </div>

                <div class="col-md-4">
                  <div class="card mb-2">
                    <img
                      class="card-img-top"
                      src="@/assets/NIT.jpg"
                      alt="Card image cap"
                    />
                  </div>
                </div>
              </div>
            </div>
            <!--/.First slide-->
          </slide>
          <slide>
            <!--Third slide-->
            <div class="carousel-item active">
              <div class="row">
                <div class="col-md-4">
                  <div class="card mb-2">
                    <img
                      class="card-img-top"
                      src="@/assets/nitnight.jpg"
                      alt="Card image cap"
                    />
                  </div>
                </div>

                <div class="col-md-4 clearfix d-none d-md-block">
                  <div class="card mb-2">
                    <img
                      class="card-img-top"
                      src="@/assets/nitnight gate.jpg"
                      alt="Card image cap"
                    />
                  </div>
                </div>

                <div class="col-md-4 clearfix d-none d-md-block">
                  <div class="card mb-2">
                    <img
                      class="card-img-top"
                      src="@/assets/nightground.jpg"
                      alt="Card image cap"
                    />
                  </div>
                </div>
              </div>
            </div>
            <!--/.Third slide-->
          </slide>
        </carousel>
      </div>
      <!-- Carousel Wrapper -->
    </div>
  </div>
</template>

<script>
export default {
  name: "ABCD",
};
</script>

<style scoped>
#carousel-main-div-for-spacing {
  margin-right: 50px;
  margin-left: 50px;
}
.col-md-4 {
  padding-top: 0;
  padding-right: 5px;
  padding-bottom: 0;
  padding-left: 5px;
}
img {
  max-height: 220px;
  height: 100%;
  width: 100%;
}
marquee {
  padding-top: 5px;
  padding-bottom: 4px;
  font-size: 15px;
  font-weight: 400;
}
</style>

<!-- Add "scoped" attribute to limit CSS to this component only -->
