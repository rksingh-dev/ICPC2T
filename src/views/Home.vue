<template>
  <div class="col-xl-8 col-md-12">
    <!-- Post -->
    <div class="row mt-2 mb-5 pb-3 mx-2">
      <!-- Card -->
      <div class="card card-body mb-5">
        <!-- Title -->

        <h2 class="font-weight-bold mt-3">
          <strong>About the Institution</strong>
        </h2>

        <hr class="red title-hr" />
        <p class="article">
          National Institute of Technology Raipur (Formerly Government
          Engineering College Raipur), situated in the capital of a newly
          Incepted state of Chhattisgarh, has proven to be "avant-grade' in the
          field of science and technology over past few decades in this region.
          With sweet memory of foundation ceremony by our President Hon'ble Dr.
          Rajendra Prasad on 14th September 1956, the institute started with two
          departments namely Metallurgical and Mining Engineering. Later the
          inauguration of the Institute building was done by our Prime Minister
          Hon'ble Pt. Jawahar Lal Nehru on 14th March 1963. From 1st December
          2005, the institute has become the National Institute of Technology.
          The institution has grown in tandem with the major surrounding
          industries – The Bhilai Steel Plant, SECL BALCO and NTPC Korba. It
          currently offers 12 Undergraduate and 6 Postgraduate courses including
          MCA and M.Tech in Applied Geology.
        </p>
        <h2 class="font-weight-bold mt-3">
          <strong>About Conference</strong>
        </h2>

        <hr class="red title-hr" />
        <p class="article">
          ICPC<sup>2</sup>T is organized by National Institute of Technology
          Raipur and technically co-sponsored by IEEE Madhya Pradesh Section,
          IEEE Student Section NIT Raipur, IES Chapter IEEE MP Section and PELS
          Chapter IEEE MP Section. ICPC<sup>2</sup>T will give a chance to the
          students, academicians, researchers, scientists and practicing
          engineers to have a platform for potential knowledge exchange on
          recent trends, theories and practices of Power Systems, Power
          Electronics, Machine Drives, Control Systems and Computational
          Technologies. Particularly, emphasis will be placed on promotion of
          new and renewable sources of power, Smart Grid and related
          cyber-physical systems. Applications of data analytics to power
          systems, such as demand response and demand side management will be
          considered. Finally, the innovative use of artificial intelligence,
          machine learning and deep learning and data visualization approaches
          for the power management in a variety of contexts including efficient
          network management, improved situational awareness and anomaly
          detection will be of interest. ICPC<sup>2</sup>T features invited
          talks and Keynote address from eminent professors/scientists from
          across the world, pre-conference workshops/tutorials from active
          engineers and technical paper presentation of the participants from
          different parts of the world.
        </p>
      </div>
      <div class="card card-body mb-5">
      <p style="color:red">
        All the registered and presented papers in the conference will only be submitted to IEEE for their inclusion into IEEE Xplore which is Scopus indexed and the eligible presented papers in the conference may be further reviewed for their publication in the IEEE Transaction on Industry Applications or IEEE IAS Magazine.
      </p>
        <h4><b>Previous conference proceedings links</b></h4>
        <ul>
          <li>
            ICPC2T
            <a
              href="https://ieeexplore.ieee.org/xpl/conhome/9051868/proceeding"
            >
              2020</a
            >
          </li>
          <li>
            ICPC2T
            <a
              href="https://ieeexplore.ieee.org/xpl/conhome/9776593/proceeding"
            >
              2022</a
            >
          </li>
          <li>
            ICPC2T
            <a
              href="https://ieeexplore.ieee.org/xpl/conhome/10474598/proceeding"
            >
              2024</a
            >
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
<style scoped>
/* Optional: Add additional styling for full-width card */
.card {
  width: 100%; /* Ensures the card spans full width */
}

.article {
  font-size: 1.2rem;
  line-height: 1.6;
  width: 100%
  ;
}

hr.red {
  border: 1px solid red;
}

.container-fluid {
  padding-left: 0;
  padding-right: 0;
}

.row {
  margin-left: 0;
  margin-right: 0;
}

/* Media Query for screens larger than 1440px */
@media (min-width: 1440px) {
  .container-fluid {
    padding-left: 0;
    padding-right: 0;
  }
  
  .card {
    width: 100%; /* Ensures no width restriction */
  }
}

h2, h4, p, li {
  font-family: Ubuntu, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji",
    "Segoe UI Symbol";
}
</style>
