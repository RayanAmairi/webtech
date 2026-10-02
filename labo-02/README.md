# Labo 2 - reflecties

Naam: Rayan Amairi

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: de drie links in de navigatie in de header
- b. `article > p`: de vier paragrafen die rechtstreeks in de article staan
- c. `.uren li:nth-child(3)`: het derde item in de lijst met openingsuren
- d. `h2 ~ p`: elke paragraaf die na de h2 is
- e. `.rassen li:first-child`: het eerste li van elke lijst

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 | groen | herkomst: mijn regel wint van de standaardstijl van de browser | groen | ja |
| 2 | blauw | volgorde: zelfde specificiteit, de laatste regel wint | blauw | ja |
| 3 | rood | specificiteit: een class wint van een element | rood | ja |
| 4 | rood | iets anders: `.v4 > a` raakt niets, want de a is geen direct kind van .v4 | rood | ja |
| 5 | blauw | specificiteit: een id wint van drie classes | blauw | ja |
| 6 | blauw | overerving: een regel die direct op het element staat, wint van een geërfde waarde | blauw | ja |
| 7 | rood | overerving: de blockquote erft de kleur van .v7 | rood | ja |
| 8 | blauw | specificiteit: het style-attribuut wint van elke selector | blauw | ja |
| 9 | rood | herkomst: `!important` wint van de gewone regel | rood | ja |
| 10 | groen | iets anders: de puntkomma na 1.5rem ontbreekt, dus die declaratie is ongeldig en wordt genegeerd | groen, lettergrootte blijft normaal | ja |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
Alles juist. Vraag 10 duurde het langst

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
 Voor de links in de navigatie koos ik nav a een class kon niet want ik mocht de HTML niet wijzigen 
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
de lettergrote van de letters ik moest ze vergelijken met de screenshot

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
Een achtergrondkleur een tekstkleur en een accentkleur zodat alles leesbaar is en alleen de navigatie opvalt.
- Wat verandert er in je site als je één token wijzigt?
Alles wat dat token gebruikt verandert tegelijk op alle vier de pagina s.

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. Het tokenblok bevat alleen kleuren. Georgia en de regelhoogte staan letterlijk in `body` (2.9).
2. De lettertypes zijn omgedraaid: tekst in Georgia, terwijl koppen Georgia en tekst Verdana moeten zijn (2.6).
3. Er staan dingen in die niet in het screenshot zitten: breedtes, marges, padding, randen, flexbox en een mediaquery (hoofdstuk 3).
4. De basismaat is 1.125rem en er staan maten zoals 1.3rem en 0.95rem, geen veelvouden van 0,25rem (2.8).
5. Het ziet er anders uit dan het screenshot: h1 in hoofdletters, gecentreerde header, vette prijzen in plaats van cursief en gedempt (2.1).