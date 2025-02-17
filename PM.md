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

### Player

Playern i detta spel gör inte så jätte mycket, fungerar typ bara som en kollisions check för att se ifall man ska ta skada från nissarna. Spelaren kan inte röra på sig eller något sådant. Allting jag har gjort med spelaren är egentligen bara att skapa den och ge den en sprite. 

![Bild på spelet](screenshot.png)

## Positiva erfarenheter




Här beskriver du vad som har gått bra i ditt projekt och analyserar varför. Hur ska du upprepa framgångarna.

## Negativa erfarenheter

Här beskriver du det som du anser har gått mindre bra med ditt projekt och analyserar hur du kan undvika detta i framtida projekt.

## Sammanfattning

Här redovisar du dina slutsatser, erfarenheter och lärdomar. Reflektera över din produkt och dess/dina utvecklingsmöjligheter.
Vad kan vidareutvecklas och finns det utrymme att bygga vidare på projektet.