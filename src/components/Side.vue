<template>
  <div class="col-xl-4 col-md-12 widget-column mt-0">
    <!-- Countdown Timer -->
    <section class="section mb-5">
      <h4 class="mt-2 text-center"><strong><b>COUNTDOWN TO EVENT</b></strong></h4>
      <hr class="red title-hr" />
      <div class="table-responsive mt-4">
        <table class="table table-bordered custom-table">
          <thead class="thead-dark">
            <tr>
              <th class="text-center">Days</th>
              <th class="text-center">Hours</th>
              <th class="text-center">Minutes</th>
              <th class="text-center">Seconds</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="text-center" style="color: red; font-weight: bold;">{{ days }}</td>
              <td class="text-center" style="color: red; font-weight: bold;">{{ hours }}</td>
              <td class="text-center" style="color: red; font-weight: bold;">{{ minutes }}</td>
              <td class="text-center" style="color: red; font-weight: bold;">{{ seconds }}</td>
            </tr>
          </tbody>
        </table>
      </div>
    </section>

    <hr class="my-3" />

    <!-- Announcements -->
    <section class="section mb-5">
      <h4 class="mt-2 text-center heading-font"><strong>ANNOUNCEMENT</strong></h4>
      <hr class="red title-hr" />
      <div class="table-responsive mt-4">
        <table class="table table-bordered custom-table">
          <thead class="thead-dark">
            <tr>
              <th class="text-center">Details</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td style="color: red;">
                <marquee
                  direction="up"
                  height="150px"
                  scrollamount="2"
                  scrolldelay="3"
                  onmouseover="this.stop();"
                  onmouseout="this.start();"
                >
<<<<<<< HEAD
                  <br /><br />
                  Paper Submission starts: 18<sup>th</sup> June 2025<br /><br />
                  Deadline for Full Paper Submission: 30<sup>th</sup> September 2025<br /><br />
                  Acceptance Notification: 1<sup>st</sup> November 2025<br /><br />
                  Camera Ready Paper Submission: 15<sup>th</sup> November 2025<br /><br />
                  Registration Deadline: 15<sup>th</sup> December 2025<br /><br />
=======
                  All the accepted papers should be presented in physical mode only.
                  <br /><br />
                  Paper Submission starts : 30<sup>th</sup> June 2024<br /><br />
                  Deadline for Full Paper Submission :
                  <s>22<sup>nd</sup> October 2024</s> 30<sup>th</sup> October 2024 (hard deadline)
                  <br /><br />
                  Acceptance Notification :
                  <s>15<sup>th</sup> November 2024</s> 20<sup>th</sup> November 2024
                  <br /><br />
                  Camera Ready Paper Submission :
                  <s>30<sup>th</sup> November 2024</s> 5<sup>th</sup> December 2024
                  <br /><br />
                  Registration Deadline :
                  <s>15<sup>th</sup> December 2024</s> 20<sup>th</sup> December 2024
                  <br /><br />
>>>>>>> origin/main
                </marquee>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </section>

    <hr class="my-3" />

    <!-- Important Dates Section -->
    <section class="section mb-5">
      <h4 class="mt-2 text-center heading-font"><strong>IMPORTANT DATES</strong></h4>
      <hr class="red title-hr" />
      <div class="table-responsive mt-4">
        <table class="table table-bordered custom-table">
          <thead class="thead-dark">
            <tr>
              <th class="text-center" colspan="2">Important Dates</th>
            </tr>
          </thead>
          <tbody>
            <tr>
<<<<<<< HEAD
              <td><strong>Paper submission starts:</strong></td>
              <td>18<sup>th</sup> June 2025</td>
            </tr>
            <tr>
              <td><strong>Deadline for Full Paper Submission:</strong></td>
              <td>30<sup>th</sup> September 2025</td>
            </tr>
            <tr>
              <td><strong>Acceptance Notifications:</strong></td>
              <td>1<sup>st</sup> November 2025</td>
            </tr>
            <tr>
              <td><strong>Camera Ready Paper Submission:</strong></td>
              <td>15<sup>th</sup> November 2025</td>
            </tr>
            <tr>
              <td><strong>Registration deadline:</strong></td>
              <td>15<sup>th</sup> December 2025</td>
            </tr>
          </tbody>
        </table>
      </div>
    </section>

    <hr class="my-3" />

    <!-- Vue-rendered CMT Acknowledgement -->
    <section class="section mb-5" style="margin-top: 40px;">
      <h4 class="mt-2 text-center heading-font"><strong> The CMT Acknowledgement </strong></h4>
      <hr class="red title-hr" />
      <div class="mt-4" style="color: red; font-weight: normal; font-size: 16px; line-height: 1.6;">
        The Microsoft CMT service was used for managing the peer-reviewing process for this conference. This service was provided for free by Microsoft and they bore all expenses, including costs for Azure cloud services as well as for software development and support.
