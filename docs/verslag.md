# Titel verslag

Versienummer : 1

Auteur : Bram Hooiveld

Studentnummer : 0266808

Klas : 24SDB

Naam Keuzedeel: Verdieping Software

Code Keuzedeel:

Datum : 16-9-2026

---

<div style="page-break-after: always;"></div>

## Inhoudsopgave

- [Titel verslag](#titel-verslag)
    - [Inhoudsopgave](#inhoudsopgave)
    - [Inleiding](#inleiding)
    - [Maakt een keuze voor software](#maakt-een-keuze-voor-software)
        - [Ondezoek](#onderzoek)
        - [Vergelijking](#vergelijking)
        - [Keuze](#keuze)
        - [Arbeidsmarkt](#arbeidsmarkt)
        - [Onderbouwing onderzoek en keuze](#onderbouwing-onderzoek-en-keuze)
    - [Bronnen](#bronnen)

<div style="page-break-after: always;"></div>

## Inleiding

Op woensdag 16 september was het keuzedeel Verdieping Software begonnen. Hierbij moeten we de keuze maken waar wij ons in willen verdiepen voor de komende 20 weken of minder. Hierbij maak ik mijn keuze voor wat voor softwarepakket ik wil gebruiken. Ik kies dan drie uit de gekozen categorie en onderzoek deze. Na mijn onderzoek maak ik mijn definitieve keuze om mij in te verdiepen.

## Maakt een keuze voor software

Voor het keuzedeel wil ik mij verdiepen in Javascript. Niet alleen JS maar een JS library met een focus op het animeren van elementen op de website.

### Onderzoek

Voor het onderzoek heb ik drie libraries gevonden. Voor elke library bekijk ik de websites waar ze zijn gebruikt en de documentatie en demos als die er zijn. Ik ga niet zoeken naar vacatures voor elke library want het is te moeilijk omdat er geen specifieke vraag is naar een library.

de libraries die ik heb gekozen om te onderzoeken zijn:

- Gsap
- Anime.js
- Motion.dev (Had eerst de naam van Framer.js)

### [Gsap](https://gsap.com/)

Gsap is één van of wel de meest populaire Javascript animation library. gebruikt door [YouTube](https://www.youtube.com/), [Netlify](https://www.netlify.com/) en [EA](https://www.ea.com/) en meer [^6].

Het opstarten van Gsap

Gsap heeft drie manieren om het te importeren voor jouw project.

- Een npm of yarn commando
- Een cdn link

Ook kan je een lijst aan functionaliteiten invullen om een automatische lijst van imports te krijgen [^6].

```JS
gsap.to(".box", { x: 200 })
```

Om een box te animeren moeten met het object gsap.methode() en dan tussen Aanhalingstekens met de juiste class of id van het HTML object. Het volgende daarna tussen {} is voor wat we ermee willen doen. In dit voorbeeld beweegt het block 200px op de x as.

### [Anime.js](https://animejs.com/)

Anime.js is net zoals Gsap een Javascript animation library. Animejs kan gebruikt worden same met Javascript en react en is gebruikt voor [Monkeytype](https://monkeytype.com/) en ook reclames op [TikTok](https://ads.tiktok.com/business/en?tt4b_lang_redirect=1). Ook wordt het gebruikt door [Riverside](https://riverside.com/) [^9].

Het opstarten van Anime.js

- With npm
- With a cdn
- A direct download from the repo

Anime.js heeft ook een uitgebreide documentatie dat over alle mogelijke dingen die je het kan voor gebruiken [^7].

### [Motion.dev](https://motion.dev/)

Motion.dev is een flexibele JS library je kan het gebruiken met JS, React, Vue, Three.js en Webgpu. Het heeft ook developer tools zoals een Ai Kit, CSS studio en MotionScore [^5]. Motion.dev heeft veel partners [^8] zoals [Figma](https://www.figma.com/), [Linear](https://linear.app/) en [Sanity](https://www.sanity.io/).

Het opstarten van Motion.dev

- met een package manager npm of yarn
- met een script tag in de html

Het gebruiken van Motion [^5]
import de animatie functie

```JS
import { animate } from "motion"
```

gebruik animate() gebruik dan een css selector of de element direct.

```JS
// CSS selector
animate(".box", { rotate: 360 })

// Elements
const boxes = document.querySelectorAll(".box")

animate(boxes, { rotate: 360 })
```

### Vergelijking

|                       | Anime js | Gsap |  Motion.dev |
| :-------------- | :--------------: | :-----------: | :---------: |
| **Prestatie**  | Lichtgewicht en presterend voor meer webanimaties zonder plugins [^1]| Goede prestaties voor wat grotere en complexe animaties [^10]| Gemaakt voor moderne en vloeiende animaties in de browser [^5]  |
| **Functies** | Geeft de gebruiker de mogelijkheid om CSS, versleepbare elementen, SVG, scrollobservatie en Staggering. Je kan JavaScript en ook React ervoor gebruiken [^7].  | Gsap geeft de meeste mogelijkheden om het te gebruiken samen met vanilla JS, maar ook: React, Svelte, Vue en meer, zoals WebGL, Three.js en Webflow [^6].| Motion.dev heeft een uitgebreide documentatie en frameworks die er ook mee gebruikt kunnen worden. die zijn React en Vue. Samen met vanilla JavaScript [^5] |
| **Gemak van gebruik** | Anime.js heeft een concentratie op een flexibele JavaScript-library om animaties te maken op het web. Je kan met npm of cdn het in een project gebruiken [^7]. | Gsap heeft een uitgebreide "Install helper" waar de makkelijk het can downloaden met npm, yarn of een CDN gebruiken. Ook kan je kiezen welke plugins en extra toevoegingen makkelijk aanvinken om de imports ervan te krijgen [^6]. | Redelijk gemakkelijk en goed met React. Het is te installeren met een npm-import of met een scripttag [^5].                         |
| **Grootte**           |  Anime.js heeft veel kleine bestanden waarvan veel onder de 10 kilobytes zijn [^7], omdat het alleen importeert wat je nodig hebt                |  Het is groter dan andere, zeker met de extra plugins |  Het is flexibel, je hoeft alleen te importeren wat nodig is voor jouw project [^5]. |
| **Ecosysteem**        | goede documentatie en gemeenschap, maar kleiner dan de grotere animation libraries [^7] [^4]  |   Gsap heeft een heel groot systeem van gebruikers en wordt door veel bedrijven gebruikt [^2] [^3] [^6] | Het is een bekende library met een gedetailleerde documentatie voor Javascript, React en Vue. En is het door bekende bedrijven gebruikt [^8] [^5].  |

### Keuze

Voor mijn keuze uit de drie Javascript libraries kies ik Gsap. Kies ik voor GSAP.

### Arbeidsmarkt

Binnen de arbeidsmarkt is geen specifieke vraag naar een bepaalde JS library, maar meer een vraag naar UI/UX designers en front-end developers die een framework zoals React of Vue kennen. De meeste, misschien alle vragen voor een front-end developer met React skills. Gsap zou mij hier in kunnen helpen omdat ik met de modules all React ga leren. Kan ik mij nieuwe kennis snel gebruiken samen met de library.

### Onderbouwing onderzoek en keuze

Ik maak mijn uiteindelijke kueze voor GSAP, Omdat het de meeste flexibiliteit aan mij kan geven en het ook gemaakt is om wat grotere animaties en complexere te maken [^6]. De editie van het aantal front-endframeworks, zoals Svelte en React, die ik ook ermee kan gebruiken. Heeft het zeker een populaire keuze gemaakt voor veel bedrijven [^6]. Samen met de simpele en uitgebreide "install helper" wordt het makkelijk om een nieuw project te starten [^6].

---

## Maakt zich de software eigen

### Reflectie

Wat weet je al, wat weet je nog niet en wat wil je nog leren? Maak een overzicht van wat je al weet, wat je nog niet weet en wat je nog wilt leren. Zo krijg je inzicht in wat je al weet, en dus ook weet wat je nog niet weet. Neem de tijd om hierop te reflecteren.

### Leerdoelen formuleren

Maak een overzicht van je leerdoelen. Wat wil je leren en wat wil je bereiken? Formuleer je leerdoelen [SMART](https://www.uu.nl/sites/default/files/upper_leerdoelen_smart_opstellen.pdf).

### Prototype voorstel

Een duidelijk, uitgebreid prototypevoorstel wat past bij de gestelde leerdoelen.

### Planning

Maak een planning met een uitgewerkte tijdslijn van de te volgen stappen om je leerdoelen te behalen. Neem hierin ook de tijd op die je nodig hebt om je prototype te maken.

### Logboek

Hou een logboek bij van de tijd die je besteed aan het maken van je prototype. Noteer hierin ook de stappen die je hebt gezet om je leerdoelen te behalen.

## Prototype

Leg uit wat je prototype is en hoe je dit hebt gemaakt. Voeg ook een link naar je video van je prototype.

## Eindconclusie

Leerdoelen behaald? Wat heb je geleerd? Wat zou je een volgende keer anders doen? Wat zijn je vervolgstappen?

<div style="page-break-after: always;"></div>

## Bronnen

[^1]: [annnimate.com](https://annnimate.com/compare/best-animation-libraries) door Good Fella. "Best Animation Libraries", laatst gewijzegd 20 Julie, 2026.

[^2]: [wmtips.com](https://www.wmtips.com/technologies/javascript-libraries/filter/animation/). "Js libraries, most popular by 2026", de opgenomen data is laatst bijgewerkt op 28 September, 2026.

[^3]: [jstool.gitlab](https://jstool.gitlab.io/blog/posts/the-most-popular-javascript-libraries-in-2026/). "The Top 100 Open-Source JavaScript Libraries", geraadpleegd op 28 September, 2026.

[^4]: [bestofjs.com](https://bestofjs.org/projects?tags=animation). "Animation libraries". geraadpleegd op 28 September, 2026.

[^5]: [Motion.dev](https://motion.dev/). eerst genoemd as framer-motion. geraadpleegd 16 September 2026.

[^6]: [Gsap.com](https://gsap.com/). geraadpleegd 16 September 2026. Bijna onderaan de pagina boven de demos staan welke merken allemaal Gsap hebben gebruikt.

[^7]: [Anime.js](https://animejs.com/) geraadpleegd 16 September 2026.

[^8]: [Motion.dev partners](https://motion.dev/partners#partners). Dit zijn de partners/bedrijven waarmee motion.dev heeft gewerkt. geraadpleegd op 28 September, 2026.

[^9]: [wappalyzer](https://www.wappalyzer.com/technologies/javascript-graphics/anime-js/). "websites using anime.js". geraadpleegd 30 September 2026. Een lijst van websites die anime.js gebruiken

[^10] [annnimate.com](https://annnimate.com/compare/gsap-vs-anime-js). "comparison between Anime.js and GSAP". geraadpleegd 30 September 2026. vergelijkingen van GSAP en Anime.js

##
