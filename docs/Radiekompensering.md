# Radiekompensering G40, G41 och G42

Radiekompensering låter programmeraren använda detaljens geometri exakt som den är på ritningen för alla koordinater.  
Utan radiekompensering måste programmeraren alltid veta storlek på verktyget och kompensera de programmerade koordinaterna för geometrin med verktygets radie.  
I detta fall kommer detaljen inte att bearbetas korrekt om ett annat verktyg med en annan storlek används. En annan fördel med att använda radiekompensering är möjligheten att använda vilken verktygsstorlek man vill, så länge som verktygskompenseringen har matats in korrekt i verktygsbiblioteket.  
Det är också mycket effektivt för finjustering av färdiga dimensioner med mindre justeringar av kompenseringsvärdena i verktygsbiblioteket.

Funktionen G40 används för att avsluta, och G41 eller G42 används för att initiera radiekompensering. G40 ska programmeras efter att bearbetningen med kompensering är färdig. Detta görs genom att flytta bort verktyget från arbetsstycket i en linjär rörelse (G01) eller snabbtransport (G00) med en sträcka som minst motsvarar radien av verktyget. Försiktighet bör iakttas här eftersom om avslutet görs i ett block utan rörelse, kommer verktyget röra sig oförutsägbart i motsatt riktning och kan skada detaljen.

G40 = Avsluta Radiekompensering

G41 = Radiekompensering Vänster

G42 = Radiekompensering Höger

![enter image description here](https://lernia.itslearning.com/data/1821/C33240/Fr%C3%A4s/04-09-2014-1916794701.jpeg)
