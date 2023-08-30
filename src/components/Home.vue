<script>
export default {
  name: "Home"
};
</script>

<template>
  <header>
    <nav>
      <div>
        <span>
          <font-awesome-icon
            icon="fa-solid fa-mug-hot"
            style="color: #be1c2d"
          />
        </span>
        <span>Kuching-TeaRoom</span>
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
    <h1>A TASTE OF MALAYSIA</h1>
    <p>
      Come enjoy our authentic Ipoh-style Malaysian cuisine. Experience recipes
      passed down for generations and made from imported ingredients straight
      from Malaysia!
    </p>
    <button>Contact Us</button>
  </div>
  <main>
    <article>
      <span>A LITTLE ABOUT</span>
      <span class="underline-one"></span>
      <h2>古晉茶室</h2>
      <h3>KUCHING-TEAROOM</h3>
      <p>
        With a Kopitiam (“Cafe”) in the region surrounding Ipoh, a major
        culinary hub of Malaysia, our family have developed a deep connection
        with authentic Malaysian cuisine for close to a century. With
        traditional family recipes passed down through generations, our passion
        for authentic Ipoh-style Malaysian food has brought us to this little
        corner of San Gabriel Valley, a culinary hub of Asian cuisine, to share
        with our community. Our goal is to bring the true flavors of Malaysia to
        this side of the Pacific and expose a new population to real Malaysian
        cuisine. We even import our ingredients direct from Malaysia to preserve
        the authentic aromas and strong rich flavors that only the herbs and
        spices cultivated in the climates of Southeast Asia can bring. Stop by
        our little shop in Alhambra and experience a true taste of Malaysia.
      </p>
      <button>Order Online</button>
    </article>
    <div class="business-hours-section">
      <div>
        <span>OUR TIMINGS</span>
        <span class="underline-two"></span>
        <h1>Business Hours</h1>
      </div>
      <div>
        <table>
          <tr>
            <td>Mon</td>
            <td>9:00 AM - 8:30 PM</td>
          </tr>
          <tr>
            <td>Tue</td>
            <td>9:00 AM - 2:30 PM</td>
          </tr>
          <tr>
            <td>Wed</td>
            <td>Close</td>
          </tr>
          <tr>
            <td>Thur</td>
            <td>9:00 AM - 8:30 PM</td>
          </tr>
          <tr>
            <td>Fri</td>
            <td>9:00 AM - 8:30 PM</td>
          </tr>
          <tr>
            <td>Sat</td>
            <td>9:00 AM - 8:30 PM</td>
          </tr>
          <tr>
            <td>Sun</td>
            <td>9:00 AM - 8:30 PM</td>
          </tr>
        </table>
      </div>
    </div>
    <div class="gallery-container">
      <h1>Our Gallery</h1>
      <div class="gallery">
        <div><img src="./images/home-image-one.jpg" alt="Gallery Image" /></div>
        <div><img src="./images/home-image-two.jpg" alt="Gallery Image" /></div>
        <div>
          <img src="./images/home-image-three.jpg" alt="Gallery Image" />
        </div>
        <div>
          <img src="./images/home-image-four.jpg" alt="Gallery Image" />
        </div>
        <div>
          <img src="./images/home-image-five.jpg" alt="Gallery Image" />
        </div>
        <div><img src="./images/home-image-six.jpg" alt="Gallery Image" /></div>
      </div>
    </div>
  </main>
  <footer>
    <span>Kuching-TeaRoom all rights reserved.</span>
  </footer>
</template>

<style scoped>
div {
  /* font-family: 'Gluten', cursive; */
}
</style>
