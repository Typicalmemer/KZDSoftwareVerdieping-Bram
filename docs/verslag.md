# Titel verslag

Versienummer: 1

Auteur: Bram Hooiveld

Studentnummer: 0266808

Klas: 24SDB

Naam keuzedeel: Verdieping Software

Code keuzedeel:

Datum: 16-9-2026

---

<div style="page-break-after: always;"></div>

## Inhoudsopgave

- [Titel verslag](#titel-verslag)
    - [Inhoudsopgave](#inhoudsopgave)
    - [Inleiding](#inleiding)
    - [Maakt een keuze voor software](#maakt-een-keuze-voor-software)
        - [Onderzoek](#onderzoek)
        - [Vergelijking](#vergelijking)
        - [Keuze](#keuze)
        - [Arbeidsmarkt](#arbeidsmarkt)
        - [Onderbouwing onderzoek en keuze](#onderbouwing-onderzoek-en-keuze)
    - [Bronnen](#bronnen)

<div style="page-break-after: always;"></div>

## Inleiding

Op woensdag 16 september is het keuzedeel Verdieping Software begonnen. Hierbij moeten we kiezen waarin we ons de komende 20 weken of minder willen verdiepen. Ik maak hierbij mijn keuze voor de software die ik wil gebruiken. Ik kies drie opties uit de gekozen categorie en onderzoek deze. Na mijn onderzoek maak ik mijn definitieve keuze waarin ik mij wil verdiepen.

## Maakt een keuze voor software

Voor het keuzedeel wil ik mij verdiepen in JavaScript. Niet alleen in JS zelf, maar ook in een JS-library die zich richt op het animeren van elementen op een website.

### Onderzoek

Voor het onderzoek heb ik drie libraries gevonden. Voor elke library bekijk ik de websites waarop deze wordt gebruikt, evenals de documentatie en demo's, als die er zijn. Ik ga niet zoeken naar vacatures voor elke library, omdat er niet specifiek naar één library wordt gevraagd.

De libraries die ik heb gekozen om te onderzoeken zijn:

- GSAP
- Anime.js
- Motion.dev (heette eerst Framer Motion)

### [GSAP](https://gsap.com/)

GSAP is een van de meest populaire JavaScript-animatielibraries. De library wordt onder andere gebruikt door [YouTube](https://www.youtube.com/), [Netlify](https://www.netlify.com/) en [EA](https://www.ea.com/) [^6].

Het opstarten van GSAP

GSAP kan op verschillende manieren in je project worden geïmporteerd.

- Een npm- of yarn-commando
- Een CDN-link

Ook kun je een lijst met functionaliteiten invullen om automatisch een lijst met imports te krijgen [^6].

```JS
gsap.to(".box", { x: 200 })
```

Om een box te animeren, gebruik je een methode van het object `gsap`, gevolgd door de juiste class of id van het HTML-element tussen aanhalingstekens. Het gedeelte tussen `{}` geeft aan wat we ermee willen doen. In dit voorbeeld beweegt het blok 200 px over de x-as.

### [Anime.js](https://animejs.com/)

Anime.js is net als GSAP een JavaScript-animatielibrary. Anime.js kan worden gebruikt met JavaScript en React. De library wordt gebruikt door [Monkeytype](https://monkeytype.com/) en in reclames op [TikTok](https://ads.tiktok.com/business/en?tt4b_lang_redirect=1). Ook wordt de library gebruikt door [Riverside](https://riverside.com/) [^9].

Het opstarten van Anime.js

- Met npm
- Met een CDN
- Door de library rechtstreeks uit de repository te downloaden

Anime.js heeft ook uitgebreide documentatie over de verschillende manieren waarop je de library kunt gebruiken [^7].

### [Motion.dev](https://motion.dev/)

Motion.dev is een flexibele JS-library die je kunt gebruiken met JS, React, Vue, Three.js en WebGPU. De library heeft ook ontwikkeltools, zoals een AI-kit, CSS Studio en MotionScore [^5]. Motion.dev heeft veel partners [^8], zoals [Figma](https://www.figma.com/), [Linear](https://linear.app/) en [Sanity](https://www.sanity.io/).

Het opstarten van Motion.dev

- Met een packagemanager zoals npm of yarn
- Met een scripttag in de HTML

Het gebruiken van Motion [^5]:
Importeer de animatiefunctie:

```JS
import { animate } from "motion"
```

Gebruik `animate()` met een CSS-selector of met het element zelf.

```JS
// CSS selector
animate(".box", { rotate: 360 })

// Elements
const boxes = document.querySelectorAll(".box")

animate(boxes, { rotate: 360 })
```

### Vergelijking

|         | Anime.js | GSAP |  Motion.dev |
| :-------------- | :--------------: | :-----------: | :---------: |
| **Prestatie**  | Lichtgewicht en geschikt voor diverse webanimaties zonder plugins [^1]| Geschikt voor snelle en geavanceerde animaties dankzij de vele plugins. Met lagSmoothing kun je problemen door CPU-pieken helpen voorkomen. Er zijn ook veel optimalisaties beschikbaar [^4] [^6] [^10] [^11]| Gemaakt voor moderne en vloeiende animaties in de browser [^5]  |
| **Functies** | Biedt de mogelijkheid om CSS, versleepbare elementen, SVG, scrollobservatie en staggering te gebruiken. Je kunt de library gebruiken met JavaScript en React [^7].  | GSAP biedt veel mogelijkheden. Je kunt het gebruiken met vanilla JS, React, Svelte, Vue en meer, zoals WebGL, Three.js en Webflow [^6].| Motion.dev heeft uitgebreide documentatie en kan worden gebruikt met frameworks zoals React en Vue, maar ook met vanilla JavaScript [^5] |
| **Gemak van gebruik** | Anime.js is een flexibele JavaScript-library voor het maken van webanimaties. Je kunt de library met npm of via een CDN in een project gebruiken [^7]. | GSAP heeft een uitgebreide 'Install Helper' waarmee je de library eenvoudig met npm, yarn of een CDN kunt installeren. Je kunt ook eenvoudig plugins en extra toevoegingen selecteren om de bijbehorende imports te krijgen [^6]. | Redelijk gemakkelijk en goed te gebruiken met React. De library kan worden geïnstalleerd met npm of via een scripttag [^5].                         |
| **Grootte** |  Anime.js bestaat uit veel kleine bestanden, waarvan er veel kleiner zijn dan 10 kilobytes [^7]. Je importeert alleen wat je nodig hebt. |  De library is groter dan andere, vooral met extra plugins. |  De library is flexibel: je hoeft alleen te importeren wat nodig is voor jouw project [^5]. |
| **Ecosysteem** | Goede documentatie en een gemeenschap, maar kleiner dan die van grotere animatielibraries [^7] [^4]  |   GSAP heeft een groot gebruikersbestand en wordt door veel bedrijven gebruikt. De library heeft ook veel maandelijkse downloads [^4]. Daarnaast is er buiten de officiële website veel informatie te vinden [^2] [^3] [^6]. | Het is een bekende library met uitgebreide documentatie voor JavaScript, React en Vue. Ook wordt de library door bekende bedrijven gebruikt [^8] [^5]. |

### Keuze

Uit de drie JavaScript-libraries kies ik voor GSAP.

### Arbeidsmarkt

Op de arbeidsmarkt is er veel vraag naar front-enddevelopers die een front-endframework zoals React, Vue en/of Svelte beheersen. GSAP is een vaardigheid die ik in combinatie met een van deze frameworks kan inzetten. Dit kan mij helpen om mezelf op de arbeidsmarkt te bewijzen en mijn kennis van JavaScript en later ook React verder te ontwikkelen.

### Onderbouwing onderzoek en keuze

Ik kies uiteindelijk voor GSAP, omdat het veel flexibiliteit biedt. Doordat het veel wordt gebruikt, is er naast de documentatie ook veel informatie beschikbaar. De mogelijkheid om GSAP met verschillende front-endframeworks, zoals Svelte en React, te gebruiken, maakt het een populaire keuze voor veel bedrijven [^6]. Dankzij de eenvoudige en uitgebreide 'Install Helper' is het bovendien makkelijk om een nieuw project te starten [^6].

---

## Maakt zich de software eigen

### Reflectie

Wat weet je al, wat weet je nog niet en wat wil je nog leren? Maak een overzicht van wat je al weet, wat je nog niet weet en wat je nog wilt leren. Zo krijg je inzicht in wat je al weet, en dus ook weet wat je nog niet weet. Neem de tijd om hierop te reflecteren.

S.
Tijdens het onderzoek heb ik veel voorbeelden gevonden van websites die de JS-libraries gebruiken, zoals Figma, Motion, Monkeytype, Anime.js, YouTube en GSAP. Hoewel ik websites en praktische voorbeelden kon vinden, kon ik geen vacatures vinden waarin specifiek naar deze JavaScript-libraries werd gevraagd. Het dichtstbij kwam ik bij vacatures voor front-enddevelopers die een framework zoals React beheersen, in combinatie waarmee ik GSAP kan gebruiken.

T.
Mijn taak was om drie softwarebibliotheken op vijf punten te vergelijken binnen de gekozen categorie, in dit geval JavaScript-animatiebibliotheken. Ik heb geen directe vacatures gevonden, maar wel genoeg websites die deze libraries gebruiken.

A.
Om zoveel mogelijk over elke library te weten te komen, heb ik websites geraadpleegd die de populariteit van de libraries met elkaar vergelijken. Ook heb ik de websites van de libraries zelf bekeken. Daar kon ik de meeste informatie vinden, zoals welke websites de libraries gebruiken.

R.
Aan het einde van mijn onderzoek heb ik de drie libraries met elkaar vergeleken en mijn keuze gemaakt. Ik heb uiteindelijk voor GSAP gekozen.

R.
Ik kon snel drie libraries vinden, maar het was lastig om veel informatie over hun relevantie op de arbeidsmarkt te vinden. Ik vond het onderzoek wel inspirerend. In eerste instantie dacht ik dat Anime.js mijn eerste keuze zou zijn. Na meer onderzoek bleek GSAP beter aan te sluiten bij wat ik wilde leren en kwam ik erachter dat het veel wordt gebruikt.

### Leerdoelen formuleren

Maak een overzicht van je leerdoelen. Wat wil je leren en wat wil je bereiken? Formuleer je leerdoelen [SMART](https://www.uu.nl/sites/default/files/upper_leerdoelen_smart_opstellen.pdf).

S.
Voor mijn keuzedeel ga ik mijn gekozen library, GSAP, gebruiken om een interactieve website te bouwen en aan te tonen dat ik de library beheers. Ik doe dit zelfstandig, met toestemming van de docenten om het juiste project te gebruiken. De komende weken werk ik hier op school aan. Ik wil dit bereiken om te laten zien dat ik een interactieve website kan bouwen.

M.
Om mijn voortgang meetbaar te maken, wil ik een website bouwen waarop ik laat zien wat ik heb geleerd. Aan de hand van de gebruikerservaring van de website kan worden beoordeeld of ik de leerdoelen heb behaald. De website helpt ook om mijn voortgang met GSAP te laten zien.

A.
Door daadwerkelijk een website met GSAP te maken, leer ik de library in de praktijk gebruiken. Tijdens het maken van de website pas ik verschillende GSAP-functionaliteiten toe. Na afloop van onderdelen kijk ik wat goed is gegaan en wat beter kan.

R.
Ik denk dat het mogelijk is om een website te bouwen die laat zien dat ik GSAP beheers. Hiervoor werk ik stap voor stap aan het uitbreiden van mijn kennis.

T.
Ik werk minimaal twee keer per week aan mijn project. Tijdens het werken houd ik bij wat ik heb gedaan, met commits of door dit te noteren. Aan het einde lever ik in wat ik heb geleerd.


### Prototype voorstel

Een duidelijk, uitgebreid prototypevoorstel wat past bij de gestelde leerdoelen.

Voor mijn voorstel beschrijf ik mijn denkproces en doe ik een klein onderzoek naar wat mijn voorstel nodig heeft.

Leerdoelen:
- GSAP verder ontwikkelen
- Een website en de elementen op de website kunnen animeren

Ik wil als prototype een website maken die mijn voortgang en vaardigheden met GSAP laat zien. Dit wil ik doen aan de hand van een portfoliowebsite. Hiermee laat ik zien wie ik ben en welke vaardigheden ik heb.

Maar wat heeft een portfoliowebsite nodig?

Een complete website heeft:
- Een homepage
- Projecten of werk
- Een pagina 'Over mij'
- Een contactpagina


### Planning

Maak een planning met een uitgewerkte tijdslijn van de te volgen stappen om je leerdoelen te behalen. Neem hierin ook de tijd op die je nodig hebt om je prototype te maken.

### Logboek

Houd een logboek bij van de tijd die je besteedt aan het maken van je prototype. Noteer hierin ook de stappen die je hebt gezet om je leerdoelen te behalen.

## Prototype

Leg uit wat je prototype is en hoe je dit hebt gemaakt. Voeg ook een link naar je video van je prototype.

## Eindconclusie

Leerdoelen behaald? Wat heb je geleerd? Wat zou je een volgende keer anders doen? Wat zijn je vervolgstappen?

<div style="page-break-after: always;"></div>

## Bronnen

[^1]: [annnimate.com](https://annnimate.com/compare/best-animation-libraries) door Good Fella. "Best Animation Libraries", laatst gewijzigd op 20 juli 2026.

[^2]: [wmtips.com](https://www.wmtips.com/technologies/javascript-libraries/filter/animation/). "JS libraries, most popular by 2026", de opgenomen data is laatst bijgewerkt op 28 september 2026.

[^3]: [jstool.gitlab](https://jstool.gitlab.io/blog/posts/the-most-popular-javascript-libraries-in-2026/). "The Top 100 Open-Source JavaScript Libraries", geraadpleegd op 28 september 2026.

[^4]: [bestofjs.com](https://bestofjs.org/projects?tags=animation). "Animation libraries", geraadpleegd op 28 september 2026.

[^5]: [Motion.dev](https://motion.dev/). Eerst bekend als Framer Motion. Geraadpleegd op 16 september 2026.

[^6]: [GSAP.com](https://gsap.com/). Geraadpleegd op 16 september 2026. Bijna onderaan de pagina, boven de demo's, staat welke merken GSAP hebben gebruikt.

[^7]: [Anime.js](https://animejs.com/), geraadpleegd op 16 september 2026.

[^8]: [Motion.dev partners](https://motion.dev/partners#partners). Dit zijn de partners en bedrijven waarmee Motion.dev heeft gewerkt. Geraadpleegd op 28 september 2026.

[^9]: [Wappalyzer](https://www.wappalyzer.com/technologies/javascript-graphics/anime-js/). "Websites using Anime.js", geraadpleegd op 30 september 2026. Een lijst met websites die Anime.js gebruiken.

[^10]: [annnimate.com](https://annnimate.com/compare/gsap-vs-anime-js). "Comparison between Anime.js and GSAP", geraadpleegd op 30 september 2026. Een vergelijking van GSAP en Anime.js.

[^11]: [Why GSAP](https://gsap.com/blog/why-gsap/). "FAQ for GSAP". Veelgestelde vragen over GSAP, zoals de bestandsgrootte en animaties.

##