=======
              <td><strong>Camera ready:</strong></td>
              <td>5<sup>th</sup> December 2024</td>
            </tr>
            <tr>
              <td><strong>Registration deadline:</strong></td>
              <s>15<sup>th</sup> December 2024</s> 20<sup>th</sup> December 2024 
            </tr>
            <tr>
              <td><strong>Paper submission starts:</strong></td>
              <td>30<sup>th</sup> June 2024</td>
            </tr>
            <tr>
              <td><strong>Deadline for Full Paper Submission Extended to:</strong></td>
              <td>
                <s>22<sup>nd</sup> October 2024</s> 30<sup>th</sup> October 2024 (hard deadline)
              </td>
            </tr>
            <tr>
              <td><strong>Acceptance Notifications:</strong></td>
              <td>
                <s>15<sup>th</sup> November 2024</s> 20<sup>th</sup> November 2024
              </td>
            </tr>
            <tr>
              <td><strong>Camera Ready Paper Submission:</strong></td>
              <td>
                <s>30<sup>th</sup> November 2024</s> 5<sup>th</sup> December 2024
              </td>
            </tr>
          </tbody>
        </table>
>>>>>>> origin/main
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Side",
  data() {
    return {
<<<<<<< HEAD
      eventDate: new Date("2026-03-11T08:00:00"),
=======
      eventDate: new Date("2025-01-20T08:00:00"), 
>>>>>>> origin/main
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
<<<<<<< HEAD
=======

>>>>>>> origin/main
.time-block {
  text-align: center;
  margin: 0 10px;
}
<<<<<<< HEAD
=======

>>>>>>> origin/main
.time {
  font-size: 2rem;
  font-weight: bold;
  color: #d32f2f;
}
<<<<<<< HEAD
=======

>>>>>>> origin/main
p {
  margin: 0;
  font-size: 1rem;
  font-weight: bold;
}
<<<<<<< HEAD
ul.list-group {
  padding-left: 0;
}
=======

ul.list-group {
  padding-left: 0;
}

>>>>>>> origin/main
.list-group-item {
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  background-color: #fff;
}
<<<<<<< HEAD
.list-group-item:hover {
  background-color: rgb(184, 221, 248);
}
=======

.list-group-item:hover {
  background-color: rgb(184, 221, 248);
}

>>>>>>> origin/main
img {
  width: 100%;
  height: 100%;
}

li:hover {
  background-color: rgb(184, 221, 248);
}
<<<<<<< HEAD
.custom-font {
  font-family: Ubuntu, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
=======

.custom-font {
  font-family: Ubuntu, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}

>>>>>>> origin/main
.heading-font {
  font-family: Ubuntu, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-weight: bold;
}
<<<<<<< HEAD
=======

/* Custom Table Styling */
>>>>>>> origin/main
.custom-table {
  background-color: #f8f9fa;
  font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: 16px;
}
<<<<<<< HEAD
=======

>>>>>>> origin/main
.custom-table thead {
  background-color: #343a40;
  color: #ffffff;
}
<<<<<<< HEAD
=======

>>>>>>> origin/main
.custom-table th {
  text-align: center;
  padding: 10px;
}
<<<<<<< HEAD
=======

>>>>>>> origin/main
.custom-table td {
  padding: 10px;
  vertical-align: middle;
}
<<<<<<< HEAD
.custom-table td:first-child {
  font-weight: bold;
}
.custom-table tbody tr:nth-child(odd) {
  background-color: #f1f1f1;
}
.custom-table tbody tr:nth-child(even) {
  background-color: #ffffff;
}
.custom-table tbody tr:hover {
  background-color: #e9ecef;
}
=======

.custom-table td:first-child {
  font-weight: bold;
}

.custom-table tbody tr:nth-child(odd) {
  background-color: #f1f1f1;
}

.custom-table tbody tr:nth-child(even) {
  background-color: #ffffff;
}

.custom-table tbody tr:hover {
  background-color: #e9ecef;
}

>>>>>>> origin/main
</style>



