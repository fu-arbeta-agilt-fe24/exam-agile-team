# Yum Yum Gimmie Sum

🍔 Uppdrag: Rädda Yum Yum Gimmie Sum! 🌮
Yum Yum Gimmie Sum är den hetaste foodtruckkedjan i stan – deras burritos är legendariska, deras ramen får folk att gråta av lycka, och deras smash burgers har fått Michelin-inspektörer att skriva poesi. Men nu är katastrofen nära! 🚨

Foodtruckarna rullar, men affärerna haltar. Kunderna älskar maten, men kön är lång, beställningar tappas bort, och ingen vet var nästa truck dyker upp. Kedjan behöver en digital lösning – och det snabbt!

🌟 Uppdraget
Ni har blivit inkallade som det agila utvecklingsteamet som ska rädda Yum Yum Gimmie Sum från kaos. Ert mål: att skapa en webbapp som gör det enklare för kunder att hitta, beställa och njuta av maten.

💡 Era nyckelutmaningar:
🔹 Lösa kundens problem: Vad behöver foodtruckens gäster mest?
🔹 Bygga en MVP: Vilka funktioner är viktigast från start?
🔹 Arbeta agilt: Sprintar, iterationer och kundfeedback kommer vara nyckeln!

🚀 Sätt på er utvecklarmössorna, rulla ut whiteboarden och börja brainstorma – Yum Yum Gimmie Sum:s framtid ligger i era händer!

## Instruktioner

Ni kommer under de kommande två veckorna att ta er an utvecklingsprojektet som beskrivs i sin korthet ovan. Projekterandet kommer att utföras i två st sprintar á en veckan vardera, med start nu på fredag (den 7/3). Genom hela projektets gång skall ni följa de olika ritualerna i Scrumprocessen som vi pratat om i klassrummet (Sprint Planning, Daily Scrum, Sprint Review och Sprint Retrospective). Fram tills projektstart ha ni dock lite arbete framför er: designen är bara delvis färdig, och produktägarens user stories behöver gås igenom, utvärderas, och rangordnas efter mest "prisvärda" feature i er Product Backlog INNAN fredag. Fredag morgon vill jag att ni pingar mig i handledningskanalen på Discord för en snabb koll så att ni är på banan, innan ni få starta igång och börja bygga applikationen.

Under projektets gång kommer ni att ha inte mindre än 13 st arbetsmöten. Under dessa möten, där ni följer de riktlinjer som vi gått igenom i klassrummet för varje möte, kommer ni att dokumentera vad ni pratar om, vilka beslut som tas, samt vilka som deltagit under mötet (närvaro krav kommer finnas för att nå godkänt betyg). Lathundar för dessa mötesprotokoll hittar ni i mappen [protokoll]('./protokoll) ovan. Varje enskilt protokoll döps enligt formatet `[mötestyp]YYYYMMDD` exempelvis `planning20250310` eller `daily20250314` osv. Protokollen lägger ni sedan själva i en mapp med namnet "protokoll" i ert eget grupprepo.

I slutet av varje sprint (torsdageftermiddagar) kommer ni att ha en Sprint Review tillsammans med er Produktägare (Rachel) där ni visar upp det inkrement ni skapat under er arbetsvecka. Varje inkrement skall bestå av en produkt som fungerar, er MVP för veckan (någonting som kunden kan lansera redan samma dag om så önskas). Ert inkrement mergas till main-branschen, medans ni låter sådant som fortfarande buggar / ännu inte är 100 % implementerat ligga kvar i dev-branschen.

Glöm inte att lägga till era produktägare/handledare som collaborators både för ert repo, samt ert projekt på Github. *Santosnr6* och *rachel-zocom* för distansklassen, *Santosnr6* och *Jakob9916* för Karlstadgänget.

Till ert förfogande så har er produktägare redan varit så vänlig att tillgodose er med ett antal färdiga user stories. Tanken med dessa är att ni fram tills på fredag går igenom vad varje user story innebär, försöker sammanfatta vad ni behöver göra för att lösa varje user story, samt skriver acceptanskriterier för era user stories. Därefter utövar ni Agil Estimering för att i slutändan kunna rangordna era User Stories i er Product Backlog. Diskutera sedan vilka 10 User Stories ni vill sikta på att lösa under er första sprint, och flytta dessa till er Sprint Backlog. 

En viktig sak som jag vill trycka på här är kursmålet rörande *den psykologiska säkerhetens vikt i ett team*. Om ni fastnar på någonting så MÅSTE NI BE OM HJÄLP. En person som fastnar på en uppgift, inte får någonting gjort, ocg stannar upp gruppens progression för att man inte ber gruppen om hjälp kommer INTE få godkänt.

## Handledningar

I vanlig ordning taggar ni er handledare (mig Jakob eller Rachel) i handledningskanalen på Discord. DOCK är ni nu ett agilt utvecklingstem, så innan ni ber om handledning försöker ni lösa eventuella problem tillsammans först. Lyckas ni sedan inte lösa problemet så dyker HELA gruppen upp till handledningen. Era handledningstider hittar ni på tidslinjen på Azomo.

## Resurser

### Designskiss på Figma

Kunden har varit så vänlig nog att ge er ett par sidor med färdig design att utgå ifrån. Dessa [hittar ni här](https://www.figma.com/design/RdHOwEzElFGXdDUcDp0nkY/Yum-Yum-Gimme-sum---frontend?node-id=0-1&t=qCz0jAlnUKeHUIoG-1). Exportera skisserna till ett eget projekt där ni prototypar upp övriga sidor ni kommer behöva (ex startsida, om oss, navigationsmeny, formulär mm).

### Data

Ni hämtar produkterna genom att göra att fetch-anrop på följande url:

```
GET https://santosnr6.github.io/Data/yumyumproducts.json
```

Om ni vill så kan ni även hämta lite startanvändare genom att göra ett fetch-anrop på följande url:

```
https://santosnr6.github.io/Data/yumyumusers.json
```
