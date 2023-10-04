<script lang="ts">
  
  let hamburgerActive = false;
  let navMenuActive = false;

  function toggleMenu() {
    hamburgerActive = !hamburgerActive;
    navMenuActive = !navMenuActive;
  }

  function closeMenu() {
    hamburgerActive = false;
    navMenuActive = false;
  }

  import chrzastkaImg from "./assets/chrastka.png";
import kosImg from "./assets/kosc.png";
import krewImg from "./assets/krew.png";
import biol1Img from "./assets/Biol-1.jpg";
import biol2Img from "./assets/Biol-2.jpg";
import biol3Img from "./assets/Biol-3.jpg";
import biol4Img from "./assets/Biol-4.jpg";
import biol5Img from "./assets/Biol-5.jpg";
import biol6Img from "./assets/Biol-6.jpg";
import biol7Img from "./assets/Biol-7.jpg";
import biol8Img from "./assets/Biol-8.jpg";

</script>

<header>
  <nav class="navBar">
    <h2 class="documentTitle">Biologia</h2>

    <ul class="navMenu" class:active={navMenuActive}>
      <li class="navItem">
        <a href="#one" class="navLink" on:click={closeMenu}>Tkanki</a>
      </li>
      <li class="navItem">
        <a href="#two" class="navLink">Tłuszczowa</a>
      </li>
      <li class="navItem">
        <a href="#three" class="navLink">Chrzęstna</a>
      </li>
      <li class="navItem">
        <a href="#four" class="navLink">Kostna</a>
      </li>
      <li class="navItem">
        <a href="#five" class="navLink">Krew</a>
      </li>
      <li class="navItem">
        <a href="#six" class="navLink">Łączna</a>
      </li>
      <li class="navItem">
        <a href="#seven" class="navLink">Homeostaza</a>
      </li>
      <li class="navItem">
        <a href="#eight" class="navLink">Zdjęcia</a>
      </li>
    </ul>

    <div class="hamburger" class:active={hamburgerActive} on:click={toggleMenu}>
      <span class="bar"></span>
      <span class="bar"></span>
      <span class="bar"></span>
    </div>
  </nav>
</header>

<main id="one" class="main section">
      <div class="readingSection section one">
        <h3 class="title">Tkanki</h3>
        <li>
          Tkanka - zbiór komórek o podanej budowie pełniących podobne funkcje w
          organizmie
        </li>
        <ul>
          Rodzaje Tkanek:
          <li>Mięśniowa</li>
          <li>Nabłonkowa</li>
          <li>Nerwowa</li>
          <li>Łączna</li>
        </ul>
        <ul>
          Tkanka łączna dzieli się na tkanki:
          <li>Tkanka łączna właściwa: tłuszczowa</li>
          <li>Tkanka łączna podporowa: kostna, chrzęstnta</li>
          <li>Tkanka łączna płynna: krew</li>
        </ul>
      </div>
      <div id="two" class="readingSection section">
        <h3 class="title">Tkanka tłuszczowa</h3>
        <li>
          Zółta - występuje u osobników dorosłych. Pełni funkcje amortyzującą,
          termoizolacyjną i magazynującą substancje zapasowe.
        </li>
        <li>
          Brunatna - występuje w okresie noworodkowym. Pełni funkcje
          termoregulacyjne.
        </li>
        <li>
          Tkankę tłuszczową posiada każdy, ponieważ to element występujący w
          podskórze.
        </li>
      </div>
      <div id="three" class="readingSection section">
        <h3 class="title">Tkanka chrzęstna</h3>
        <ul>
          Chechy tkanki chrzęstnej:
          <li>Sprężysta i elastyczna</li>
          <li>Odporna na urazy mechaniczne</li>
          <li>Rozciągliwa</li>
        </ul>
        <ul>
          Występuje w:
          <li>Powierzchnie stawowe kości</li>
          <li>Małżowina uszna</li>
          <li>Elementy krtani</li>
          <li>Łączy niektóre kości, np. żebra z mostkiem</li>
        </ul>
      </div>
      <div id="four" class="readingSection section">
        <h3 class="title">Tkanka kostna</h3>
        <li>Funkcja - tworzy kości</li>
        <ul>
          Cechy:
          <li>Twarda</li>
          <li>Mało elastyczna</li>
          <li>Sztywna</li>
        </ul>
      </div>
      <div id="five" class="readingSection section">
        <h3 class="title">Krew</h3>
        <ul>
          Funkcje:
          <li>
            Tkanka transportująca: tlen, CO2, mikro i makroelementy, białka,
            cukry, tłuszcze, kwasy nukleinowe
          </li>
          <li>Ochrona organizmu przed drobnoustrojami</li>
        </ul>
      </div>
      <div id="six" class="readingSection section">
        <h3 class="title">Tkanka łączna</h3>
        <li>
          Tkanka zbudowana z substancji międzykomórkowej oraz komórek, które są
          w tej substancji zanurzone
        </li>
      </div>
      <div id="seven" class="readingSection section">
        <h3 class="title">Homeostaza</h3>
        <li>Jest to stan równowagi organizmu</li>
        <ul>
          Homeostaza:
          <li>Temperatura 35-37</li>
          <li>Ciśnienie 120/80 mmHg</li>
          <li>Poziom tlenu i dwutlenku węgla</li>
          <li>Ph krwi - kwasowość środowiskowa</li>
          <li>Poziom cukru -> glukoza 70-140 mg/na 1L krwi</li>
          <li>H2O nawodnienie komórek</li>
          <li>Składniki mineralne - mikro i makro elementy</li>
          <li>Żelazo</li>
        </ul>
        <ul>
          Zaburzenia homeostazy:
          <li>Choroby</li>
          <li>Stres</li>
          <li>Brak snu</li>
          <li>Warunki atmosferyczne</li>
          <li>Zła dieta</li>
          <li>Alkochol</li>
          <li>Używki</li>
          <li>Papierosy</li>
          <li>Brak ruchu</li>
        </ul>
      </div>
      <div id="eight" class="readingSection section">
    <h3 class="title">Zdjęcia</h3>
    <img src={chrzastkaImg} alt="chrząstka" class="picture" />
    <img src={kosImg} alt="kość" class="picture" />
    <img src={krewImg} alt="krew zdjecie" class="picture" />
    <img src={biol1Img} alt="b1" class="picture" />
    <img src={biol2Img} alt="b2" class="picture" />
    <img src={biol3Img} alt="b3" class="picture" />
    <img src={biol4Img} alt="b4" class="picture" />
    <img src={biol5Img} alt="b5" class="picture" />
    <img src={biol6Img} alt="b6" class="picture" />
    <img src={biol7Img} alt="b7" class="picture" />
    <img src={biol8Img} alt="b8" class="picture" />
</div>

    </main>
