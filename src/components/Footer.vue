
  <template>
  <!-- Footer -->
  <footer class="page-footer unique-color mt-3">
    <!-- Footer Links -->
    <div class="container-fluid">
      <div class="row py-5">
        <!-- About Us -->
        <div class="col-md-4 col-lg-4">
          <h5 class="white-text">About Us</h5>
          <p class="white-text">
            The ICPC²T conference is organized by NIT Raipur to bring together
            researchers, academics, and industry professionals to exchange
            knowledge and innovative ideas.
          </p>
        </div>

        <!-- Quick Links -->
        <div class="col-md-4 col-lg-4">
          <h5 class="white-text">Quick Links</h5>
          <ul class="list-unstyled">
            <li>
              <a class="white-text" href="#about">About Conference</a>
            </li>
            <li>
              <a class="white-text" href="#registration">Registration Details</a>
            </li>
            <li>
              <a class="white-text" href="#schedule">Conference Schedule</a>
            </li>
            <li>
              <a class="white-text" href="#contact">Contact Us</a>
            </li>
          </ul>
        </div>

        <!-- Contact Us -->
        <div class="col-md-4 col-lg-4">
          <h5 class="white-text">Contact Us</h5>
          <ul class="list-unstyled">
            <li>
              <i class="fas fa-envelope"></i>
              <a class="white-text ml-2" href="mailto:icpc2t@nitrr.ac.in">
                icpc2t@nitrr.ac.in
              </a>
            </li>
            <li>
              <i class="fas fa-phone"></i>
              <span class="white-text ml-2">+91 98765 43210</span>
            </li>
            <li>
              <i class="fas fa-map-marker-alt"></i>
              <span class="white-text ml-2">
                National Institute of Technology Raipur, G.E. Road, Raipur (C.G.)
              </span>
            </li>
          </ul>
        </div>
      </div>

      <hr />

      <!-- Social Media and Developers -->
      <div class="row py-3 d-flex align-items-center">
        <!-- Social Media -->
        <div class="col-md-6">
          <h6 class="white-text">Follow Us</h6>
          <a class="fb-ic">
            <i class="fab fa-facebook white-text mr-4"> </i>
          </a>
          <a class="tw-ic">
            <i class="fab fa-twitter white-text mr-4"> </i>
          </a>
          <a class="li-ic">
            <i class="fab fa-linkedin white-text mr-4"> </i>
          </a>
          <a class="ins-ic">
            <i class="fab fa-instagram white-text"> </i>
          </a>
        </div>

        <!-- Developers -->
        <div class="col-md-6 text-right">
          <p class="white-text">
            <strong>Developers</strong>: Dilpreet Kaur Bhatia and Ayush Pratap Singh
          </p>
        </div>
      </div>

      <hr />

      <!-- Copyright -->
      <div class="row">
        <div class="col text-center">
          <p class="white-text">
            © 2024 Copyright:
            <a href="http://nitrr.ac.in" target="_blank">
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
  background-color: #343a40;
  color: white;
  padding-top: 20px;
  padding-bottom: 20px;
}

a.white-text {
  color: #ffffff;
  text-decoration: none;
}

a.white-text:hover {
  color: #ffa726;
  text-decoration: underline;
}

.fab {
  font-size: 18px;
}

.fab:hover {
  color: #ffa726;
}

hr {
  border-top: 1px solid rgba(255, 255, 255, 0.2);
}
</style>
