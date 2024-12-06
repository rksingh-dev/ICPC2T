<template>
  <!-- Footer -->
  <footer class="page-footer">
    <!-- Footer Links -->
    <div class="container-fluid">
      <div class="row py-2">
        <!-- About Us -->
        <div class="col-md-4 col-lg-4">
          <h5 class="black-text">About Us</h5>
          <p class="black-text">
            The ICPC²T conference is organized by NIT Raipur to bring together
            researchers, academics, and industry professionals to exchange
            knowledge and innovative ideas.
          </p>
        </div>

        <!-- Quick Links -->
        <div class="col-md-4 col-lg-4">
          <h5 class="black-text">Quick Links</h5>
          <ul class="list-unstyled">
            <li>
              <a class="black-text" href="brochure.pdf" target="_blank">Brochure</a>
            </li>
            <li>
              <a class="black-text" href="Home.vue" target="_blank">About Conference</a>
            </li>
            <li>
              <a class="black-text" href="router-link" target="_blank">Registration Details</a>
            </li>
            <li>
              <a class="black-text" href="#schedule">Conference Schedule</a>
            </li>
          </ul>
        </div>

        <!-- Contact Us -->
        <div class="col-md-4 col-lg-4">
          <h5 class="black-text">Contact Us</h5>
          <ul class="list-unstyled">
            <li>
              <i class="fas fa-envelope"></i>
              <a class="black-text ml-1" href="mailto:icpc2t@nitrr.ac.in">
                icpc2t@nitrr.ac.in
              </a>
            </li>
            <li>
              <i class="fas fa-phone"></i>
              <span class="black-text ml-1">+91 8225910484</span>
            </li>
            <li>
              <i class="fas fa-phone"></i>
              <span class="black-text ml-1">+91 9618832222</span>
            </li>
            <li>
              <i class="fas fa-phone"></i>
              <span class="black-text ml-1">+91 8109831322</span>
            </li>
            <li>
              <i class="fas fa-map-marker-alt"></i>
              <span class="black-text ml-1">
                National Institute of Technology Raipur, G.E. Road, Raipur (C.G.)
              </span>
            </li>
          </ul>
        </div>
      </div>

      <hr />

      <!-- Social Media and Developers -->
      <div class="row py-1 d-flex align-items-center">
        <!-- Social Media -->
        <div class="col-md-6">
          <h6 class="black-text">Follow Us</h6>
          <a class="fb-ic">
            <i class="fab fa-facebook black-text mr-3"> </i>
          </a>
          <a class="tw-ic">
            <i class="fab fa-twitter black-text mr-3"> </i>
          </a>
          <a class="li-ic">
            <i class="fab fa-linkedin black-text mr-3"> </i>
          </a>
          <a class="ins-ic">
            <i class="fab fa-instagram black-text" href="https://www.instagram.com/ieeenitrr/profilecard/?igsh=MWZ2cXh3OGhyMGRzMg==" target ="__blank"> </i>
          </a>
        </div>

        <!-- Developers -->
        <div class="col-md-6 text-right">
          <p class="black-text">
            <strong>Developers</strong>: Dilpreet Kaur Bhatia, Ayush Pratap Singh,Utkarsh Bharat and Tanya kumari
          </p>
        </div>
      </div>

      <hr />

      <!-- Copyright -->
      <div class="row">
        <div class="col text-center">
          <p class="black-text">
            © 2024 Copyright:
            <a href="http://nitrr.ac.in" target="_blank" class="black-text">
              National Institute of Technology Raipur
            </a>
          </p>
        </div>
      </div>
    </div>
  </footer>
  <!-- Footer -->
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.page-footer {
  background-color: rgb(135, 169, 242);
  color: black;
  padding-top: 8px;
  padding-bottom: 8px;
}

.row {
  margin-bottom: 6px;
}

a.black-text {
  color: black;
  text-decoration: none;
}

a.black-text:hover {
  color: #ffa726;
  text-decoration: underline;
}

.fab {
  font-size: 16px; /* Slightly larger icon size */
}

.fab:hover {
  color: #ffa726;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.2);
  margin-top: 6px;
  margin-bottom: 6px;
}

h5 {
  font-size: 16px; /* Increased heading size */
  margin-bottom: 6px;
}

ul li {
  margin-bottom: 4px;
  font-size: 14px; /* Larger list font size */
}

p {
  font-size: 14px; /* Larger paragraph font size */
  margin-bottom: 6px;
}
</style>

