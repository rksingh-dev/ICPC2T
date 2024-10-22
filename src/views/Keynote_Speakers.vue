<template>
  <div class="col-xl-8 col-md-12">
    <!-- Post -->
    <div class="row mt-2 mb-5 pb-3 mx-2">
      <!-- Card -->
      <div class="card card-body mb-5">
        <h2 class="font-weight-bold mt-3">
          <strong>Speakers</strong>
        </h2>
        <!-- <p class="article">Will be Updated Soon.</p> -->
        <carousel id="primary"
      :per-page="1"
      :mouse-drag="false"
      :autoplay=true
      :speed=2000
      :loop=true
      :autoplayHoverPause=true
    >
       <slide
        data-index="0"
        data-name="MySlideName"
      
        :centerMode="true"
      > 
       <div class="speaker-card"> 
        <div class="right">
          <img class="carousel-img" src="@/assets/Kleber Melo e Silva.jpg" />
        </div>
        <div class="left"> <h2><strong>Kleber Melo E Silva</strong></h2>
        <p> An Electrical Engineer, he graduated from the Federal University of Campina Grande (UFCG) in 2004, earning his Master's (2005) and Doctorate (2009) there. He was a Visiting Professor at UEPB in 2007 and a tenured professor at IFPB (2008-2009). Since 2009, he has been a professor at the University of Brasília (UnB), coordinating the LAPSE lab and the PPGEE program (2016-2018, 2021-present). He served as a Visiting Professor at Texas A&M University (2019-2020) and is an Associate Editor for IEEE journals. A Senior Member of IEEE and CNPq Research Fellow (PQ-2), his research focuses on power system protection, fault location, and electromagnetic transients.
        </p>
        </div>
        </div> 
          
      </slide>
      <slide
        data-index="1"
        data-name="MySlideName"
      
        :centerMode="true"
      > 
       <div class="speaker-card"> 
        <div class="right">
          <img class="carousel-img" src="@/assets/Dr Sze Sing Lee.jpg" />
        </div>
        <div class="left"> <h2><strong>Dr Sze Sing Lee </strong></h2>
        <p>Dr. Sze Sing Lee (Senior Member, IEEE) received the B.Eng. (Hons.) and Ph.D. degrees in electrical engineering from Universiti Sains Malaysia, Penang, Malaysia, in 2010 and 2013, respectively. From 2014 to 2019, he was a Lecturer\Assistant Professor with the branch campus of the University of Southampton, Malaysia. From 2018 to 2019, he was a Visiting Research Professor with Ajou University, South Korea. He is currently an Assistant Professor with Newcastle University, Singapore. His research interests include power converter\inverter topologies and their control strategies. Dr. Lee is an Associate Editor for the IEEE TRANSACTIONS ON INDUSTRIAL ELECTRONICS and IEEE ACCESS, and a Guest Associate Editor for the IEEE TRANSACTIONS ON POWER ELECTRONICS. He is a Chartered Engineer registered with Engineering Council, U.K.
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
          <img class="carousel-img" src="@/assets/Dr. Nilesh Jayantilal Vasa.jpg" />
        </div>
        <div class="left"> <h2><strong>Dr. Nilesh Jayantilal Vasa</strong></h2>
        <p>Dr. Nilesh J Vasa is a Professor, Department of Engineering Design, IIT Madras. He is also Dean of students at IIT Madras. His major research interests are Laser-assisted sensing, opto mechatronics, pulsed laser deposition of functional thin films, laser assisted micromanufacturing. He has several patents to his credit and recently applied is "Off-resonant broadband absorption based photoacoustic sensor for multiple gas sensing“ with Ramya Selvaraj, Nilesh J. Vasa, S. M. Shivanagendra. He has authored more than 106 journal articles and 54 conference papers and peer reviewed journals.
        </p>
        </div>
        </div> 
      </slide> 
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
      </slide>  -->
     
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
