---
ShowToc: false
ShowBreadcrumbs: false
hideMeta: true
ShowRssButtonInSectionTermList: false
layout: "single"
---

<div class="home-container">

  <!-- LEFT COLUMN -->
  <div class="home-left">
    <div class="home-logo-container">
      <img src="/images/logo.svg" class="home-logo" alt="Delft Mercurians Logo" />
    </div>
    <p class="home-tagline">
      We are the Delft Mercurians, a group of TU Delft students united in the goal of participating in the RoboCup Small Size League. Together we develop fully autonomous football robots from the ground up. These robots play 10 minute long 6 vs 6 football matches against teams from all over the world. We were founded in 2022 and have since competed in Eindhoven, The Netherlands (2024) and El-Salvador, Brazil (2025). <br>
We are currently busy with designing and manufacturing our next iteration of robots to compete at RoboCup 2026 in Seoul, South-Korea in July.
    </p>
    <div class="buttons">
      <a class="button button-home" href="about/" rel="noopener"><span>About</span></a>
      <a class="button button-home" href="publications/" rel="noopener"><span>Publications</span></a>
      <a class="button button-home accent" href="join/" rel="noopener"><span>Join the team</span></a>
      <a class="button button-home accent-blue" href="contact/" rel="noopener"><span>Contact</span></a>
    </div>
    <div class="home-spacer"></div>
    <div class="home-image-mobile">
      <img src="/images/background_field.jpeg" alt="Delft Mercurians robot" />
    </div>
    <p class="home-caption">Part of</p>
    <div class="home-sponsors">
      <a href="https://rsadelft.nl">
        <img src="/images/sponsors/rsa_logo.svg" alt="Robotics Student Association" class="rsa-logo" />
      </a>
    </div>
    <div class="home-spacer"></div>
    <p class="home-caption">Sponsors and partners</p>
    <div class="home-sponsors">
      <a href="https://tudelftroboticsinstitute.nl">
        <img src="/images/sponsors/dri_logo.svg" alt="TUDelft Robotics Institute" class="dri-logo" />
      </a>    
      <a href="https://bglobal.nl/">
        <img src="/images/sponsors/bglobal_logo.png" alt="bGlobal" />
      </a>
      <a href="https://nl.rs-online.com/web/">
        <img src="/images/sponsors/rs_logo.jpg" alt="RS Components" />
      </a>
      <a href="https://en.nanotec.com">
        <img src="/images/sponsors/nanotec_logo.svg" alt="Nanotec" />
      </a>
      <a href="https://www.tudelft.nl/me/over/afdelingen/cognitive-robotics-cor">
        <img src="/images/sponsors/CoR_text_large.png" alt="CoR" />
      </a>
      <a href="https://www.keulen.com/">
        <img src="/images/sponsors/vankeulen_logo.svg" alt="Van Keulen Interieurbouw" class="vk-logo" />
      </a>
      <a href="https://www.st.com/">
        <img src="/images/sponsors/st_logo.png" alt="ST Microelectronics" class="st-logo" />
      </a>
      <a href="https://va-imaging.com/">
        <img src="/images/sponsors/getcameras_logo.png" alt="VA Imaging" class="getcameras-logo" />
      </a>
      <a href="https://tinytronics.nl/">
        <img src="/images/sponsors/tinytronics_logo.png" alt="Tinytronics" />
      </a>
      <a href="https://robohouse.nl">
        <img src="/images/sponsors/robohouse_logo.png" alt="Robohouse" />
      </a>
    </div>
  </div>


  <!-- RIGHT IMAGE -->
  <div class="home-right">
    <img src="/images/background_field.jpeg" alt="Background field">
  </div>

</div>


<style>
/* Allow full width */
.main {
  max-width: 100% !important;
  padding: 0 !important;
}

.post-footer {
  display: none;
}

.nav .logo {
  visibility: hidden;
  max-width: 0px;
}

.home-container {
  display: flex;
  position: relative;
}

/* LEFT SIDE */
.home-left {
  width: 45%;
  padding: 6rem 4rem 4rem 4rem;
  display: block;
  text-align: left;
}

.home-left * {
  text-align: left;
}

.home-left > * {
  width: 100%;
  text-align: left;
  margin-left: 0;
  margin-right: 0;
}

.home-logo-container {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  align-items: center;
  justify-content: flex-start;
  max-width: 300px;
  margin-top: -100px;
}

.home-logo {
  display: block;
  margin: 0;
}

.home-tagline {
  margin-top: 1rem;
}

/* Horizontal buttons */
.buttons {
  margin-top: 2rem;
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  justify-content: flex-start;
  flex-wrap: wrap;
  min-width: 100%;
}

.button-home {
  padding: 8px 12px 8px 12px;
}

/* Sponsors */
.home-caption {
  margin-top: 4rem;
}


.home-spacer {
  height: 10px;
}

.home-sponsors {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  align-items: center;
  justify-content: flex-start;
}

.home-sponsors img {
  max-height: 50px;
}

.rsa-logo {
  min-height: 100px !important;
  max-height: 100px !important;
}

/* RIGHT IMAGE */
.home-right {
  position: fixed;
  right: 0;
  top: 0;
  width: 90vw;
  height: 100vh;
  z-index: -1;
  overflow: hidden;
}

@media (max-width: 2000px) {
  .home-right {
    width: 70vw !important;
  }
  .home-left {
    width: 60%;
  }
}

@media (max-width: 1500px) {
  .home-right {
    width: 50vw !important;
  }
  .home-left {
    width: 70%;
  }
}

.home-right img {
  width: 100%;
  height: calc(100% + 20px);
  margin-top: -10px;
  margin-bottom: -10px;
  object-fit: cover;

  /* Thin diagonal separator (~100px) */
  -webkit-mask-image: linear-gradient(
    100deg,
    transparent 0px,
    transparent calc(50% - 200px),
    black 50%
  );
  mask-image: linear-gradient(
    100deg,
    transparent 0px,
    transparent calc(50% - 200px),
    black 50%
  );
}

.home-image-mobile {
  display: none;
}

.home-image-mobile img {
  border-radius: 10px;
  max-height: 200px;
  width: 100%;
  object-fit: cover;
}

/* Dark mode sponsor overrides */
body.dark .dri-logo {
  content: url("/images/sponsors/dri_logo_dark.svg");
}
body.dark .st-logo {
  content: url("/images/sponsors/st_logo_dark.png");
}
body.dark .getcameras-logo {
  content: url("/images/sponsors/getcameras_logo_dark.png");
}
body.dark .vk-logo {
  content: url("/images/sponsors/vankeulen_logo_dark.svg")
}
body.dark .rsa-logo {
  content: url("/images/sponsors/rsa_logo_dark.svg")
}


body {
  background-image: url("/images/football_background.svg") !important;
}
body.dark {
  background-image: url("/images/football_background_dark.svg") !important;
}

@media (min-width: 900px) {
  body .nav a, body .nav svg {
    color: #dadadb !important;
  }
}

@media (max-width: 900px) {

  .home-container {
    flex-direction: column;
  }

  .home-left {
    width: 100%;
    padding: 3rem 2rem;
  }

  .home-right {
    display: none;
  }

  .home-image-mobile {
    display: block;
  }
}
</style>
