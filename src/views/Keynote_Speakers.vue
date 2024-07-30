<template>
  <div class="col-xl-8 col-md-12">
    <!-- Post -->
    <div class="row mt-2 mb-5 pb-3 mx-2">
      <!-- Card -->
      <div class="card card-body mb-5">
        <h2 class="font-weight-bold mt-3">
          <strong>Speakers</strong>
        </h2>
        <p class="article">Will be Updated Soon.</p>
        <carousel id="primary"
      :per-page="1"
      :mouse-drag="false"
      :autoplay=true
      :speed=2000
      :loop=true
      :autoplayHoverPause=true
    >
      <!-- <slide
        data-index="0"
        data-name="MySlideName"
      
        :centerMode="true"
      > -->
      <!-- <div class="speaker-card"> 
        <div class="right">
          <img class="carousel-img" src="@/assets/ak_rathore.jpeg" />
        </div>
        <div class="left"> <h2><strong>Akshay Kumar Rathore</strong></h2>
        <p> Prof. Akshay Kumar Rathore (IEEE Fellow), an expert in power electronics and 
          control of electrical motor drives. He received his Master's degree(GOLD MEDALIST) at IIT BHU,India.
           He had two subsequent postdoctoral research appointments with the University of Wuppertal,Germany,
            and the University of Illinois at Chicago, USA. From November 2010 to February 2016, 
            he served as an Assistant Professor at the Department of Electrical and Computer Engineering,
           National University of Singapore and from March 2016-Dec 2021 in Concordia University,Montreal respectively.
        </p>
        </div>
        </div> -->
          
      <!-- </slide>
      <slide
        data-index="1"
        data-name="MySlideName"
      
        :centerMode="true"
      > -->
      <!-- <div class="speaker-card"> 
        <div class="right">
          <img class="carousel-img" src="@/assets/bhimsing_sir.jpg" />
        </div>
        <div class="left"> <h2><strong>Bhim Singh </strong></h2>
        <p> Prof. Bhim Singh has received his B.E. (Electrical) from the University of Roorkee, India, in 1977 
          and his M. Tech. (Power Apparatus & Systems) and Ph.D. from the IIT Delhi, India, 
          in 1979 and 1983, respectively.

          In 1983, he joined the Department of Electrical Engineering, University of Roorkee (Now IIT Roorkee),as a Lecturer.
          Later, he joined the Department of Electrical Engineering, IIT Delhi, India.He has been HOD(Electrical) at 
          IIT Delhi from July 2014 to August 2016. Later, Prof. Singh has been Dean Academics at IIT Delhi from August 2016 to
          August 2019.
        </p>
        </div>
        </div>
          
      </slide>
      <slide
        data-index="2"
        data-name="MySlideName"
      
        :centerMode="true"
      >
      <div class="speaker-card"> 
        <div class="right">
          <img class="carousel-img" src="@/assets/mk_badapanda.jpg" />
        </div>
        <div class="left"> <h2><strong>M.K Badapanda</strong></h2>
        <p>Prof. Manmath Kumar Badapanda has received his B.Tech in Electrical Engineering 
          from Veer Surendra Sai University of Technology, Burla, Odisha in 1988; M.Tech in Electrical Engineering from IIT BHU, in 1990 
          and P.G Diploma in Business Administration degree from IIMS, Kolkata in 1999.
          He has started his professional career with DLW, Varanasi, Ministry of Indian Railways, 
          Government of India in 1991.Later he shifted to RRCAT, Indore,
          a premier Research and Development organization under Department of Atomic Energy, Government of India.
        </p>
        </div>
        </div> 
      </slide> -->
      <!-- <slide
        data-index="1"
        data-name="MySlideName"
      
        :centerMode="true"
      >
        <img class="carousel-img" src="@/assets/speaker2.jpeg" />
      </slide>
      <slide
        data-index="2"
        data-name="MySlideName"
      
        :centerMode="true"
      >
        <img class="carousel-img" src="@/assets/speaker3.jpg" />
      </slide> -->
     
    </carousel>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Keynote_Spaeakers",
  components: {},
};
</script>

<style scoped>
.carousel-img {
  height: 400px;
  width: 300px;
  padding-left: 10px ;
}
.speaker-card{
  display: flex;
  /* flex-wrap: wrap; */
  gap: 15px;
}
.speaker-card .left{
  padding-left: 10px;
  height:fit-content;
  width: 100%;
  text-align: justify;
  text-justify: inter-word;
}
@media(max-width:800px) {
  .speaker-card{
    display:block;
  }
  
}
 
</style>
