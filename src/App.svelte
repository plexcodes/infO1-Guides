<script>
import { fade,fly,slide } from 'svelte/transition';
import { onMount } from 'svelte';
let ready = false;
onMount(() => (ready = true));
</script>
<html lang="en">
  <head>
    <title>infO(1)Guides</title>
    <meta property="og:title" content="infO(1)Guides" />
    <meta property="twitter:card" content="summary_large_image" />
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta charset="utf-8" />
    <meta property="twitter:card" content="summary_large_image" />
    <style data-tag="reset-style-sheet">
      html {  line-height: 1.15;}body {  margin: 0;}* {  box-sizing: border-box;  border-width: 0;  border-style: solid;}p,li,ul,pre,div,h1,h2,h3,h4,h5,h6 {  margin: 0;  padding: 0;}button,input,optgroup,select,textarea {  font-family: inherit;  font-size: 100%;  line-height: 1.15;  margin: 0;}button,select {  text-transform: none;}button,[type="button"],[type="reset"],[type="submit"] {  -webkit-appearance: button;}button::-moz-focus-inner,[type="button"]::-moz-focus-inner,[type="reset"]::-moz-focus-inner,[type="submit"]::-moz-focus-inner {  border-style: none;  padding: 0;}button:-moz-focus,[type="button"]:-moz-focus,[type="reset"]:-moz-focus,[type="submit"]:-moz-focus {  outline: 1px dotted ButtonText;}a {  color: inherit;  text-decoration: inherit;}input {  padding: 2px 4px;}img {  display: block;}html { scroll-behavior: smooth  }
    </style>
    <style data-tag="default-style-sheet">
      html {
        font-family: League Spartan;
        font-size: 40px;
      }

      body {
        font-weight: 400;
        font-style:normal;
        text-decoration: none;
        text-transform: none;
        letter-spacing: normal;
        line-height: 1.55;
        color: var(--dl-color-gray-900);
        background-color: var(--dl-color-gray-white);

      }
    </style>
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Nanum+Pen+Script:wght@400&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@100;200;300;400;500;600;700;800;900&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;600;700;800;900&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Oxygen:wght@300;400;700&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono:wght@400&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@0,300;0,400;0,700;0,900;1,300;1,400;1,700;1,900&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Spectral:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap"
      data-tag="font"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div>
      <link href="acasa.css" rel="stylesheet" />

      <div class="acasa-container">
        {#if ready}
        <div data-role="Header" class="acasa-header" in:fade="{{ duration: 1000 }}">
          <header class="acasa-header1">
            <div class="acasa-logo">
              <a href="index.html" class="acasa-navlink">
                <!-- svelte-ignore a11y-img-redundant-alt -->
                <img
                  alt="image"
                  src="playground_assets/info%5B1%5Dguides%20%5B1%5D-200h.png"
                  class="acasa-image"
                />
              </a>
            </div>
          </header>
        </div>{/if}
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <div class="acasa-main">
          <div class="acasa-blur-background"></div>
          <div class="acasa-hero">
            <div class="acasa-container1">
              {#if ready}
              <h1 class="acasa-text" in:fly="{{ y: -200, duration: 2000 }}">
                <span>Librăria virtuală de ghiduri</span>
                <br />
                <span>pentru FTC și programare.</span>
                <br />
              </h1>{/if}
              {#if ready}
              <div class="acasa-container2" in:fly="{{ y: 200, duration: 2000 }}">
                <a href="#ghiduri" class="acasa-link">
                  <div
                    class="primary-button-container primary-button-root-class-name"
                  >
                    <button class="primary-button-button mediumLabel button">
                      <span>Ghiduri</span>
                    </button>
                  </div>
                </a>
                <a href="#proiecte" class="acasa-link1">
                  <div
                    class="primary-button-container primary-button-root-class-name1"
                  >
                    <button class="primary-button-button mediumLabel button">
                      <span>Colaborează cu Noi!</span>
                    </button>
                  </div>
                </a>
              </div>{/if}
            </div>
          </div>
          <!-- svelte-ignore a11y-img-redundant-alt -->
          <img
            alt="image"
            src="playground_assets/turquoise-circle.svg"
            class="acasa-turquoise-cirble"
          />
          <!-- svelte-ignore a11y-img-redundant-alt -->
          <img
            alt="image"
            src="playground_assets/4-updated.svg"
            class="acasa-purple-circle"
          />
          <img
            alt="image"
            src="playground_assets/all-green-final-left.svg"
            class="acasa-left"
          />
          <img
            alt="image"
            src="playground_assets/all-green-final-right.svg"
            class="acasa-right"
          />
        </div>
        <div class="acasa-feature1">
          <div class="acasa-container3">
            <span class="acasa-text05">Învață de la cei mai buni!</span>
            <span class="acasa-text06">
              <span>Librăria virtuală inf<b>O(1)</b>Guides 
                conține cele mai cuprinzătoare ghiduri scrise pentru
                programul de robotică First Tech Challenge și programare,
                destinate elevilor de liceu.
              </span>
            </span>
          </div>
          <!-- svelte-ignore a11y-img-redundant-alt -->
          <img
            src="playground_assets/logo-400w.png"
            alt="image"
            class="acasa-image1"
          />
        </div>
        <div class="acasa-container4">
          <div class="acasa-feature2">
            <div class="acasa-container5">
              <h2 id="ghiduri" class="acasa-text10">Ghiduri Disponibile</h2>
            </div>
          </div>
          <a
            href="https://gm0.org/ro/latest/"
            target="_blank"
            rel="noreferrer noopener"
            class="acasa-link2"
          >
            <div class="acasa-feature-card">
              <!-- svelte-ignore a11y-img-redundant-alt -->
              <img
                alt="image"
                src="playground_assets/gm0-logo-200h.png"
                class="acasa-image2"
              />
              <span class="acasa-text11">
                <span>Ultima Actualizare: 29/1/2023</span>
                <br />
              </span>
              <h2 class="acasa-text14">Game Manual 0</h2>
              <span class="acasa-text15">
                <span>
                  &quot;Game Manual 0&quot; este cel mai vast ghid existent
                  pentru programul First Tech Challenge, la care au contribuit
                  peste 30 de membri și alumni ale celor mai de succes echipe
                  FTC sau FRC din Statele Unite ale Americii și tradus în limba
                  română de echipa &quot;infO(1)Robotics&quot; și alți
                  colaboratori.
                </span>
                <br />
              </span>
            </div>
          </a>
        </div>
        <div class="acasa-container6">
          <div class="acasa-feature21">
            <div class="acasa-container7">
              <h2 id="proiecte" class="acasa-text18">
                Proiecte în Căutare de Colaboratori
              </h2>
            </div>
            <div class="acasa-feature-card1">
              <!-- svelte-ignore a11y-img-redundant-alt -->
              <img
                alt="image"
                src="playground_assets/gm0-logo-200h.png"
                class="acasa-image3"
              />
              <h2 class="acasa-text19">Game Manual 0</h2>
              <span class="acasa-text20">
                <span>
                  Proiectul &quot;Game Manual 0&quot; este în căutare de
                  colaboratori, fluenți în limba engleză, pentru traducerea si
                  verificarea articolelor. Pentru mai multe detalii puteți
                  consulta platforma
                </span>
                <a
                  href="https://www.transifex.com/gamemanual0/gm0/dashboard/"
                  target="_blank"
                  rel="noreferrer noopener"
                  class="acasa-link3"
                >
                  Transifex
                </a>
                <span>
                  atașată sau să mă contactați personal pe Discord (plex#4113)
                  sau
                </span>
                <a
                  href="https://www.facebook.com/whosplex"
                  target="_blank"
                  rel="noreferrer noopener"
                  class="acasa-link4"
                >
                  Facebook
                </a>
                <span>.</span>
                <br />
              </span>
              <span class="acasa-text25">
                <span>Procentaj Tradus: 41.74%</span>
                <br />
              </span>
            </div>
          </div>
        </div>
        <div class="acasa-footer">
          <footer class="acasa-container8">
            <a href="index.html" class="acasa-navlink1">
              <!-- svelte-ignore a11y-img-redundant-alt -->
              <img
                alt="image"
                src="playground_assets/2-200h.png"
                class="acasa-image4"
              />
            </a>
            <div class="acasa-divider"></div>
            <span class="acasa-text28">
              <span class="acasa-text29">
                FTC Team 15993 &quot;infO(1)Robotics&quot; - made with swag by
                plex
              </span>
              <br />
            </span>
          </footer>
        </div>
      </div>
    </div>
    <script src="https://unpkg.com/@teleporthq/teleport-custom-scripts"></script>
  </body>
</html>
