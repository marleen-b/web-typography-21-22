# Web Typography, 2020/2021, opdrachtomschrijving

Als je doof bent, of als je om een andere reden geen geluid kunt horen, dan mis je veel informatie als je een film kijkt. Knisperende voetstappen, langzaam aanzwellende muziek, nerveus getik op een deur, je hoort het natuurlijk allemaal niet. Nu bestaat er zoiets als *closed caption*, wat een type ondertiteling is waarbij ook dingen als omgevingsgeluiden en de muziek beschreven worden. Hierdoor krijgt een kijker die informatie wel binnen.

Alleen wordt die auditieve informatie nogal neutraal beschreven. Het geluid van huilend persoon zou bijvoorbeeld beschreven kunnen worden als *snikgeluid op de achtergrond*. En iemand die lacht zou geschreven kunnen worden als *iemand lacht.* Heel neutraal, bijna zakelijk, en bovendien allebei in precies hetzelfde neutrale lettertype. Terwijl het toch echt over twee heel verschillende emoties gaat. 

Dat kan visueel sterker. 

En dat gaan jullie doen.

## Typografische restricties; mijn keuze.

Voor de opdracht moest ik één van de twee opties kiezen en onderbouwen. Voor de typografische restricties had ik de keuze uit systeemfont of Brenner.


### Optie 1; Systeemfont plus- en minpunten:
-   Het systeem bepaald het font.
-	Geen controle over welk lettertype er precies gebruikt wordt.
-	Alleen normal, bold en italic zijn er mogelijk als font-weight opties
-	Meer uitdaging in het gebruik font-size, text-decoration, color, letter-spacing, word-spacing, text-shadow en animatie. 

### Optie 2; Brenner plus-en minpunten:
-	Keuzestress over welke lettertype en variant je gaat gebruiken en voor welke voice of sound. 
-	De vele lettertypen kunnen de toon of voice beter overbrengen. 
-	Meer mogelijkheden dan met systeemfonts. 
-   Een uitgebreid keus uit een font familie. Zoals sans-serif, serif, bold, display en script.

Ik ben uiteindelijk gegaan voor het systeemfont. Ik kan namelijk soms moeilijk de knoop doorhaken, waardoor het heel lastig zou worden om een keuze te maken tussen alle font mogelijkheden. Het systeemfont daagt mij ook meer uit om te kijken naar andere visuele mogelijkheden. 


## Tone of voice
De opdracht draait om het geluid visueel weer te geven dus hoe geef je de pieptoon, alarm en de stemmen visueel weer.
Wat we horen moet je vormgeven en niet wat je ziet.

In de html zijn de captions verdeeld in classes zoals voice1 en voice2. Elk stukje tekst wordt door een bepaalde voice/stem gezegd.  
Wat mij opviel is dat de classes voor de tweede scene(is vanaf 1:27 in de video) nog ontbraken. Als je goed luister merk je dat elke voice zijn eigen unieke eigenschappen heeft. Hieronder heb ik voor mijzelf dit kort op een rijtje gezet. Ook een aantal andere zaken die mij opvielen staan hieronder beschreven.

### Voice 2: 
Deze voice klinkt erg eentonig, vaak weinig emotie. Klinkt wel als een menselijke stem en niet robotachtig. 
Maar de stem klinkt diep en eentonig ook door de vele herhalingen van zinnen. 

### Voice 3:
Het is maar één zin: "Fuckoff Skinjob". De stem schreeuwt niet de tekst alsof iedereen het kan horen. Het klinkt als of degene van zich afbijt.
Bijna binnenmonds iemand van zich afbijten klinkt diep maar wel heel vlot gesproken. 

### "Cells"
Ongeveer vanaf 34 seconden in de video hoor je een aantal keer "cells". Wat mij opvalt is dat dit woord een aantal keer herhaald wordt.
De eerste keer dat cells gezegd wordt het heel snel gezegd(> letter-spacing -2px). Daarna hoor je het voor de 2e keer. Wat een herhaling is van de eerste keer maar het klinkt een stukje langzamer.(> letter-spacing 5px) 

### Voice 5: 
In de tweede scene worden er naar mijn mening andere stemmem gebruikt.Zo wordt voice 2 komt wel weer terug maar de andere stem klinkt heel anders. Daarom heb ik ervoor gekozen om dit voice5 te noemen.





## Toelichting op de gemaakte visuele elementen in CSS.

- Waarom heb je gekozen voor italic/bold/ 20px voor bij voice1?
- Waarom wordt de background red op precies 13 seconden. 

- Vanaf 9 seconden hoor je een alarm geluid. Het deed mij heel erg denken aan een rood alarm zwaailicht, daarom heb gekozen voor een rode gradient achtergrondkleur


- Plotseling compleet witte achtergrond om de stilte te benadrukken. In games zoals Call of Duty wordt het scherm helemaal wit door de knal van een flashbang. De speler wordt hierdoor 'verblind' door de knal. In dit geval wordt de kijker 'verblind' door de knal van stilte. 
Op dit moment heb ik ook een clip-path gebruikt, omdat de zwarte balken van de video op dit moment heel erg storend waren. Door de zwarte balken weg te halen ontstaat er meer balans in de plotselinge stilte die je wilt visualiseren.

- Het schudden van de videoframe. Het komt voor mij toch echt binnen als ooeh nu gaat er wat spannends gebeuren nu moet je goed opletten als kijker. Om de aandacht te trekken koos ik voor een shake animatie. Ik hoorde ook een beetje wat trillends terug ik het geluid soort bzzzz opstijgend geluid.


## Bronnen

Shake animatie: https://www.w3schools.com/howto/howto_css_shake_image.asp 

Yellow Warning tape: https://codepen.io/pigparlor/pen/wvMBPvO & https://stripesgenerator.com/ 


Voor noise effect 
Ik had ook wel gekeken naar andere methodes, maar deze begreep ik niet of was iets te ingewikkeld

https://css-tricks.com/grainy-gradients/
https://www.youtube.com/watch?v=z1ES-oz4SbM 