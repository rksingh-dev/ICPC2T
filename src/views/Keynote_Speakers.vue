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
          <img class="carousel-img" src="@/assets/Akshay.png" />
        </div>
        <div class="left"> <h2><strong>Akshay Kumar Rathore</strong></h2>
        <p>Akshay Kumar Rathore (IEEE Fellow) is an expert in power electronics and control of electrical motor drives. He received the Gold Medal for  securing  the  highest academic  standing  in his Master’s  degree among  all  electrical  engineering  specializations at Indian  Institute  of  Technology (BHU) Varanasi,  India. He had two subsequent postdoctoral research appointments with the University of Wuppertal, Germany (2008-2009), and the University of Illinois at Chicago, USA (2009-2010).  From November 2010 to February 2016, he served as an Assistant Professor at the Department of Electrical   and   Computer   Engineering, National   University   of Singapore. From March 2016-Dec 2021, he served as an Associate Professor at the Department of Electrical   and   Computer   Engineering, Concordia University, Montreal, Canada where he was listed in the Provost Circle of Distinction in 2021. He served as Graduate Program Director and Chair of Graduate Awards during 2020-21.
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
          <img class="carousel-img" src="@/assets/Kleber Melo e Silva.jpg" />
        </div>
        <div class="left"> <h2><strong>Kleber Melo E Silva</strong></h2>
        <p> An Electrical Engineer, he graduated from the Federal University of Campina Grande (UFCG) in 2004, earning his Master's (2005) and Doctorate (2009) there. He was a Visiting Professor at UEPB in 2007 and a tenured professor at IFPB (2008-2009). Since 2009, he has been a professor at the University of Brasília (UnB), coordinating the LAPSE lab and the PPGEE program (2016-2018, 2021-present). He served as a Visiting Professor at Texas A&M University (2019-2020) and is an Associate Editor for IEEE journals. A Senior Member of IEEE and CNPq Research Fellow (PQ-2), his research focuses on power system protection, fault location, and electromagnetic transients.
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
          <img class="carousel-img" src="@/assets/Vinod_KU.jpg" />
        </div>
        <div class="left"> <h2><strong>Prof. Vinod Khadkikar</strong></h2>
        <p>Prof. Khadkikar, an IEEE Fellow since 2022, is known for his contributions to power quality solutions. He serves as Co-Editor-in-Chief of IEEE Transactions on Industrial Electronics and is a Distinguished Lecturer for the IEEE Industry Applications Society. He has held roles on the IEEE IAS Fellow Evaluation committee and as an Associate Editor for IEEE Transactions on Industry Applications and IET Power Electronics.With a B.E. from Government College of Engineering, Aurangabad, an M.Tech. from IIT Delhi, and a Ph.D. from ETS Montreal, he has held academic positions at the University of Western Ontario, MIT, and currently at Khalifa University, Abu Dhabi, where he joined in 2010. He has authored over 75 IEEE Transactions papers and was ranked among the top 2% of researchers in Electrical Engineering globally by Stanford University in 2022. He also serves as a Scientist Member in the Mohammed bin Rashid Academy of Scientists (MBRAS) and holds leadership roles in energy-focused research themes at Khalifa University.
        </p>
        </div>
        </div> 
      </slide> 
      <slide
        data-index="3"
        data-name="MySlideName"
      
        :centerMode="true"
      >
      
      <div class="speaker-card"> 
        <div class="right">
          <img class="carousel-img" src="@/assets/Biplab.jpg" />
        </div>
        <div class="left"> <h2><strong>Biplab Sikdar</strong></h2>
        <p>Biplab Sikdar is a Professor in the Department of Electrical and Computer Engineering at the National University of Singapore. He currently serves as the Head of Department for the Department of Electrical and Computer Engineering, and leads the $54 million Cisco-NUS corporate research laboratory. He received the B. Tech. degree in electronics and communication engineering from NERIST, North Eastern Hill University, Shillong, India, in 1996, the M.Tech. degree in electrical engineering from the Indian Institute of Technology, Kanpur, India, in 1998, and the Ph.D. degree in electrical engineering from the Rensselaer Polytechnic Institute, Troy, NY, USA, in 2001. He was an Assistant Professor from 2001-2007 and Associate Professor from 2007-2013 in the Department of Electrical, Computer, and Systems Engineering at Rensselaer Polytechnic Institute from 2001 to 2013. He is a recipient of the NSF CAREER award, the Tan Chin Tuan fellowship from NTU Singapore, the Japan Society for Promotion of Science fellowship, and the Leiv Eiriksson fellowship from the Research Council of Norway. His research interests include IoT and cyber-physical system security, network security, and network performance evaluation. Dr. Sikdar is a member of Eta Kappa Nu and Tau Beta Pi, and IEEE Distinguished Lecturer and ACM Distinguished Speaker. He has served as an Associate Editor for the IEEE Transactions on Communications, IEEE Transactions on Mobile Computing, IEEE Internet of Things Journal, and IEEE Open Journal of Vehicular Technology.
        </p>
        </div>
        </div> 
      </slide> 
      <slide
        data-index="4"
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
        data-index="5"
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
width: 50%;
  gap: 15px;
}
.speaker-card .left{
  padding-left: 10px;
  height:fit-content;
  width: 70%;
  text-align: justify;
  text-justify: inter-word;
}
@media(max-width:800px) {
  .speaker-card{
    display:block;
  }
  
}
 
</style>
