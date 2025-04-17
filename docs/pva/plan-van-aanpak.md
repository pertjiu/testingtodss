# Plan van aanpak
- Datum	:	18/03/2025
- Versie	:	V1.3
- Auteurs	:	Damian, Soulaiman, Duncan, Jens, Kasper, Thomas

## Inhoud

- [Plan van Aanpak](#plan-van-aanpak)
    - [Revisiehistorie](#revisiehistorie)
    - [Inleiding](#inleiding)
    - [Organisatorische context](#organisatorische-context)
    - [De opdracht](#de-opdracht)
    - [Projectaanpak](#projectaanpak)
    - [Referenties](#referenties)

---

## Revisiehistorie

| Datum | Versie	| Omschrijving |
|-------|---------|--------------|
| 04/03/25	|  0.1 |	Initiële invulling bestand |
| 10/03/2025 |	1.1	| Document verder afgemaakt, hoofdstuk 3 is aardig af nu |
| 10/03/2025 |	1.2	| Spelfouten uit document gehaald |
| 12/03/2025 |	2.0	| Technieken toegevoegd bij de randvoorwaarden |

---

## Inleiding 

Het project voor Clinithink had als doel om zorgstudenten beter te leren klinisch redeneren. 
Het bedrijf heeft dit gedaan door een AI-Chatbot te ontwikkelen die hun helpt oefenen met virtuele patiënten. 
In dit document leggen we uit hoe we de Chatbot verder gaan uitwerken, hoe het aansluit bij de behoeften van studenten en de doelen van de school. 
We bespreken ook hoe het product is getest, wat de resultaten zijn en hoe het bijdraagt aan de kennis en vaardigheden van de studenten.

---

## Organisatorische context

### Wie is de klant?
Deze opdracht wordt uitgevoerd binnen de opleiding Fysiotherapie van de Hogeschool Utrecht (HU). De opleiding leidt studenten op tot fysiotherapeuten door middel van theorie en praktijk.

### Missie, visie en doelstelling van de klant
Hogeschool Utrecht heeft als missie "De HU wil een belangrijke bijdrage leveren aan de kwaliteit van (samen)leven in onze stedelijke omgeving.". De HU richt zich op het opleiden van studenten en wil dit zo innovatief en professioneel doen. Dat blijkt uit hun volgende visie, “de HU werkt aan innovatie en professionalisering van de beroepspraktijk en de ontwikkeling van talent”. 

### Organisatiestructuur
De opleiding Fysiotherapie valt onder de Faculteit Gezondheidszorg van de HU. Dit project is bedacht door docenten en wordt uitgevoerd met hulp van student -ontwikkelaars.

![image](https://github.com/user-attachments/assets/19b11c70-4ae2-45b2-9084-754af4991779)


### Betrokken Personen, Stakeholders
- Opdrachtgever: Sijmen Hacquebord - sijmen.hacquebord@hu.nl
- Gebruikers: Fysiotherapiestudenten en -docenten (De docenten leveren de casussen aan en studenten kunnen hier vervolgens mee oefenen)

### Taken van de Student binnen Project
De student werkt als ontwikkelaar in het project en helpt met:
- Het bouwen van een leerapplicatie met duolingo/spelachtige methodes.
- Hosting en onderhoud in Azure mogelijk maken en zorgen voor een goede overdracht
- Samenwerking met docenten en Fysio-Studenten
De student houdt nauw contact met de opdrachtgever door iedere week een korte meeting te houden met de opdrachtgever.

---

### De opdracht
Hoe kan gamification worden geïntegreerd in een bestaande webapplicatie om de betrokkenheid en leerervaring van studenten te verbeteren, geïnspireerd door het Duolingo-model?


### Afbakening
Binnen dit project richten we ons op twee hoofdcomponenten:
-	ontwikkelen van een leerplatform : We ontwikkelen een leerplatform geïnspireerd door Duolingo. Dit platform biedt gebruikers de mogelijkheid om op een interactieve en speelse manier nieuwe kennis op te doen.
-	Een portal ontwikkelen: Deze portal moeten studenten en docenten in staat stellen in te loggen. Docenten krijgen toegang tot extra functionaliteiten zoals het bekijken van studenteninformatie en het maken en doorsturen van vragen.
Voor het maken van de portal moeten we rekening houden met dat alles online via Azure draait en dat er onderscheid is tussen de inlog informatie van een docent en een student. Hierbij kan de docent informatie opvragen van de leerling en zelfs mogelijk vragen kan maken en door te kunnen sturen, dit is wel low priority de rest valt buiten scope. Dit kan wel nog veranderen mits de opdrachtgever dat zegt.
 
Binnen de scope:
- Ontwikkeling van een online dashboard met een onderscheid tussen student- en docentrollen.
- Implementatie van een veilige inlogomgeving, gehost via Azure.
- Docenten kunnen persoonsgegevens van studenten inzien en gesprekken lezen die de studenten voeren met de Chatbot. Zo kan de docent deze gebruiken tijdens de les.
- Geavanceerde analytics of feedbacksystemen voor studenten.


Buiten de scope:
- Het ontwikkelen van AI-modellen ( we houden dit theoretisch maar dit zou na het project eenvoudig uitgebreid kunnen worden met bestaande code.)
- Offlineversies of integratie met andere systemen buiten Azure.

### Randvoorwaarden
- Het systeem moet draaien op Azure Cloud.
- Er moet een duidelijke scheiding zijn tussen de rechten en functionaliteiten van docenten en studenten.
- Het project moet voldoen aan de AVG/GDPR-wetgeving betreffende studentgegevens.
- De lay-out van het dashboard moet gebruiksvriendelijk en toegankelijk zijn.
- De opdrachtgever kan aanvullende functionele eisen stellen tijdens de ontwikkeling.
- Java 21
- npm (komt mee met Node.js)
- Git (voor versiebeheer)
- Microsoft Visual Studio (voor backend-debugging)
- Visual studio code (voor frontend-ontwikkeling)

### Risico’s
Omdat we volledig vanaf nul beginnen, brengt dit extra tijd en ontwikkelingswerk met zich mee. We moeten zorgvuldig de juiste technologieën kiezen om onderhoudsproblemen te voorkomen. Daarnaast is er het risico op ‘scope creep’, waarbij extra functies de planning vertragen. Ook moet er voldoende aandacht zijn voor testen en stabiliteit om een betrouwbaar platform te garanderen. Een strakke planning en regelmatige feedbackmomenten helpen deze risico’s te beperken.

### Op te leveren eindresultaat
Het eindresultaat zal bestaan uit een backend en een frontend. De applicatie draait op de Azure-cloudomgeving en biedt studenten en docenten de mogelijkheid om in te loggen. Studenten kunnen oefenen met het omgaan met patiënten, terwijl docenten inzicht krijgen in de beantwoorde vragen en de voortgang van studenten. Hoewel AI-modellen en chatbots theoretisch onderdeel van het concept blijven, worden deze in de huidige oplevering niet geïmplementeerd.

### Relaties met andere projecten
Dit project raakt aan:
- Digitale hulpmiddelen voor klinisch redeneren: Het leerplatform ondersteunt studenten bij het ontwikkelen van hun vaardigheden.
- Gamificatieprojecten binnen de opleiding: ontwikkeling naar een Duolingo-achtig systeem voor fysiotherapie (en andere vergelijkbare opleidingen in de toekomst) .
- Azure-integratieprojecten: Eventueel nieuwe cloud omgeving nodig.

Bijdrage aan SDG’s Dit project sluit aan bij de Sustainable Development Goals (SDG’s) van de Verenigde Naties:
- SDG 3: Goede gezondheid en welzijn → Het helpt studenten beter klinisch te redeneren, wat leidt tot betere patiëntenzorg.
- SDG 4: Kwaliteitsonderwijs → Het biedt een digitale leeromgeving met verbeterde leerhulpmiddelen.


---

### Projectaanpak
Wij gaan dit project agile werken met scrum waarbij kasper van ons de scrum master is.
Elke dinsdagochtend 9u hebben wij een review.
Elke 2 weken een reviews en een planning.
Over app doen wij elke dag een daily standup.
Een retro aan het eind van elke sprint.


### Organisatie
Voor dit project werken we met behulp van de scrum methode, deze methode is fijn, omdat we met meerdere sprint werken van ieder een paar weken. 
Na afloop van elke sprint laten we als Review een deel van onze uitwerking zien aan de opdrachtgever/product owner, die dan hier vervolgens feedback op kan geven. 
Op deze manier kunnen we ons hele project opdelen in kleinere stukjes, zodat we meer overzicht creëren. De product owner is Sijmen Hacquebord.

Na afloop van elke sprint doen we ook een Retrospective. Dit gebeurt alleen met ons team en dus zonder opdrachtgever, in de Retrospective gaan we met z'n alle bespreken wat er goed ging en wat verbeterd kan worden. Hier heeft onze scrum master de leiding, dit is Kasper Meijer.

### Planning van de ceremonies
Planning op eerste maandag van de sprint tenzij de les op dinsdag valt.
De Sprint Review hebben we geplant op elke laatste week van de sprint, wanneer de opdrachtgever beschikbaar is.
De Sprint Retro plannen we op elke laatste lesdag van de sprint.

| Sprint |	Planning |	Review |	Retrospective |
|--------|-----------|---------|----------------|
| 0	- |	- |	- |
| 1 |	4-3-2025 |	In de week van 17-3-2025 |	21-3-2025 |
| 2 |	25-3-2025 |	In de week van 7-4-2025 | 11-4-2025 |
| 3 |	15-4-2025 |	In de week van 5-5-2025 | 9-5-2025 |
| 4 |	13-5-2025 |	In de week van 26-5-2025 | 30-5-2025 |
| 5 |	3-6-2025 |	In de week van 16-6-2025 | 20-6-2025 |
| 6 |	24-6-2025 |	In de week van 7-7-2025 | 11-7-2025 |

### Product backlog
Vanuit een vorig project kan het restant van de product backlog opgenomen worden. Als dit een nieuwe opdracht is wordt een initiële product backlog samengesteld met de opdrachtgever.

#### Learning stories
- Learning story (Thomas, Kasper): Als teamlid wil ik kennis maken met de programmeertaal C#, zodat ik goed de bestaande situatie kan begrijpen en verder kan maken.

#### Research stories
- Als team willen we kennis maken met de huidige applicatie, zodat we vanuit daar verder kunnen werken en een beter beeld kunnen krijgen van welke taken we moeten verrichten.
- Als team willen we de huidige situatie werkend krijgen op onze computers, zodat wij kunnen zien wat er precies gemaakt is en een beter beeld kunnen krijgen van hoe we dingen verder moeten doen.

---

## Referenties
[Hogeschool Utrecht. (z.d.). HU Visie | Hier komt alles samen | Hogeschool Utrecht](https://www.hu.nl/visie)

[Sprint Review Meeting | Scrumguide.nl. (2020, 16 april). Scrumguide](https://scrumguide.nl/sprint-review/)

