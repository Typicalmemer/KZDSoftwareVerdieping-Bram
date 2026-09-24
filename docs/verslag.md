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

Op Woensdag 16 September was het keuzedeel Verdieping Software begonnen. Hierbij moeten we de keuze maken wat wij ons willen verdieping voor de komende 20 weken of minder.

## Maakt een keuze voor software

Voor het keuzedeel wil ik mij verdiepen in Javascript. Niet alleen JS maar een JS library met een focus op het animeren van elementen op de website.

### Onderzoek

Zoek minstens 3 voorbeelden van vacatures met softwarepakketten of 3 voorbeelden van bedrijven die bepaalde softwarepakketten gebruiken. Neem deze op in je verslag. Zorg dat je zowel een foto als link van elke vacature of website in je verslag zet.

Leg uit hoe je je onderzoek hebt gedaan.

Voor het onderzoek heb ik drie libraries gevonden. Voor elke library bekijk ik de websites waar ze zijn gebruikt en de documentatie en demos als die er zijn. Ik ga niet zoeken naar vacatures voor elke library want het is te moeilijk omdat een specifieke voor te krijgen vanwege hoeveel library's bestaan.

- Gsap 
- Anime.js
- Motion.js (Had eerst de naam van Framer.js) 

### *[Gsap](https://gsap.com/)*

Gsap is één van of wel de meest populaire Javascript animation library. gebruikt door [YouTube](https://www.youtube.com/), [Netlify](https://www.netlify.com/) en [EA](https://www.ea.com/) en meer. 

Het opstarten van Gsap 

Gsap heeft drie manieren om het te importeren voor jouw project. 
- Een npm commando 
- Een cdn link 
- Een yarn commando 

Ook kan je een lijst aan functionaliteiten invullen om een automatische lijst van imports te krijgen. 

```JS
gsap.to(".box", { x: 200 })
```

Om een box te animeren moeten met het object gsap() en dan tussen Aanhalingstekens met de juiste class of id van het HTML object. Het volgende daarna tussen {} is voor wat we ermee willen doen. In dit voorbeeld beweegt het block 200px op de x as.

### *[Anime.js](https://animejs.com/)*

Anime.js is net zoals Gsap een Javascript animation library. Animejs can gebruikt worden same met Javascript en react en is gebruikt voor [Monkeytype](https://monkeytype.com/) en ook reclames op [TikTok](https://ads.tiktok.com/business/en?tt4b_lang_redirect=1). Ook wordt het gebruikt door [Riverside](https://riverside.com/).

Het opstarten van Anime.js
- With npm 
- With a cdn
- A direct download from the repo

Anime.js heeft ook een uitgebreide documentatie dat over alle mogelijke dingen die je het kan voor gebruiken.


### *[Motion.dev](https://motion.dev/)*

Motion.dev is een flexibele JS library je kan het gebruiken met JS, React, Vue, Three.js en Vgpu. Het heeft ook developer tools zoals een Ai Kit, CSS studio en MotionScore. Motion.dev heeft veel geholpen met het creëren van ui bijvoorbeeld [Mlnk](https://mlnk.team/), [Sanda creates](https://sandracreates.com/) en [interstellar interiors](https://interstellarinteriors.com/).

Het opstarten van Motion.dev  
- met een package manager npm of yarn
- met een script tag in de html

Het gebruiken van Motion
import de animatie functie
```BASH
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

Vergelijk de pakketten op tenminste 5 punten

| | Anime.js | Gsap | Motion.dev | 
|:----------|:------:|:------------:|:------:|
| **Prestatie** | Lichtgewicht en presterend voor meer webanimaties zonder plugins  | Goede prestaties voor wat grotere en complexe animaties | Gemaakt voor moderne en vloeiende animaties in de browser |
| **Functies** | Geeft de gebruiker de mogelijkheid om CSS, versleepbare elementen, SVG, scrollobservatie en Staggering. Je kan JavaScript en ook React ervoor gebruiken.  | Gsap geeft de meeste mogelijkheden om het te gebruiken samen met vanilla JS, maar ook: React, Svelte, Vue en meer, zoals WebGL, Three.js en Webflow  | Motion.dev heeft een uitgebreide documentatie en frameworks die er ook mee gebruikt kunnen worden. die zijn React en Vue. Samen met vanilla JavaScript |
| **Gemak van gebruik** | Anime.js heeft een concentratie op een flexibele JavaScript-library om animaties te maken op het web. Je kan met npm of cdn het in een project gebruiken.  | Gsap heeft een uitgebreide "Install helper" waar de makkelijk het can downloaden met npm, yarn of een CDN gebruiken. Ook kan je kiezen welke plugins en extra toevoegingen makkelijk aanvinken om de imports ervan te krijgen. | Redelijk gemakkelijk en goed met React. Het is te installeren met een npm-import of met een scripttag.  |
| **Grootte** | Anime.js heeft veel kleine bestanden waarvan veel onder de 10  kilobytes zijn, omdat het alleen importeert wat je nodig hebt | Het is groter dan andere, zeker met de extra plugins | Het is flexibel, je hoeft alleen te importeren wat nodig is voor jouw project. |
| **Ecosysteem** | goede documentatie en gemeenschap, maar kleiner dan de grotere animation libraries | Gsap heeft een heel groot systeem van gebruikers en wordt door veel bedrijven gebruikt | Het is een bekende library met een gedetailleerde documentatie voor Javascript, React en Vue. |

### Keuze

Onderbouw je keuze[^1] op basis van je vergelijking.

Voor mijn keuze uit de drie Javascript libraries kies ik Gsap.

#### Waarom Gsap?

Ik kies voor GSAP, omdat het de meeste flexibiliteit aan mij kan geven en het ook gemaakt is om wat grotere animaties te maken. De editie van het aantal front-endframeworks, zoals Svelte en React, die ik ook ermee kan gebruiken. Heeft het zeker een populaire keuze gemaakt voor veel bedrijven. Samen met de simpele en uitgebreide "install helper" wordt het makkelijk om een nieuw project te starten.


### Arbeidsmarkt

Onderbouw waarom je keuze belangrijk is voor je toekomstige arbeidsmarkt. Niet vergeten verwijzen[^2] naar bronnen.

Binnen de arbeidsmarkt is een specifieke vraag naar een bepaalde JS library, maar meer een vraag naar UI/UX designers en front-end developers die een framework zoals React of Vue kennen. De meeste misschien alle vragen voor een front-end developer met React skills. Gsap zou mij hier in kunnen helpen omdat ik met de modules all React ga leren kan ik mij nieuwe kennis snel gebruiken. 

### Onderbouwing onderzoek en keuze

Onderbouw je onderzoek en keuze voor software. Niet vergeten verwijzen[^3] naar bronnen.

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

[^1]: NextlevelJobs.eu. (16 maart 2026). 7 Most In-Demand Programming Languages in Europe (2026) — Salaries + Jobs. Geraadpleegd op 20 september 2025 via https://nextleveljobs.eu/blog/7-in-demand-programming-languages-for-2026

[^2]: bron 2

[^3]: bron 3

##
