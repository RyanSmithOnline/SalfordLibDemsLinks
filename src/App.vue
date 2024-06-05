<template>
  <div>
    <img class="logo" src="./assets/logo.webp" alt="" />
    <h1 class="tag">Salford Liberal Democrats</h1>
    <h5 class="GI2" style="margin-bottom: 5px;">Promoted by the Salford Lib Dems,</h5>
    <h5 class="GI2">Unit 2, 07 Boat Shed, 16 Exchange Quay, Salford M5 3EQ</h5>
    <div class="max580">
      <h4 class="GI">Get involved</h4>
      <a href="https://www.facebook.com/SalfordLiberalDemocrats" target="_blank" class="link1" height="auto">
        <div class="">
          <div class="logo4"></div>
          <p class="">Facebook</p>
        </div>
      </a>
      <a href="https://x.com/salfordlibdems" target="_blank" class="link1" height="auto">
        <div class="">
          <div class="logo4"></div>
          <p class="">Twitter</p>
        </div>
      </a>
      <a href="https://www.salfordlibdems.uk" target="_blank" class="link1" height="auto">
        <div class="">
          <div class="logo2"></div>
          <p class="">Our Website</p>
        </div>
      </a>
      <a href="https://www.facebook.com/groups/1406669859992678" target="_blank" class="link1" height="auto">
        <div class="">
          <div class="logo6"></div>
          <p class="">Facebook - CleanUp Salford Quays</p>
        </div>
      </a>
      <a href="https://libdems.my.salesforce-sites.com/DonationPage/donation/2221-donate" target="_blank" class="link1"
        height="auto">
        <div class="">
          <div class="logo1"></div>
          <p class="">Donate</p>
        </div>
      </a>
      <a href="https://libdems.my.salesforce-sites.com/LiberalDemocrats/NewMemberLocal" target="_blank" class="link1"
        height="auto">
        <div class="">
          <div class="logo3"></div>
          <p class="">Join the Liberal Democrats</p>
        </div>
      </a>
      <a href="https://www.salfordlibdems.uk/campaigns" target="_blank" class="link1" height="auto">
        <div class="">
          <div class="logo6"></div>
          <p class="">Our Campaigns</p>
        </div>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>


<style>
body {
  background-color: #2A3235;
  font-family: Inter, sans-serif;
}

.link1:hover {
  transform: scale(1.02);
}

.logo1 {
  overflow-x: hidden;
  overflow-y: hidden;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  pointer-events: none;
  -webkit-box-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  align-items: center;
  background-color: currentcolor;
  mask-image: url("/currency-pound.svg");
  mask-size: 100%;
  left: 8px;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  border-bottom-right-radius: 12px;
  border-bottom-left-radius: 12px;
  width: 48px;
  height: 48px;
}

.logo2 {
  overflow-x: hidden;
  overflow-y: hidden;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  pointer-events: none;
  -webkit-box-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  align-items: center;
  background-color: currentcolor;
  mask-image: url("/id.svg");
  mask-size: 100%;
  left: 8px;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  border-bottom-right-radius: 12px;
  border-bottom-left-radius: 12px;
  width: 48px;
  height: 48px;
}

.logo3 {
  overflow-x: hidden;
  overflow-y: hidden;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  pointer-events: none;
  -webkit-box-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  align-items: center;
  background-color: currentcolor;
  mask-image: url("/license.svg");
  mask-size: 100%;
  left: 8px;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  border-bottom-right-radius: 12px;
  border-bottom-left-radius: 12px;
  width: 48px;
  height: 48px;
}

.logo4 {
  overflow-x: hidden;
  overflow-y: hidden;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  pointer-events: none;
  -webkit-box-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  align-items: center;
  background-color: currentcolor;
  mask-image: url("/user.svg");
  mask-size: 100%;
  left: 8px;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  border-bottom-right-radius: 12px;
  border-bottom-left-radius: 12px;
  width: 48px;
  height: 48px;
}

.logo5 {
  overflow-x: hidden;
  overflow-y: hidden;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  pointer-events: none;
  -webkit-box-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  align-items: center;
  background-color: currentcolor;
  mask-image: url("/wave-triangle.svg");
  mask-size: 100%;
  left: 8px;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  border-bottom-right-radius: 12px;
  border-bottom-left-radius: 12px;
  width: 48px;
  height: 48px;
}

.logo6 {
  overflow-x: hidden;
  overflow-y: hidden;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  pointer-events: none;
  -webkit-box-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  align-items: center;
  background-color: currentcolor;
  mask-image: url("/zodiac-aquarius.svg");
  mask-size: 100%;
  left: 8px;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  border-bottom-right-radius: 12px;
  border-bottom-left-radius: 12px;
  width: 48px;
  height: 48px;
}

.max580 {
  max-width: 580px;
  margin-right: auto;
  margin-left: auto;
}

.GI {
  font-family: Inter, sans-serif;
  text-align: center;
  color: rgb(255, 255, 255);
  margin-top:50px;
}

.GI2 {
  font-family: Inter, sans-serif;
  text-align: center;
  color: rgb(255, 255, 255);
  margin-top:0px;
  font-weight: 400;
}

.logo {
  border-top-left-radius: 50%;
  border-top-right-radius: 50%;
  border-bottom-right-radius: 50%;
  border-bottom-left-radius: 50%;
  width: 96px;
  height: 96px;
  display: block;
  object-fit: contain;
  object-position: initial;
  filter: none;
  margin-top: 72px;
  margin-right: auto;
  margin-left: auto;
}

