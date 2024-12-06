<template>
  <!-- Sidebar -->
  <div class="col-xl-4 col-md-12 widget-column mt-0">
    <!-- Section: Announcement -->
    <section class="section mb-5">
      <h4 class="mt-2 text-center">
        <strong>ANNOUNCEMENT</strong>
      </h4>
      <hr class="red title-hr" />
      <div class="card card-body d-flex text-center">
        <p class="card-text red-text">
          <marquee
            direction="up"
            height="150px"
            scrollamount="2"
            scrolldelay="3"
            onmouseover="this.stop();"
            onmouseout="this.start();"
          >
            Paper Submission starts: 30<sup>th</sup> June 2024<br /><br />
            Deadline for Full Paper Submission: <s>22<sup>nd</sup> October 2024</s>   
            30<sup>th</sup> October 2024 (hard deadline)<br /><br /> 
            Acceptance Notification: <s>15<sup>th</sup> November 2024</s> 20<sup>th</sup> November 2024<br /><br /> 
            Camera Ready Paper Submission: <s>30<sup>th</sup> November 2024</s> 5<sup>th</sup> December 2024<br /><br /> 
            Registration Deadline: <s>5<sup>th</sup> December 2024</s> 15<sup>th</sup> December 2024<br /><br /> 
          </marquee>
        </p>
      </div>
    </section>

    <!-- Section: Countdown Timer -->
    <section class="section mb-5">
      <h4 class="mt-2 text-center">
        <strong>COUNTDOWN TO EVENT</strong>
      </h4>
      <hr class="red title-hr" />
      <div class="card card-body text-center">
        <div class="countdown-timer">
          <div class="time-block">
            <span class="time">{{ days }}</span>
            <p>Days</p>
          </div>
          <div class="time-block">
            <span class="time">{{ hours }}</span>
            <p>Hours</p>
          </div>
          <div class="time-block">
            <span class="time">{{ minutes }}</span>
            <p>Minutes</p>
          </div>
          <div class="time-block">
            <span class="time">{{ seconds }}</span>
            <p>Seconds</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Section: Important Dates -->
    <section class="section mt-5">
      <h4 class="mt-2 text-center">
        <strong>IMPORTANT DATES</strong>
      </h4>
      <hr class="red title-hr" />
      <ul class="list-group z-depth-1 mt-4">
        <li class="list-group-item">Camera ready: 5<sup>th</sup> December 2024</li>
        <li class="list-group-item">Registration deadline: 15<sup>th</sup> December 2024</li>
        <li class="list-group-item">Conference start date: 20<sup>th</sup> January 2025</li>
        <li class="list-group-item">Paper Submission starts: 30<sup>th</sup> June 2024</li>
        <li class="list-group-item">
          Deadline for Full Paper Submission Extended to: 
          <s>22<sup>nd</sup> October 2024</s> 30<sup>th</sup> October 2024 (hard deadline)
        </li>
        <li class="list-group-item">Acceptance Notification: <s>15<sup>th</sup> November 2024</s> 20<sup>th</sup> November 2024</li>
      </ul>
    </section>

    <!-- Section: Technical Sponsors -->
    <section class="section mb-5">
      <h4 class="mt-2 text-center">
        <strong>TECHNICAL SPONSORS</strong>
      </h4>
      <hr class="red title-hr" />
      <div class="card card-body d-flex text-center">
        <p class="card-text red-text">
          <carousel
            :per-page="1"
            :mouse-drag="true"
            :loop="true"
            :autoplay="true"
          >
            <slide>
              <img src="@/assets/partners/ieee_mp_section.jpg" alt="" />
            </slide>
            <slide>
              <img src="@/assets/partners/ieeespons.png" alt="" />
            </slide>
            <slide>
              <img src="@/assets/partners/pels.png" alt="" />
            </slide>
            <slide>
              <img src="@/assets/partners/ias.png" alt="" />
            </slide>
          </carousel>
        </p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Side",
  data() {
    return {
      eventDate: new Date("2025-01-20T00:00:00"), // Conference start date
      days: 0,
      hours: 0,
      minutes: 0,
      seconds: 0,
    };
  },
  mounted() {
    this.startCountdown();
  },
  methods: {
    startCountdown() {
      setInterval(() => {
        const now = new Date();
        const timeDifference = this.eventDate - now;

        if (timeDifference > 0) {
          this.days = Math.floor(timeDifference / (1000 * 60 * 60 * 24));
          this.hours = Math.floor((timeDifference / (1000 * 60 * 60)) % 24);
          this.minutes = Math.floor((timeDifference / (1000 * 60)) % 60);
          this.seconds = Math.floor((timeDifference / 1000) % 60);
        }
      }, 1000);
    },
  },
};
</script>

<style scoped>
.countdown-timer {
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin-top: 10px;
}

.time-block {
  text-align: center;
  margin: 0 10px;
}

.time {
  font-size: 2rem;
  font-weight: bold;
  color: #d32f2f;
}

p {
  margin: 0;
  font-size: 1rem;
  font-weight: bold;
}

ul.list-group {
  padding-left: 0;
}

.list-group-item {
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  background-color: #fff;
}

.list-group-item:hover {
  background-color: rgb(184, 221, 248);
}

img {
  width: 100%;
  height: 100%;
}
</style>
