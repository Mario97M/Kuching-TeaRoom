<script>
export default {
  name: "Home"
};
</script>

<template>
  <body>
    <header>
      <nav>
        <div class="nav-brand">
          <span>
            <font-awesome-icon
              icon="fa-solid fa-mug-hot"
              style="color: #be1c2d; height: 7em"
            />
          </span>
          <span class="brand"
            >Kuching <br />
            TeaRoom</span
          >
        </div>
        <div>
          <ul>
            <li>Home</li>
            <li>Online Order</li>
            <li>Contact Us</li>
          </ul>
        </div>
      </nav>
    </header>
    <div class="home-background-image">
      <div>
        <h1>A TASTE OF MALAYSIA</h1>
        <p>
          Come enjoy our authentic Ipoh-style Malaysian cuisine. Experience
          recipes passed down for generations and made from imported ingredients
          straight from Malaysia!
        </p>
        <a href="#"><button>Contact Us</button></a>
      </div>
    </div>
    <main>
      <!-- Article -->

      <div class="home-article-background-pattern">
        <div class="article-container">
          <article>
            <span>A LITTLE ABOUT</span><br />
            <span class="underline-one"></span>
            <div>
              <h2>古晉茶室</h2>
              <h3>KUCHING TEAROOM</h3>
            </div>
            <p>
              With a Kopitiam (“Cafe”) in the region surrounding Ipoh, a major
              culinary hub of Malaysia, our family have developed a deep
              connection with authentic Malaysian cuisine for close to a century.
              With traditional family recipes passed down through generations, our
              passion for authentic Ipoh-style Malaysian food has brought us to
              this little corner of San Gabriel Valley, a culinary hub of Asian
              cuisine, to share with our community. Our goal is to bring the true
              flavors of Malaysia to this side of the Pacific and expose a new
              population to real Malaysian cuisine. We even import our ingredients
              direct from Malaysia to preserve the authentic aromas and strong
              rich flavors that only the herbs and spices cultivated in the
              climates of Southeast Asia can bring. Stop by our little shop in
              Alhambra and experience a true taste of Malaysia.
            </p>
            <button>Order Online</button>
          </article>
        </div>
      </div>

      <!-- Business hours -->

      <div class="business-hours-section">
        <div>
          <span>OUR TIMINGS</span><br />
          <span class="underline-two"></span>
          <h1>Business Hours</h1>
        </div>
        <div class="business-hours">
          <div class="days-hours">
            <div class="day">Mon</div>
            <div class="hours">9:00 AM - 8:30 PM</div>
          </div>
          <div class="days-hours">
            <div class="day">Tue</div>
            <div class="hours">9:00 AM - 2:30 PM</div>
          </div>
          <div class="days-hours">
            <div class="day">Wed</div>
            <div class="hours">Close</div>
          </div>
          <div class="days-hours">
            <div class="day">Thurs</div>
            <div class="hours">9:00 AM - 8:30 PM</div>
          </div>
          <div class="days-hours">
            <div class="day">Fri</div>
            <div class="hours">9:00 AM - 8:30 PM</div>
          </div>
          <div class="days-hours">
            <div class="day">Sat</div>
            <div class="hours">9:00 AM - 8:30 PM</div>
          </div>
          <div class="days-hours">
            <div class="day">Sun</div>
            <div class="hours">9:00 AM - 8:30 PM</div>
          </div>
        </div>
      </div>
      <div class="gallery-container">
        <h1>Our Gallery</h1>
        <div class="gallery">
          <div>
            <img src="./images/home-image-one.jpg" alt="Gallery Image" />
          </div>
          <div>
            <img src="./images/home-image-two.jpg" alt="Gallery Image" />
          </div>
          <div>
            <img src="./images/home-image-three.jpg" alt="Gallery Image" />
          </div>
          <div>
            <img src="./images/home-image-four.jpg" alt="Gallery Image" />
          </div>
          <div>
            <img src="./images/home-image-five.jpg" alt="Gallery Image" />
          </div>
          <div>
            <img src="./images/home-image-six.jpg" alt="Gallery Image" />
          </div>
        </div>
      </div>
    </main>
    <footer>
      <span>Kuching-TeaRoom all rights reserved.</span>
    </footer>
  </body>