.tag {
  margin-top: 20px;
  color: rgb(255, 255, 255);
  font-weight: 700;
  font-size: 20px;
  line-height: 1.5;
  text-overflow: ellipsis;
  max-width: 100%;
  white-space-collapse: collapse;
  overflow-x: hidden;
  overflow-y: hidden;
  font-family: Inter, sans-serif;
  text-align: center;
}

.link1 {
  margin-right:auto;
  margin-left:auto;
  width: calc(100% - 20px);
  transition-duration: 0.15s;
  transition-timing-function: cubic-bezier(0, 0.2, 0.5, 3);
  transition-delay: 0s;
  transition-behavior: normal;
  transition-property: transform;
  font-family: Inter, sans-serif;
  hyphens: auto;
  white-space-collapse: collapse;
  background-color: rgb(255, 255, 255);
  border-bottom-color: rgb(42, 50, 53);
  border-bottom-left-radius: 14px;
  border-bottom-right-radius: 14px;
  border-bottom-style: none;
  border-bottom-width: 0px;
  border-image-outset: 0;
  border-image-repeat: stretch;
  border-image-slice: 100%;
  border-image-source: none;
  border-image-width: 1;
  border-left-color: rgb(42, 50, 53);
  border-left-style: none;
  border-left-width: 0px;
  border-right-color: rgb(42, 50, 53);
  border-right-style: none;
  border-right-width: 0px;
  border-top-color: rgb(42, 50, 53);
  border-top-left-radius: 14px;
  border-top-right-radius: 14px;
  border-top-style: none;
  border-top-width: 0px;
  box-sizing: border-box;
  color: rgb(42, 50, 53);
  background-image: none;
  color: inherit;
  overflow-wrap: break-word;
  word-break: break-word;
  padding-left: 66px;
  padding-right: 66px;
  min-height: 64px;
  margin-top: 15px;
  border-top-style: none;
  border-right-style: none;
  border-bottom-style: none;
  border-left-style: none;
  font-family: inherit;
  font-weight: inherit;
  font-size: inherit;
  text-align: center;
  cursor: pointer;
  background-image: none;
  text-decoration-line: none;
  display: flex;
  -webkit-box-align: center;
  align-items: center;
  -webkit-box-pack: center;
  justify-content: center;
  height: auto;
  position: relative;
  appearance: none;
  box-sizing: border-box;
  vertical-align: middle;
  align-items: center;
  appearance: none;
  background-attachment: scroll;
  background-clip: border-box;
  background-image: none;
  background-origin: padding-box;
  background-position-x: 0%;
  background-position-y: 0%;
  background-repeat: repeat;
  background-size: auto;
  border-bottom-color: rgb(42, 50, 53);
  border-bottom-style: none;
  border-bottom-width: 0px;
  border-image-outset: 0;
  border-image-repeat: stretch;
  border-image-slice: 100%;
  border-image-source: none;
  border-image-width: 1;
  border-left-color: rgb(42, 50, 53);
  border-left-style: none;
  border-left-width: 0px;
  border-right-color: rgb(42, 50, 53);
  border-right-style: none;
  border-right-width: 0px;
  border-top-color: rgb(42, 50, 53);
  border-top-style: none;
  border-top-width: 0px;
  box-sizing: border-box;
  color: rgb(42, 50, 53);
  cursor: pointer;
}

/*cyrillic-ext*/
@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}

/*cyrillic-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}

/*cyrillic-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}

/*cyrillic-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}

/*cyrillic-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}
</style>
<style>
/*cyrillic-ext*/
@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}

/*cyrillic-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}

/*cyrillic-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}

/*cyrillic-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}

/*cyrillic-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2JL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0460-052F, U + 1C80-1C88, U + 20B4, U + 2DE0-2DFF, U + A640-A69F, U + FE2E-FE2F;
}

/*cyrillic*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa0ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0301, U + 0400-045F, U + 0490-0491, U + 04B0-04B1, U + 2116;
}

/*greek-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2ZL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 1F00-1FFF;
}

/*greek*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0370-03FF;
}

/*vietnamese*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa2pL7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0102-0103, U + 0110-0111, U + 0128-0129, U + 0168-0169, U + 01A0-01A1, U + 01AF-01B0, U + 0300-0301, U + 0303-0304, U + 0308-0309, U + 0323, U + 0329, U + 1EA0-1EF9, U + 20AB;
}

/*latin-ext*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa25L7W0Q5n-wU.woff2) format('woff2');
  unicode-range: U + 0100-02AF, U + 0304, U + 0308, U + 0329, U + 1E00-1E9F, U + 1EF2-1EFF, U + 2020, U + 20A0-20AB, U + 20AD-20CF, U + 2113, U + 2C60-2C7F, U + A720-A7FF;
}

/*latin*/

@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/inter/v13/UcC73FwrK3iLTeHuS_fvQtMwCp50KnMa1ZL7W0Q5nw.woff2) format('woff2');
  unicode-range: U + 0000-00FF, U + 0131, U + 0152-0153, U + 02BB-02BC, U + 02C6, U + 02DA, U + 02DC, U + 0304, U + 0308, U + 0329, U + 2000-206F, U + 2074, U + 20AC, U + 2122, U + 2191, U + 2193, U + 2212, U + 2215, U + FEFF, U + FFFD;
}
</style>