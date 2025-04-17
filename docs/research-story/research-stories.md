# Research Story uitwerkingen

- Datum	:	14/04/2025
- Versie	:	V1.0
- Auteurs	:	Damian, Kasper, Duncan, Soulaiman, Thomas & Jens

## Inhoud

- [Research Story Uitwerkingen](#research-story-uitwerkingen)
    - [Inleiding](#inleiding) 
    - [Simpel & Effectief Vak Upload Systeem](#simpel-&-effectief-vak-upload-systeem)
    - [Geschikte Back-end Programmeertaal](#geschikte-back-end-programmeertaal)
    - [Geschikte Front-end Programmeertaal](#geschikte-front-end-programmeertaal)
    - [Nuttige Gamification Type(s)](#nuttige-gamification-type(s))
    - [Website Gebruiker Motivatie](#website-gebruiker-motivatie)
    - [Efficiënt/effectief Leerplatform Kenmerken](#efficiënt/effectief-leerplatform-kenmerken)
    - [Geschikte Databasetaal](#geschikte-databasetaal)

---

## Inleiding

Wij, als development-team, hebben meerdere research stories opgesteld rondom de hoofdvraag: "Hoe kan gamification worden geïntegreerd in een bestaande webapplicatie om de betrokkenheid en leerervaring van studenten te verbeteren, geïnspireerd door het Duolingo-model?"

Deze research stories zijn uitgevoerd met als doel een stevige kennisbasis op te bouwen, zodat we de wensen van de opdrachtgever op een doordachte en onderbouwde manier kunnen realiseren. Door het beantwoorden van de deelvragen binnen deze stories hebben we inzicht gekregen in de beste aanpak voor elk specifiek aspect van de hoofdvraag.

---

## Simpel & Effectief Vak Upload Systeem

### Beschrijving

We willen een simpel systeem bouwen voor de webapplicatie waarin de docent een vak kan aanmaken en vervolgens hoofdstukken hieraan kan toevoegen. Deze hoofdstukken moeten uitleg en vragen bevatten die de docent zelf kan invullen / samenstellen. Op welke manier is dit het best te doen? Op basis van de al gemaakte wireframe(s), of moeten deze toch verbetert worden/gemaakt worden op een andere manier? Reasearch story op basis van deelvraag: "Wat is de beste manier om een simpel & effectief systeem te maken voor de docent om vakken en hoofdstukken aan te maken voor het leerplatform? Functionele deelvraag".

---

### Eisen opdracht gever vaststellen

Om verder te kunnen werken aan #43 moet er duidelijk op papier gezet worden wat de opdrachtgever precies verwacht van een systeem waarmee docenten vakken en hoofdstukken kunnen aanmaken op het leerplatform. De opdrachtgever heeft aangegeven dat de volgende 3 onderdelen aanwezig moeten zijn voor een docent bij het maken van een module/onderdeel/opdracht:

#### Module (0, 1 of MEER):
- MOET: naam;
- MAG: introductie;
- MAG: Onderdelen.

#### Onderdeel (0, 1 of MEER):
- MOET: naam;
- MAG: introductie;
- MAG: opdrachten.

#### Opdracht (meerkeuze-vraag) (0, 1 of MEER):
- MOET: naam;
- MAG: introductie;
- MOET: vraag;
- MOET: antwoord keuzes;
- MAG: hint.

---

### Analyse bestaande (web)applicaties

Om een goed beeld te krijgen wat een goede aanpak is voor #43 is een verstandige zet: kijken hoe populaire websites zoiets vergelijkbaars aanpakken.

#### Kahoot
Als eerst heb ik gekeken naar de bekende quiz/oefen website genaamd Kahoot. Ik heb gekeken naar wat de verschillende/nieuwe features zijn tussen de eisen van de opdrachtgever en deze website. Deze zijn:

##### Module/module info 
- Importeer optie; 
- Zichtbaarheid instelling;
- Cover afbeelding;
- Taal instelling;
- Het opslaan van de module naar je eigen computer.

##### Hoofdstukken
- Geen.

##### Opdrachten/vragen
- Verschillende type vragen;
- Introductie tekst en of media (e.g. afbeelding/video);
- Tijd limiet;
- Punten.

#### StudyGo (wrts)
Vervolgens heb ik gekeken naar een andere bekende quiz/oefen site genaamd StudyGo. Ik heb nogmaals gekeken naar de features die verschillen. Deze zijn:

##### Module/module info
- Geen.

##### Hoofdstuk
- Importeer optie.

##### Opdrachten/vragen
- Verschillende type vragen;
- Introductie tekst en of media (e.g. afbeelding/video);
- Vervolg vragen.

#### Vergelijking
Na het vergelijken van de 2 verschillende sites kunnen deze met elkaar natuurlijk ook vergeleken worden. Overeenkomende features kunnen mogelijk handige en aantrekkelijke features vormen. Hier zijn er een aantal van:
- Imports: zowel Kahoot als StudyGo bevatten beide importeer opties voor module content;
- Verschillende vragen: beide hebben keuzen uit verschillende typen vragen;
- Media intro: beide hebben de optie om media toe te voegen naast een tekstuele introductie van een vraag.

Als er genoeg tijd is voor verbeteringen aan de web applicatie als er een werkend product geleverd kan worden, zouden deze 3 features toegevoegd kunnen worden. Deze 3 vallen beide goed binnen de visie van de opdrachtgever.

Unieke features:
- Module zichtbaarheid instelling (Kahoot);
- Module cover afbeelding  (Kahoot);
- Taal instelling  (Kahoot);
- Opdracht/vraag tijdlimiet instelling  (Kahoot);
- Punten per opdracht en of hoofdstuk  (Kahoot);
- Vervolg opdracht/vraag van een andere opdracht/vraag (StudyGo).

Van de unieke features is de zichtbaarheid kunnen instellen een must bij de eerste werkende oplevering. Hierna zou een punten systeem per module/onderdeel/opdracht een goed idee kunnen zijn om de website competitief te maken, of dit echt iets goeds is wordt onderzocht in een andere research story. De overige features zouden als goede verbeteringen kunnen dienen.

---

### Criteria van een goed systeem opstellen

Naast de gedefinieerde functies in #50 (van research story #43) is het belangrijk om criteria waar een goed systeem aan moet voldoen op papier te zetten. Dit houd in wat echt niet kan missen.

- Zowel naam van een cursus/onderdeel/opdracht als een optioneel introductie veld;
- Zichtbaarheid instelling (zichtbaar voor studenten en welke en of voor docenten en welke);
- Dynamisch toevoegen of verwijderen van onderdelen/opdrachten;
- Downloaden en uploaden van een cursus. 

Als deze 4 features in het eindresultaat zitten zal dit zorgen voor een goede basis en voldoet dit aan de minimale verwachtingen van een algemene gebruiker.

---

### Tekstueel content-structuur

Vòòr het maken van een uitgebreid diagram/mockup is het nu handig om eerst op papier te zetten. Dit heb ik gedaan door middel van een "tekstueel content-structuur" ontwerp. Voorbeeld met van elk onderdeel 1 al aangemaakt. Gebruik van tekens:
- `*` = Benodigt;
- `v-select` = Selectie uit meerdere;
- `{ ... }` = Toont de inhoud van een onderdeel;
- `[x]` = Correct antwoord;
- `[]` = Fout antwoord;
- `[+ ...]` = Toevoeg knop;
- `[- Verwijder ...]` = Verwijderen knop.

Ontwerp:

![Image](https://github.com/user-attachments/assets/45d2bc50-65b0-490d-b521-1a970fee690d)

---

### Review tekstuele ontwerp

Review ontvangen van @ThomasHU123 onder #52: "Structuur ziet er goed uit. Voor de nieuwe dingen kan er nu een wireframe gemaakt worden."

---

### Feedback verwerking in verbeterde mockups

Na het ontvangen van feedback, heb ik van deze feedback en het textuele ontwerp de bestaande mockups verbeterd. Deze zijn nu als volgt:

![Mockup add vak](https://github.com/KasperMeijer/TODSS-DrieVakantiesNodig/blob/main/images/mockup-add-vak-page.png)

![Mockup add hoofdstuk](https://github.com/KasperMeijer/TODSS-DrieVakantiesNodig/blob/main/images/mockup-add-hoofdstuk-page.png)

![Mockup add vraag](https://github.com/KasperMeijer/TODSS-DrieVakantiesNodig/blob/main/images/mockup-add-vraag-page.png)

![Mockup import](https://github.com/KasperMeijer/TODSS-DrieVakantiesNodig/blob/main/images/mockup-add-import-page.png)

![Mockup export](https://github.com/KasperMeijer/TODSS-DrieVakantiesNodig/blob/main/images/mockup-add-export-page.png)

---

### Conclusie

Na het uitvoeren van deze research story is een duidelijk en verbeterd ontwerp tot stand gekomen voor het beheren van vakken en hoofdstukken binnen een leerplatform. Door analyse van vergelijkbare platforms zoals Kahoot en StudyGo, het opstellen van systeemcriteria en het verwerken van ontvangen feedback, zijn er overzichtelijke mockups ontwikkeld. Deze sluiten goed aan bij de wensen van de opdrachtgever en leggen de basis voor een functionele implementatie in de webapplicatie.

Het systeem is ontworpen met gebruiksgemak en uitbreidbaarheid in gedachten, waarbij essentiële functies zoals zichtbaarheid, dynamisch beheer van inhoud en import/exportmogelijkheden zijn meegenomen. Een volgende stap is het ontwikkelen van deze component en het verder onderzoeken van optionele functies zoals puntenverdeling en mediatypen per opdracht.

---

### Bronnen

- _StudyGo_. (z.d.). https://studygo.com/nl/learn/create-list;
- _Kahoot!_ (z.d.). Create, Explore, And Host Kahoots | Kahoot! https://create.kahoot.it/creator;
- Eerder gemaakte mockup(s): ![Image](https://github.com/user-attachments/assets/1463270e-1bf6-4e72-a18e-ac8cb093cfb2)

---

## Geschikte Back-end Programmeertaal

### Welke backend talen zijn er?

Een simpele zoekopdracht op Google geeft al heel veel opties en mogelijkheden. Eigenlijk kunnen er een heleboel programmeertalen gebruikt worden en ligt het er maar net aan waar je goed in bent of wat de eisen zijn van het project. Volgens de Stackoverflow Survey van 2024 worden de onderstaande programmeertalen het meest gebruikt onder programmeurs.
1.	JavaScript
2.	SQL
3.	HTML/CSS
4.	Python
5.	TypeScript
6.	Bash/Shell
7.	Java
8.	C#
9.	C++
10.	PHP
11.	C
12.	Go
13.	Powershell
14.	Rust
15.	Kotlin
16.	Dart
17.	Ruby
18.	Lua
19.	Swift
20.	Visual Basic
21.	Assembly

Er volgen nog meer programmeertalen, maar deze zijn een stuk minder bekend en worden door minder dan 5% van de programmeurs gebruikt. Een aantal talen hiervan kunnen we niet gebruiken voor een backend. Denk hierbij aan HTML/CSS en SQL. Hieruit kunnen we opmaken dat er voor backend vooral JavaScript/TypeScript (TypeScript is een soort extensie van JavaScript en lijkt hier dus erg op), Python, Java, C#. We gaan met deze 4 verder onderzoek doen. 

---

### Wat zijn de voor- en nadelen per programmeertaal?

Elke taal heeft zijn eigen mogelijkheden en elke taal is dus anders. Het ligt er maar net aan in wat voor project je de taal wilt gaan gebruiken. Dat is dus precies de reden dat we dit onderzoek doen. 

#### JavaScript / TypeScript

JavaScript is erg populair. Met de groei van Node.js wordt JavaScript steeds meer gebruikt voor de backend. Een aantal voordelen van (FreeCodeCamp, 2019) JavaScript zijn:
•	JavaScript is snel
•	JavaScript heeft simpele syntax wat gebaseerd is op Java
•	JavaScript is heel populair. Op GitHub is een toename te zien van de projecten die JavaScript gebruiken
•	JavaScript wordt al gedomineerd in de frontend. Als je voor zowel de frontend als backend JavaScript gebruikt hoef je maar één taal te gebruiken en dus niet steeds te switchen. Hierdoor is het beter te onderhouden

#### Python

Python staat bekend om het simpele gebruik en wordt steeds populairder voor backend development (Jeremiah, 2024). Voordelen van het gebruiken van een Python backend zijn:
•	Python heeft simpele syntax en is makkelijk te gebruiken voor beginnende gebruikers
•	Python ondersteund Object Oriented Programming
•	Python heeft veel standaard en derde libraries
•	Python heeft een grote community
•	Python staat bekend om haar schaalbaarheid en prestaties in combinatie met een framework zoals Django en Flask 
•	Python kan makkelijk verbinden met een SQL of NoSQL database 
•	Python wordt veel gebruikt voor Data Science en Machine Learning

#### Java

Java is ontwikkeld in 1991 door James Gosling en in 1995 uitgebracht voor openbaar gebruik in webapplicaties. Volgens FreeCodeCamp (Fagbuyiro, 2023) heeft Java de volgende voordelen:
•	Java is Strongly Typed, je moet data types aangeven bij variabele. Dit voorkomt errors
•	Java gebruikt een compiler in tegenstelling tot Python (Interpreter)
•	Java is schaalbaar en robuust
•	Java heeft veel libraries die open-source en gratis zijn
•	Java is divers, wordt door veel IDE’s ondersteund
•	Java syntax is simpel en snel te leren
•	Java is veilig
•	Het is WORA taal, Write Once Run Anywhere, kan op elke machine gedraaid worden
Enige nadelen van Java zijn:
•	Java zou gericht zijn op opslag en niet data back-ups. Dit zou een groot nadeel zijn onder veel gebruikers
•	Java code kan complex zijn, gebruik van veel woorden
•	Java gebruikt veel geheugen en is aanzienlijk trager dan C of C++. De snelheid en prestaties zijn dus iets lager

#### C#

C# lijkt erg op Java. C# heeft ook een Compiler en is ook Strongly Typed (je moet dus bij je variabele aangeven om wat voor data type het gaat). Enkele voordelen (Mir, 2023) van C# zijn:
•	C# is Strongly Typed, je moet data types aangeven bij variabele. Dit voorkomt errors
•	C# heeft een Compiler in tegenstelling tot een Interpreter
•	C# staat erom bekend goed samen te werken met Microsoft en Windows systemen

---

### Welke frameworks zijn er beschikbaar per programmeertaal?
Op hotframeworks.com is de Github score van de verschillende frameworks te zien en zo overzichtelijk te zien wat het populairst is.

| Framework        | Language    | GitHub Score | StackOverflow Score | Final Score |
|------------------|-------------|---------------|----------------------|-------------|
| Django           | Python      | 92            | 97                   | 95          |
| Laravel          | PHP         | 91            | 94                   | 93          |
| Ruby on Rails    | Ruby        | 89            | 97                   | 93          |
| Spring Boot      | Java        | 91            | 91                   | 91          |
| Express          | JavaScript  | 90            | 88                   | 89          |
| Flask            | Python      | 90            | 84                   | 87          |
| ASP.NET Core     | C#          | 85            | 87                   | 86          |
| Symfony          | PHP         | 83            | 86                   | 85          |
| NestJs           | TypeScript  | 90            | 72                   | 81          |
| Meteor           | JavaScript  | 87            | 79                   | 83          |

Volgens Stackoverflow Survey worden de volgende Frameworks gebruikt voor de backend van een applicatie. Per programmeertaal wordt de meest gebruikte Framework uitgewerkt.

#### JavaScript / TypeScript

![image](https://github.com/user-attachments/assets/ed7ca95c-9aa1-4b97-9f77-5d4ae7e72c94)

#### Express

Express is een Web Framework (Copes, 2022) wat gebouwd is op Node.js. Node.js is een soort basis waar veel services en applicaties op worden gebouwd en verder kan worden uitgebreid zoals Express. Met behulp van Express kan je een webserver opzetten. De voordelen van Express zijn onder andere dat het gratis is, open source is, makkelijk uit te breiden is en daarnaast ook nog eens hoge prestaties aantoont. Daarnaast kan je gebruik maken van bestaande soort “prebuilds” waardoor je heel snel aan de slag kan en je eigen draai kan geven aan de applicatie.

#### Python

![image](https://github.com/user-attachments/assets/171bd6f6-c896-4ddb-a48c-d1e5c5ac5966)

#### Django

Django, ontwikkeld tussen 2003 en 2005, is een Python Web Framework (MDN, sd) die zorgt voor snelle ontwikkeling van veilige en onderhoudbare websites. Net zoals Express is Django gratis en open source. Bekende websites zoals Instagram, Mozilla en Pinterest maken ook gebruik van Django. Django maakt gebruik van de Model-View-Template architectuur en kan wat meer moeite kosten om te leren. Daarnaast is Django iets langzamer in vergelijking met Express (Gauthier, 2024).

#### Java

![image](https://github.com/user-attachments/assets/9aea43f7-79f1-48ae-9d23-fba36845ef7b)

#### Spring boot

Spring Boot (Microsoft, sd) is een module die is voortgekomen uit het Spring Framework wat in 2003 is gestart. Naast Spring Boot heb je ook nog modules als Spring Security en Spring Data. Met de Spring Initializr (start.spring.io) kun je binnen enkele seconden een nieuw Spring Boot project opzetten. Je kunt makkelijk dependecies zoals Hibernate of Lombok toevoegen, maar dus ook de modules als Spring Security en Spring Data. Spring Boot is puur gefocust op het opzetten van een webserver door gebruik te maken van de ingebouwde HTTP-servers zoals Tomcat. Binnen Spring wordt wel weer gebruik gemaakt van de Model-View-Controller architectuur wat makkelijker te leren is.

#### C#

![image](https://github.com/user-attachments/assets/27b1081c-1e3a-4b58-841b-6247330b9e14)

#### ASP.NET Core

ASP.NET Core is een open source framework (Microsoft, 2024) wat gebruikt wordt voor het bouwen van moderne, cloud- en internet verbonden applicaties. Door ASP.NET Core MVC te gebruiken is het mogelijk om Web API’s en Web apps te bouwen. Ook C# maakt gebruik van de Model-View-Controller architectuur. 

---

### Welke programmeertaal en Framework is het meest geschikt voor dit project?

#### Welke eisen stelt het project aan de programmeertaal?

De opdrachtgever van het project heeft aangegeven wellicht gebruik te willen maken van de bestaande bot in de applicatie. Dit is geen must en hier wordt alleen naar gekeken als er nog tijd voor is. Het bestaande project bestaat uit een TypeScript frontend, C# backend en Python Bot. Nu is met de opdrachtgever afgesproken dat we de webapplicatie vanaf start opbouwen en dus niet rekening hoeven te houden met de bestaande ontwikkelomgeving. Wel houden we de Python bot in het achterhoofd. Deze zou samen moeten kunnen werken met onze backend

#### Welke eisen stellen wij als team aan de programmeertaal?
Als team hebben wij voornamelijk gewerkt met Java. Python hebben wij kort behandeld in ons eerste jaar en is dus best wel wat weggezakt. JavaScript hebben wij wel wat langer gehad, maar daar hebben wij meer gekeken naar de frontend van een applicatie. Wij willen als team werken met een programmeertaal waar wij al veel van weten en snel mee aan de slag kunnen. Hierdoor ligt onze keuze voor de backend al snel bij Java gecombineerd met het Spring Boot Framework. 

---

### References

- Copes, F. (2022, November 18). The Express + Node.js Handbook – Learn the Express JavaScript Framework for Beginners. Retrieved from FreeCodeCamp: https://www.freecodecamp.org/news/the-express-handbook/
- Fagbuyiro, D. (2023, February 9). Why You Should Use Java for Backend Development. Retrieved from FreeCodeCamp: https://www.freecodecamp.org/news/java-for-backend-web-development/
- FreeCodeCamp. (2019, December 5). The Advantages and Disadvantages of JavaScript. Retrieved from FreeCodeCamp: https://www.freecodecamp.org/news/the-advantages-and-disadvantages-of-javascript/
- Gauthier, M. (2024, April 20). Express VS Django. Retrieved from Medium: https://medium.com/@mikegauthier222/express-vs-django-d5c30ecad1e9
- HotFrameWorks. (n.d.). Retrieved from HotFrameWorks: https://hotframeworks.com/
- Jeremiah, O. (2024, August 18). Python Backend Development: A Complete Guide for Beginners. Retrieved from Datacamp: https://www.datacamp.com/tutorial/python-backend-development?dc_referrer=https%3A%2F%2Fwww.google.com%2F
- MDN. (n.d.). Retrieved from Django introduction: https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Django/Introduction
- Microsoft. (2024, June 18). Overview of ASP.NET Core. Retrieved from Microsoft: https://learn.microsoft.com/en-us/aspnet/core/introduction-to-aspnet-core?view=aspnetcore-9.0
- Microsoft. (n.d.). Wat is Java Spring Boot? Retrieved from Microsoft: https://azure.microsoft.com/nl-nl/resources/cloud-computing-dictionary/what-is-java-spring-boot
- Mir, M. A. (2023, April 1). What are the advantages of C# over Python or Java? Retrieved from Medium: https://medium.com/@ssc.ahmed.926748/what-are-the-advantages-of-c-over-python-or-java-8f906112cd61
- Stackoverflow. (2024). Technology | 2024 Stack Overflow Developer Survey. Retrieved from Stackoverflow: https://survey.stackoverflow.co/2024/technology#most-popular-technologies-language-prof

---

## Geschikte Front-end Programmeertaal

_Niet gemaakt door @jensdor_

---

## Nuttige Gamification Type(s)

### ONDERZOEK:

Welke type(s) gamification is/zijn het meest geschikt voor onze web-applicatie doeleinden? Functionele 

er worden 7 main types van gamifacation benoemd
1.	Points and rewards
2.	Leaderboards and rankings
3.	Badges and achievements
4.	Challenges and quests
5.	Interactive storytelling
6.	Social sharing and collaboration
7.	Data-driven engagement

Dit zijn de 7 types die benoemd worden.
[Link naar source gamification](https://quizmodeon.com/blog/7-types-of-gamification)

---

### POINTS & REWARDS:

Dit type gamifaction is zoals de name voorsteld. Je word beoordeeld op wat je doet en aan de hand van je score krijg je een reward. 

Dit type kan er voor  zorgen dat de gebruiker meer ze best zal doen of zich zelf zou willen verbeteren een daarom meer engagement krijgt met het systeem omdat het de gebruiker dan zelf kan zien of hij verbetert en dit kan leiden tot meer motivatie.

[Dit artikel](https://uxplanet.org/gamification-rewarding-with-personal-stats-2e550df34af7) gaat dieper in op dit type gamifaction naast het feit dat het dieper in gaat heeft het ook voorbeelden vanuit al bestande aplicaties zoals de nikke+ running app. Uiteindleijk beneomd het dat dit type gamifacation niet alleen te ggebruiken is maar gekombineerd moet worden om er voor te zorgen dat de gebruiker gemotiveerd blijft om te leren en terug tekomen.
Zoals het er naar uit ziet gaan  wij deze toepassen op het project.

---
 
### LEADERBOARDS AND RANKINGS:

Dit type gamifaction is ook net zoals name zegt en gaat goed samen met de points & rewards type wegens zijn meet baarheid . Hier word een rankings lijst(leaderboard) toegepast om zo te meten wie het best bezig is. Dit zorgt ervoor dat je direct feedback onvangt en dus direct ziet of je het goed doet. Uitenlijk zal dit dan kunnen zorgen voor meer motivatie om een betere ranking te krijgen of je eigen PB te verbeteren waardoor de gebruiker dus meer engaged blijft.
[Dit artikel](https://medium.com/design-bootcamp/gamification-strategy-when-to-use-leaderboards-7bef0cf842e1) gaat hier dieper op in waarom/wanneer je het best dit type gamifaction kan gebruiken.

Hun conconclusie komt neer op dat het een goed idee is alleen moet je oppassen met een te groote leaderboard omdat zoals zij het zeggen “Seeing you are 5/10 is not too bad, but seeing you are ranked 1005/1010 could be devastating. It turns out anyone would rather be the best of the worse than the worst of the best.”

Daarnaast geven ze ook genoeg voorbeelden hoe dit type kan gebruiken.

Zoals het er uit ziet gaan wij dan deze toepassen op het project.

---

### BADGES & ACHIEVEMENTS:

Dit type gamifaction gaat vaak samen met points & rewards om duidelijke meet waardes te krijgen voor het uitdelen vand badges je zou zelfs kunnen bedenken dat misschien het REWARDS deel van dat type dit is dus points & ( badges & achievements). 

Wat het voornamelijk doet is het reward je op je prestaties dit is een goede visuele indiacator of je verbetering leverd of het good aan het doen bent je zou zelfs door middel van de achievements of badges de gebruiker toegang kunnen geven tot iets niuews zoals een behaalde achievement geeft een puzzle stukje haal alle puzzelstukjes een je unlocked een limited timed iets wat je kan doen. Dit zorgt dan vervolges voor meer engagement met het systeem en meer motivatie omdat de gebruiker dan bijvoorbeeld dan die ene achievement nodig heeft om dat iets te unlocken.

[Dit artikel](https://www.scavify.com/gamification/gamification-badges) gaat hier wat dieper op in wat bijvoorbeeld de motivatie grepen zijn van dit type.

Zij hebben dan wel geen concrete conclustie maar benoemen wel wat de voordelen zijn van het type en in welke situatie je ze kan gebruiken 
Zoals het er uit ziet gaan we deze toepassen op het project

---

### CHALLENGES & QUESTS:

Dit type gamifaction gaat goed samen met badges & achievements want dit kan de prerequisite voor het ontvangen van een badges of het behalen van een achievenement.
Wat je hier voornamelijk doet is dat je de gebruiker een duidelijk doel geeft die dan ingesteld zou kunnen worden door de beheerrder van de aplicatie die kan je dan zowel time limited maken of standaard. Dit is dan een motivatie factore om die challange of quest te doen voordat hij verloopt of gewoon als doel om iets te behalen en is dus ook een goede visuele indicator

[Dit artkil](https://blog.tubikstudio.com/gamification-in-ux-missions-and-challenges/) gaat hier dieper op in 

Hun conclusie is dat dit type voornamelijk is als een motievatie booster en engegement booster niet perse een methode om het leuker te maken.
Zoals het er uit ziet gaan wij deze toepassen op het project.

---

### INTERACTIVE STORYTELLING:

Dit type gamifacation gaat goed samen met een goed geschreven verhaallijn.
Dit is een type gamifaction om de gebruiker engaged te houden doormidel van een goed verhaal waarbij de gebruiker input heeft dit kan in de form van een gesprek waarbij de gebruiker dan antworden moet geven en dan aan het einde de situatie ziet uitspelen.

[Dit artikel](https://hummingbirdsday.medium.com/gamification-7-interactive-storytelling-e6229469a5ae) gaat hier verder op in.

Deze gaan wij niet gebruiken in dit project 

---

### SOCIAL SHARRING & COLLABORATION:

Dit type gamification is goed voor het samenwwerken en het motiveren doormiddel van elkaar door bijvoorbeeld elkaars profiel te kunnen inzien of samen een vraag te kunnen beantwoorden of door een wedstrijd tegen elkaar te spelen waarbji je elke dag een random vraag krijgt die eider dan beantwoord en zo kan je een stand bij houden.

Dit gaat daarom ook vaak goed samen met de leaderboord type en het artikel die daar benoemd is geeft ook een paar situaties van deze type aan.

Deze kan gebruikt worden in het project maar heeft dan een lage prio dan de andere al die al benoemt zijn.

---

### DATA-DRIVEN ENGAGEMENT:

Dit type gamifaction is een realtime tracker type waarbij er geken word naar jouw engagment op het systeem een aanpassingen gemaakt opbassis van de al gebruikte gamifaction stratagieén.
[dit artikel](https://www.motivacraft.com/gamification-for-data-driven-decisions-how-to-make-better-decisions-with-gamification/) gaat hier verder op in 
zo word er benoemt dat dit type bijvoorbeeld valt onder het maken van grapieken om statestieken te laten zien zo zou je het bijvoorbeeld kunnen gebuiken om een scherm te maken waar dan opstaat hoeveel van de de gebruikers een achievement hebben gehaalt enz.

deze gaat ook gebruikt worden in dit project.

---

### Conclusie:

Voor dit project lijkt het handig om gebruik te gaan maken van de types: 
-	Points and rewards
-	Leaderboards and rankings
-	Badges and achievements
-	Challenges and quests
-	Data-driven engagement
Waarbij  Social sharing and collaboration als een misschien later nog toegepast kan worden

De points kunnen dan toegekent worden door de opdracht modules waarbij er speciale opdracht modules gemaakt kunnen worden door de docenten die dan vallen onder limited of niet limited time quests 
Daarnaast kunnen we dan aan de hand van de behaalde scores van de modules de leaderboards maken en de badges/ achievements uitdellen. Daarnaast zouden we dan in het scherm van de leaderboard een butten kunnen toevoegen om het scherminhoud te verandere om zo de collective data te laten zien van het gehaalde badges of achievements.

Hoewel dit laaste deel overeen komt met de social sharing and collaboration type benoemen we het niet als dit type en zoals benoemt in het deel van  social sharing zouden misschien een head to head mode kunnen maken maar dit is dan nog een bespreek geval met de opdrachtgever en het team.

---

### BRONNEVERMELDING:

- Quizmodeon. (z.d.). 7 Types of Gamification | Blog. https://quizmodeon.com/blog/7-types-of-gamification
- Eşanu, E. (2019, 7 oktober). Gamification: Rewarding users with points - UX Planet. Medium. https://uxplanet.org/gamification-rewarding-with-personal-stats-2e550df34af7

- Liberty, S. (2024, 27 november). Gamification Strategy: When to use Leaderboards - Bootcamp - medium. Medium. https://medium.com/design-bootcamp/gamification-strategy-when-to-use-leaderboards-7bef0cf842e1
- 12 Ways Gamification badges Motivate Teams + Examples 2024 | Scavify ®. (z.d.). https://www.scavify.com/gamification/gamification-badges
- Gamification in UX. Missions and Challenges. (2023, 14 augustus). Tubik Blog: Articles About Design. https://blog.tubikstudio.com/gamification-in-ux-missions-and-challenges/
- Hummingbirdsday. (2022, 30 maart). Gamification (7): Interactive Storytelling - Hummingbirdsday - Medium. Medium. https://hummingbirdsday.medium.com/gamification-7-interactive-storytelling-e6229469a5ae
- Platform, M. G., & Platform, M. G. (2024, 3 mei). Gamification for Data-Driven Decisions: How to Make Better Decisions with Gamification. Motivacraft. https://www.motivacraft.com/gamification-for-data-driven-decisions-how-to-make-better-decisions-with-gamification/

---

## Website Gebruiker Motivatie

### Onderzoeksvraag

**Hoe zorgen we ervoor dat gebruikers gemotiveerd blijven om onze leerapp te gebruiken? En hoe kunnen we dat doen met meldingen, e-mails of andere manieren?**

---

### Inleiding

Veel mensen beginnen enthousiast met leren via een app, maar stoppen na een tijdje. Het is daarom belangrijk dat de app manieren gebruikt om gebruikers te blijven motiveren. Uit onderzoek blijkt dat dingen als meldingen, beloningen, doelen en sociale functies goed kunnen helpen. In dit onderzoek kijken we hoe we zulke functies kunnen gebruiken om gebruikers actief te houden op een leerplatform.

---

### 1. Waarom motivatie belangrijk is

Als gebruikers gemotiveerd zijn, leren ze vaker en beter. Volgens onderzoekers Deci en Ryan  blijven mensen vooral gemotiveerd als ze het gevoel hebben dat ze:

- Vrij kunnen kiezen wat ze doen (autonomie),
- Goed worden in iets (competentie),
- En verbonden zijn met anderen (sociale band).

Een leerapp kan op al deze punten helpen, bijvoorbeeld door keuzes te bieden, voortgang te laten zien, en andere mensen bij het leerproces te betrekken.

---

### 2. Manieren om motivatie te verhogen

#### 2.1 Spel-elementen (gamificatie)

Leren kan soms saai en vermoeiend zijn, helemaal als je het idee hebt dat je alleen maar puur aan het blokken bent.
Daarom gebruiken veel leerapps spelelementen om een gebruiker zijn leerervaring leuker en spannender te maken.
Dit noemen we gamificatie. 
Je ziet dit ook terug in games: je krijgt punten, je kunt levels halen of je krijgt een beloning als je iets goeds doet. 
In een leerapp werkt dat eigenlijk net zo.

Onderzoekers zoals Hamari et al. (2014) hebben onderzocht of dit ook echt helpt – en dat doet het! 
Als je bijvoorbeeld iets kunt winnen of een doel kunt halen, dan ben je sneller geneigd om terug te komen naar de app en door te blijven oefenen. 
Het wordt een soort spel dat je elke dag een beetje beter wil spelen.
**Voorbeelden in de app:**

- Punten verdienen voor elke oefening.
- Een badge als je 5 dagen achter elkaar leert.
- Een lijst met scores van jou en andere gebruikers.

#### 2.2 Doelen en voortgang

Mensen blijven langer gemotiveerd als ze kunnen zien hoe goed ze het doen. Volgens Clark & Mayer helpt het aanzienlijk als gebruikers een duidelijk doel voor ogen hebben wat realistisch te bereiken is en vaak feedback ontvangen over hun voortgang. Dit zorgt voor een gevoel van controle, wat belangrijk is voor motivatie.

Wanneer gebruikers weten waar ze naartoe werken en tussendoor bevestiging krijgen dat ze op de goede weg zijn, is de kans groter dat ze gemotiveerd blijven om door te gaan. Dit past ook bij de motivatiepsychologie: mensen raken gemotiveerd wanneer ze succeservaringen opdoen en het gevoel hebben dat ze groeien.

**Voorbeelden in de app:**

- Een voortgangsbalk die laat zien hoeveel je al hebt gedaan.
- Instellen van eigen leerdoelen (bijv. 10 minuten per dag).
- Een kort berichtje met feedback na elke oefening.
- Een buffer dag/dagen kiezen waarin je niks hoeft te doen voor de dag.

#### 2.3 Geef de gebruiker een voldoende uitdaging

Gebruikers blijven gemotiveerd als de moeilijkheidsgraad van de oefeningen goed aansluit bij hun niveau. Als iets te moeilijk is, raken mensen gefrustreerd en haken ze af. Maar als het te makkelijk is, verliezen ze snel hun interesse. Het is dus belangrijk om een goede balans te vinden: de uitdaging moet precies goed zijn – niet te moeilijk, maar ook niet te makkelijk.

Volgens de theorie van Vygotsky is leren het meest effectief in de "zone van naaste ontwikkeling" – dit is het gebied waar een gebruiker net buiten zijn huidige kunnen leert, maar het met wat hulp of oefening wel kan halen. Dit principe kun je ook toepassen in een leerapp.

**Dit kan je bereiken door:**
- Moeilijkheidsgraden: Gebruikers kunnen kiezen tussen bijvoorbeeld makkelijk, gemiddeld en moeilijk. De app past de vragen of opdrachten aan op het gekozen niveau.

- Adaptieve content: De app past zich automatisch aan op basis van de prestaties van de gebruiker. Als iemand goed scoort, worden de oefeningen wat moeilijker. Als iemand juist moeite heeft, krijgt die gebruiker extra uitleg of makkelijkere vragen.

- Beloningen voor moeilijke taken: Gebruikers kunnen extra punten, badges of complimenten krijgen als ze een moeilijkere opdracht succesvol afronden. Dit moedigt aan om zichzelf uit te dagen.

 Door deze technieken toe te passen blijft de leerervaring motiverend en uitdagend, hiermee blijven gebruikers langer gemotiveerd  om door te gaan.

---

### 3. Gebruik van meldingen en berichten

#### 3.1 Push-notificaties


Push-notificaties zijn korte berichten die op het scherm van je telefoon verschijnen, zelfs als je de app op dat moment niet gebruikt. Ze worden vaak gebruikt om gebruikers te herinneren aan iets belangrijks of om ze terug te brengen naar de app. 
In leerapps kunnen notificaties een sterke rol spelen bij het motiveren van gebruikers om door te gaan.

Volgens onderzoek van **Localytics (2018)** openen gebruikers de app vaker als er op een slimme manier gebruik wordt gemaakt van push-notificaties. 
Maar let op: ze moeten wel goed worden ingezet. Teveel meldingen of meldingen die niet revelant zijn, kunnen juist een negatief effect hebben.

##### Wat werkt goed volgens onderzoek:

- **Verstuur meldingen op het juiste moment.**  
  Mensen reageren beter op meldingen wanneer ze op een handig moment komen, bijvoorbeeld in de avond of vlak na school of werk. Dan hebben ze meer rust om even te oefenen.

- **Personaliseer de meldingen.**  
  Niet iedereen wordt door hetzelfde aangesproken. Iemand die vaak actief is, kun je motiveren met woorden als “Je streak is sterk!” terwijl iemand die minder actief is misschien juist geholpen is met: “Even 5 minuten oefenen vandaag?”.

- **Stuur niet te veel meldingen.**  
  Te vaak gestoord worden werkt irritant. Dan is de kans groot dat mensen de meldingen uitzetten of zelfs stoppen met de app gebruiken. 1 goede melding per dag is vaak genoeg.

##### Voorbeelden van motiverende push-notificaties:

- *“Je bent al 3 dagen op rij actief – hou dit vol!”*
- *“Klaar voor je volgende oefening? Je bent er bijna!”*
- *“Je dagdoel is nog niet gehaald. 5 minuutjes is genoeg!”*


##### Samenvatting

Door meldingen aan te passen aan het gedrag en de voorkeuren van de gebruiker, kunnen ze  helpen om mensen gemotiveerd te houden.

#### 3.2 In-app meldingen

In-app meldingen zijn berichten die je ziet terwijl je de app aan het gebruiken bent.
Ze verschijnen bijvoorbeeld bovenaan je scherm of in een pop-up zodra je een bepaalde actie uitvoert in de app. 
In tegenstelling tot push-notificaties in 3.1, helpen in app meldingen om je te motiveren **op het moment zelf**, terwijl je aan het leren bent.

Deze meldingen zijn vaak kort, positief en gericht op het motiveren van de gebruiker. 
Ze kunnen net dat extra zetje geven om nog even door te gaan of om een nieuw doel te halen.

##### Waarom in-app meldingen werken:

- Ze geven **directe feedback** tijdens het leren.
- Ze kunnen helpen om een gebruiker te begeleiden.
- Helpt het gevoel van voortgang en beloning.
- Ze zorgen voor een positieve sfeer in de app en maken het leerproces motiverend.

##### Voorbeelden van in-app meldingen:

- *“Nog 1 oefening en je hebt een nieuwe badge!”*
- *“Je doet het goed – blijf zo doorgaan!”*
- *“Je hebt zojuist 5 oefeningen afgerond!”*



##### Samenvatting

In-app meldingen zijn een handig middel om gebruikers tijdens het leren te motiveren, te begeleiden en te belonen. 
Door ze goed in te zetten op het juiste moment, kun je zorgen voor een positieve leerervaring, zodat gebruikers net wat langer blijven oefenen.


#### 3.3 E-mails

E-mails zijn handig om iets uitgebreider te communiceren. 
Volgens Campaign Monitor openen veel mensen nog steeds e-mails, vooral als ze nuttig en persoonlijk zijn.

**Soorten e-mails:**

- Wekelijkse voortgangsrapportjes.
- Tips die passen bij het leerdoel van de gebruiker.
- Een herinnering als iemand even niets heeft gedaan.

---

### 4. Samen leren met anderen

Leren wordt leuker als je het samen doet. 
Volgens Vygotsky leren mensen beter in een sociale omgeving. 
Ook EdTech Review zegt dat gebruikers vaker terugkomen als ze samen kunnen werken.

**Voorbeelden in de app:**

- Samen leren met een maatje.
- Challenges met groepen (bijv. wie leert het meest deze week?).
- Je resultaten kunnen delen.

---

### 5. Testen wat werkt

Wat de ene persoon motiveert, werkt misschien helemaal niet voor iemand anders. 
Sommige mensen houden van uitdagingen en willen in een leaderboard staan, terwijl anderen liever rustig op hun eigen tempo leren. 
Daarom is het belangrijk dat een leerapp flexibel is en verschillende soorten gebruikers ondersteunt.

Om erachter te komen wat het beste werkt, kun je gebruik maken van testen, zoals **A/B-testen**. 
Hierbij test je twee of meerdere varianten van iets om te zien welke beter werkt. 
Zo ontdek je wat het meeste effect heeft op de motivatie van gebruikers.

##### Voorbeeld A/B-test:

- **Groep A** krijgt elke ochtend om 9:00 uur een herinnering om te oefenen.
- **Groep B** krijgt dezelfde herinnering, maar dan ’s avonds om 20:00 uur.
- Daarna kijk je in de statistieken welke groep vaker terugkomt in de app.

Als blijkt dat groep B (de avondgroep) vaker terugkomt, dan kun je kiezen om standaard ’s avonds meldingen te sturen.

Door dit soort testen uit te voeren, kun je de app steeds slimmer maken en aanpassen op wat het beste werkt voor verschillende mensen. Dit zorgt ervoor dat meer gebruikers gemotiveerd blijven en de app vaker blijven gebruiken.

---

### Conclusie

Gebruikers gemotiveerd houden is belangrijk voor het succes van een leerapp. Je kunt dit doen met leuke elementen zoals badges en punten, maar ook met meldingen, doelen, sociale functies en e-mails. Het is belangrijk om goed te kijken wat bij de doelgroep past, en daar op in te spelen.

Door meldingen op de juiste manier te gebruiken, en de app persoonlijk te maken, zorg je ervoor dat gebruikers blijven terugkomen en dat ze echt iets leren.

-  Conclusie moet nog aangepast worden gebaseerd op onze leerapp, nu is het nog aleen vaag en heel algemeen.
---

### Bronnenlijst 

- Clark, R. C., & Mayer, R. E. (2016). *E-learning and the science of instruction: Proven guidelines for consumers and designers of multimedia learning* (4e ed.). Wiley.

- Deci, E. L., & Ryan, R. M. (2000). The “what” and “why” of goal pursuits: Human needs and the self-determination of behavior. *Psychological Inquiry, 11*(4), 227–268. https://doi.org/10.1207/S15327965PLI1104_01

- Hamari, J., Koivisto, J., & Sarsa, H. (2014). Does gamification work? – A literature review of empirical studies on gamification. In *Proceedings of the 47th Hawaii International Conference on System Sciences* (pp. 3025–3034). IEEE. https://doi.org/10.1109/HICSS.2014.377

- Vygotsky, L. S. (1978). *Mind in society: The development of higher psychological processes*. Geraadpleegd van  https://eenmeesterinleren.nl/zone-van-naaste-ontwikkeling-van-lev-vygotsky/#:~:text=Vygotsky%20stelde%20dat%20leren%20een,ontwikkelen%20van%20kennis%20en%20begrip.

- Campaign Monitor. (2021). *The ultimate email marketing benchmarks for 2021*. Geraadpleegd van https://www.campaignmonitor.com/resources/guides/email-marketing-benchmarks/

- Localytics. (2018). *Push notification benchmark report*. Geraadpleegd van https://info.localytics.com/blog/push-notification-benchmarks

- Digital Promise. (2016). *Learning in the 21st century: The future of learning*. Geraadpleegd van https://digitalpromise.org

- EdTech Review. (2020). *Social learning in EdTech: Driving engagement and outcomes*. Geraadpleegd van https://edtechreview.in

- frankwatching (2019). *Zo start je met A/B-testen beginners guide*. Geraadpleegd van https://www.frankwatching.com/archive/2019/06/07/ab-testen-beginners-guide/

---

## Efficiënt/effectief Leerplatform Kenmerken

### Theoretisch kader

Onze website moet voldoen aan een paar eisen en wensen die we hebben
meegekregen van de opdrachtgever. Dit noemen wij elementen en
componenten. Dit zou je kunnen zien als stukjes op iedere webpagina die
ieder zijn eigen functionaliteit heeft en ook kan samenwerken met andere
componenten of elementen, zodat het op deze manier een goede
samenhangende webpagina wordt.

---

### De opdracht

Ik heb in de research story die we hebben gemaakt een aantal punten
opgesteld die voldaan moeten zijn voordat we kunnen beginnen aan de
opdracht (DoR). Ook heb ik punten opgesteld die voldaan moeten zijn om
de story correct af te ronden (DoD).

Later heb ik drie taken gemaakt waarin ik onderzoeken ga doen over welke
elementen het beste op de webpagina kunnen komen.

Zoals ik in het theoretisch kader al een beetje beschreef is het dus de
opdracht van de research story om na te gaan wat de beste elementen zijn
voor op elke webpagina. Wij zijn meerdere keren in gesprek geweest met
onze opdrachtgever om te kijken wat hem het beste leek om erin te
hebben.

---

### Het onderzoek

Nadat we een paar keer in gesprek zijn geweest met onze opdrachtgever,
hebben we een aantal ideeën gekregen, bijvoorbeeld dat een leaderboard
heel handig was om het een beetje competitief te maken. Dus op deze
manier is ons onderzoek eigenlijk een beetje begonnen, we hebben goed
geluisterd naar de opdrachtgever en ook zijn we een paar keer alleen met
het team in gesprek geweest zonder opdrachtgever, om te kijken of hier
nog nieuwe dingen uit komen.

Ook hebben we gebruik gemaakt van diverse zoekmachines die we van de HU
konden gebruiken, zoals HUGO en Google Scholar. Hier zijn uitsluitend
gecontroleerde wetenschappelijke rapporten/onderzoeken te vinden, daar
kunnen we dus handige informatie vandaan halen.

Onze opdrachtgever had al snel gezegd dat we iets van een applicatie
moeten maken dat lijkt op DuoLingo, dus dat konden we ook als
vergelijkingsmateriaal gebruiken.

Later heb ik ook DuoLingo rapporten opgezocht in de HUGO zoekmachine en
kwam ik wel op een interessant document: Online library (zie
bronnenlijst)

De bovenstaande link leidt naar een wetenschappelijk onderzoek. In
hoofdstuk 2.2 is er onderzoek gedaan naar hoe effectief het is om te
leren op een commercieel online platform. In de tekst staat ook dat er
sowieso geen nadeel is aan het online leren in vergelijking met een
standaard klaslokaal en dat het waarschijnlijk zelfs nog beter en
sneller gaat online.

Op GitHub heb ik de taken staan waar ik als comment de punten heb
opgeschreven die handig zijn om op de webpagina te hebben. Dit zijn de
drie taken:

<https://github.com/KasperMeijer/TODSS-DrieVakantiesNodig/issues/55>

<https://github.com/KasperMeijer/TODSS-DrieVakantiesNodig/issues/56>

<https://github.com/KasperMeijer/TODSS-DrieVakantiesNodig/issues/57>

---

### Conclusie

Uiteindelijk zijn we op de volgende kern-elementen gekomen die op het
leerplatform moeten komen:

- Leaderboard (te zien voor studenten en docenten, maar hoort bij één
  student).

- Docent moet vak kunnen aanmaken.

- Docent moet hoofdstuk kunnen aanmaken.

- Docent moet vragen kunnen toevoegen aan een hoofdstuk.

- Student moet alle vakken kunnen zien en door de vakken kunnen
  scrollen.

- Student kan alleen vragen op volgorde maken, niet door elkaar heen.

- Student moet om hints kunnen vragen, elke hint kost punten.

- Student voortgang per vak kunnen zien op het dashboard.

- Student moet zijn eigen docent kunnen zien, zodat die te bereiken is.

Ook zijn we gekomen op een paar elementen die we niet kunnen gebruiken:

- Feedback van de vragen aan het eind van de ronde geven (feedback moet
  direct na elke vraag gegeven worden).

- Finale ronde met chatbot voor elk hoofdstuk (Dit zouden we wel kunnen
  doen, maar echt alleen als we tijd over hebben).

---

### Bronnenlijst

Jiang, X., Rollinson, J., Plonsky, L., Gustafson, E., & Pajak, B.
(2021b). Evaluating the reading and listening outcomes of
beginning‐level Duolingo courses. *Foreign Language Annals*, *54*(4),
974--1002. <https://doi.org/10.1111/flan.12600>

*GitHub · Build and ship software on a single, collaborative platform*.
(2025). GitHub. <https://github.com/>

Online library - **Evaluating the reading and listening outcomes of
beginning-level Duolingo courses -geraadpleegd van:**
<https://onlinelibrary-wiley-com.hu.idm.oclc.org/doi/full/10.1111/flan.12600?sid=worldcat.org>

---

## Geschikte Databasetaal

Wordt aan gewerkt.