</template>

<style scoped>
html,
body {
  font-family: "Montserrat", sans-serif;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0 5em 0 5em;
}

nav ul {
  display: flex;
  list-style-type: none;
  gap: 2em;
}

nav ul li {
  cursor: pointer;
}

nav span {
  margin-right: 1em;
}

.nav-brand {
  display: flex;
  align-items: center;
}
.brand {
  font-family: "Gluten", cursive;
  font-size: 3rem;
  font-weight: 900;
  color: #f2b69f;
  text-shadow: 2px 2px #73261b;
}

.home-background-image div {
  max-width: 40em;
  margin-left: 10%;
}

.home-background-image h1 {
  font-weight: 900;
  font-size: 4.5rem;
}

.home-background-image div {
  position: relative;
  top: 4em;
}

.home-background-image p {
  font-weight: 600;
  font-size: 1.6rem;
  line-height: 50px;
}

.home-background-image button {
  background-color: white;
  border: none;
  border-radius: 10px;
  padding: 0.8em 1.5em;
  color: #ea7142;
  font-family: "Playfair Display", serif;
  font-weight: 600;
  font-size: 1.2rem;
  cursor: pointer;
}

.home-background-image {
  background-image: url("./images/home-background-image.jpg");
  background-color: #9d9d9d;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  height: 80vh;
  margin: 0;
  color: white;
}

article {
  width: 30em;
}

article span {
  color: #ebb408;
}

article .underline-one {
  display: inline-block;
  border-bottom: 2px solid #ebb408;
  width: 3em;
  margin-top: 1em;
}

article h2 {
  color: #be1c2d;
  font-size: 4.5rem;
  text-shadow: 0px 0px 0px #73261b, 4px 4px 0px #73261b;
  margin-bottom: 0;
}

article h3 {
  font-family: "Gluten", cursive;
  font-size: 2.5rem;
  font-weight: 900;
  color: #f2b69f;
  text-shadow: 2px 2px #73261b;
  margin-top: 0.5em;
}

article p {
  color: #ebb408;
  line-height: 30px;
  font-size: 1.2rem;
}

article div {
  text-align: center;
}

.article-container {
  width: 75%;
  margin: auto;
}

.home-article-background-pattern {
  background-image: url(./images/home-background-patter-leaves.webp);
  background-repeat: repeat;
  padding: 7em 0 2em 0;
}

article button {
  background-color: #ebb408;
  border: none;
  border-radius: 10px;
  padding: 0.8em 1.5em;
  color: black;
  font-family: "Playfair Display", serif;
  font-size: 1.2rem;
  font-weight: 600;
  cursor: pointer;
}

.business-hours-section {
  background-color: #2d2d2d;
  display: flex;
  justify-content: space-around;
  padding: 5em 5em 2em 5em;
  color: white;
  margin: 0 0 7em 0;
}

.business-hours-section h1 {
  font-size: 2.5em;
}

.business-hours-section span {
  color: #ebb408;
  font-size: 0.9rem;
}

.underline-two {
  display: inline-block;
  border: 2px solid #ebb408;
  width: 3em;
}

.business-hours-section table tr {
  background-color: black;
}

.business-hours {
  width: 25em;
  display: flex;
  flex-direction: column;
  gap: 3px;
}
.days-hours {
  display: flex;
  justify-content: space-between;
  background-color: black;
  padding: 10px 30px;
  border-radius: 10px 10px 0 0;
}

.gallery-container h1 {
  text-align: center;
  margin-bottom: 2em;
  font-size: 2.5rem;
  font-family: "Playfair Display", serif;
}

footer {
  background-color: #151515;
  color: white;
  padding: 20px 0;
  text-align: center;
}
</style>
