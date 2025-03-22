<template>
  <div>
    <img class="logo" src="./assets/logo.webp" alt="Salford Lib Dems logo" />
    <h1 class="tag">Salford Liberal Democrats</h1>
    <h5 class="GI2">Promoted by the Salford Lib Dems,</h5>
    <h5 class="GI2">Unit 2, 07 Boat Shed, 16 Exchange Quay, Salford M5 3EQ</h5>
    <div class="max580">
      <h4 class="GI">Get involved</h4>
      <!-- Loop through links to generate the anchor tags -->
      <a
        v-for="link in links"
        :key="link.text"
        :href="link.href"
        target="_blank"
        class="link1"
      >
        <div class="link-content">
          <!-- Use both the common logo styles and the specific logo mask -->
          <div :class="['link-logo', link.logoClass]"></div>
          <p>{{ link.text }}</p>
        </div>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      links: [
        { text: "Facebook", href: "https://www.facebook.com/SalfordLiberalDemocrats", logoClass: "logo4" },
        { text: "Instagram", href: "https://www.instagram.com/salfordquayslibdems/", logoClass: "logo4" },
        { text: "Twitter", href: "https://x.com/salfordlibdems", logoClass: "logo4" },
        { text: "Our Website", href: "https://www.salfordlibdems.uk", logoClass: "logo2" },
        { text: "Apply for a Postal Vote", href: "https://www.gov.uk/apply-postal-vote", logoClass: "logo2" },
        { text: "CleanUp Salford Quays", href: "https://www.cleanupuk.org.uk/groups/cleanupthequays", logoClass: "logo6" },
        { text: "Facebook - CleanUp Salford Quays", href: "https://www.facebook.com/groups/1406669859992678", logoClass: "logo6" },
        { text: "Donate", href: "https://libdems.my.salesforce-sites.com/DonationPage/donation/2221-donate", logoClass: "logo1" },
        { text: "Join the Liberal Democrats", href: "https://libdems.my.salesforce-sites.com/LiberalDemocrats/NewMemberLocal", logoClass: "logo3" },
        { text: "Our Campaigns", href: "https://www.salfordlibdems.uk/campaigns", logoClass: "logo6" }
      ]
    };
  }
};
</script>

<style>
/* Import the Inter font from Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');

body {
  background-color: #2A3235;
  font-family: 'Inter', sans-serif;
  margin-bottom: 40px;
}

.logo {
  border-radius: 50%;
  width: 96px;
  height: 96px;
  object-fit: contain;
  display: block;
  margin: 40px auto 0;
}

.tag {
  margin-top: 20px;
  color: #fff;
  font-weight: 700;
  font-size: 20px;
  text-align: center;
  overflow: hidden;
}

.GI,
.GI2 {
  text-align: center;
  color: #fff;
  margin: 0;
  font-family: 'Inter', sans-serif;
}

.GI {
  margin-top: 50px;
}

.GI2 {
  font-weight: 400;
  margin-bottom: 5px;
}

.max580 {
  max-width: 580px;
  margin: 0 auto;
}

.link1 p {
    margin: 0 56px;
}

.link1 {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 15px auto 0;
  min-height: 55px;
  padding: 0;
  background-color: #fff;
  color: #2A3235;
  border-radius: 14px;
  text-decoration: none;
  transition: transform 0.15s cubic-bezier(0, 0.2, 0.5, 3);
}

.link1:hover {
  transform: scale(1.02);
}

.link-content {
  position: relative;
  width: 100%;
  text-align: center;
}

/* Common styles for logo elements used inside links */
.link-logo {
  position: absolute;
  top: 50%;
  left: 8px;
  width: 48px;
  height: 48px;
  transform: translateY(-50%);
  pointer-events: none;
  background-color: currentColor;
  border-radius: 12px;
  mask-size: 100%;
}

/* Specific logo mask images */
.logo1 { mask-image: url("/currency-pound.svg"); }
.logo2 { mask-image: url("/id.svg"); }
.logo3 { mask-image: url("/license.svg"); }
.logo4 { mask-image: url("/user.svg"); }
.logo5 { mask-image: url("/wave-triangle.svg"); }
.logo6 { mask-image: url("/zodiac-aquarius.svg"); }
</style>