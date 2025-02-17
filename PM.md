# Titel

Axel Jakobsson - 17 Februari 2025

## Inledning

I denna uppgift fick vi grafiker från estet klassen och har gjort ett spel som använder dem. Syftet med detta arbete var att lära sig om objekt orienterad programmer och hur det kan se ut. 

I arbetet så började vi med en bas som vi fick av läraren. Där ingick saker såsom sprite inläsning osv, ett canvas setup osv. 

## Bakgrund

### Fiender

En sak som var väldigt viktigt för spelet var fienderna för annars hade man inte behövt göra någonting. Sättet som jag spawnar in fienderna på är väldigt enkelt då koden kollar ifall Math.Random är mindre än 0.01 varje tick. 
<br>Alltså 1% chans att spawna en fiende och det körs 60 gånger per sekund. Sedan körs det också en check som kollar vart fienden ska spawna. 40% chans att spawna höger, 40% chans att spawna vänster och 20% chans att inte spawna alls.
<br>När fienderna väl har spawnat in så har jag ett check som bestämmer åt vilket håll dem ska gå.
<br>

### Combat

Combat systemet i detta spel är väldigt simpelt då man får tre olika knappar som man ska klicka på för att döda den närmaste nissen. Jag gör detta genom att generera tre knappar och kollar sedan efter korrekt input i ordningen som det ska komma. Ifall man trycker på fel knapp så får man en "time out" period där man inte kan trycka på några knappar och knapparna kommer troligen bytas eftersom dem byts automatiskt efter fem sekunder. 

I början hade jag tänkt mig att mitt combat system skulle vara mycket mer utvecklat fast det blev inte så på grund av hur svårt det hade varit för mig att implementera. 

### Player

Playern i detta spel gör inte så jätte mycket, fungerar typ bara som en kollisions check för att se ifall man ska ta skada från nissarna. Spelaren kan inte röra på sig eller något sådant. Allting jag har gjort med spelaren är egentligen bara att skapa den och ge den en sprite. 

![Bild på spelet](screenshot.png)

## Positiva erfarenheter

Jag tycker att spelet har gått fram i rätt bra takt förutom i vissa moment (negativa erfarenheter) och spelet fungerar nästan hur jag hade tänkt mig. Combat systemet är lite buggigt med inputsen eftersom jag viste inte riktigt hur jag skulle mitt problem att när man höll ner en knapp eller bara tryckte så räknades det som flera inputs. Jag fixade det genom att jag lade till någon sorts input delay mellan knapp trycken så att det inte räknades som flera ifall man bara klickade.

Det var lite trögt i början att förstå hur objekt orienterade programmering fungerade och sådant men det gick till slut att förstå lite grann i alla fall.

## Negativa erfarenheter

Det var en del saker som hindrade framgången av spelet. Till exempel så hade jag väldigt svårt att förstå mig av spritesen och animationerna och hur man skulle animera dem med frame height, frame width, frame x osv. Någonting som också tog ett tag var inputten i combat systemet som jag nämnde i de positiva erfarenheterna. 

Jag vet inte riktigt hur jag ska helt undvika liknande problem i framtiden då man kommer alltid stöta på saker som man inte kan lösningen på sedan i början. Dock så kommer nog det som jag hade problem med i detta projekt inte vara något stort problem i senare projekt då jag nu har lärt mig grunden om animationerna, hade nog gått att göra ett bättre system för inputten men jag var lite osäker och det nuvarande fungerar rätt så bra 

## Sammanfattning

I detta projekt har jag lärt mig att vissa saker som man kanske tänker är rätt snabba att implementera kan ta väldigt lång tid på grund av att man inte riktigt förstår hur vissa saker fungerar. I gruppens plan så skulle spelet vara på en mycket större skala med olika banor, en shop, nissarna hade gjort ett coolt hopp på en som blir slow motion när dem kommer nära spelaren osv. 

Spelet hade kunnat utvecklats lite mer med fler animationer när man gör vissa saker, såsom att döda nissarna. Spelet saknar rätt mycket "juice".




Här redovisar du dina slutsatser, erfarenheter och lärdomar. Reflektera över din produkt och dess/dina utvecklingsmöjligheter.
Vad kan vidareutvecklas och finns det utrymme att bygga vidare på projektet.