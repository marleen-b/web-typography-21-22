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

Ik ben uiteindelijk gegaan voor het systeemfont. Ik kan namelijk soms moeilijk de knoop doorhaken, waardoor het heel lastig zou worden om een keuze te maken tussen alle font mogelijkheden. Het systeemfont daagt mij ook meer uit om te kijken naar andere visuele mogelijkheden door CSS.


## Tone of voice
De opdracht draait om het geluid visueel weer te geven dus hoe geef je de pieptoon, alarm en de stemmen visueel weer.
Wat we horen moet je vormgeven en niet wat je ziet.

In de html zijn de captions verdeeld in classes zoals voice1 en voice2. Elk stukje tekst wordt door een bepaalde voice/stem gezegd.  
Wat mij opviel is dat de classes voor de tweede scene(is vanaf 1:27 in de video) nog ontbraken. Als je goed luister merk je dat elke voice zijn eigen unieke eigenschappen heeft. Hieronder heb ik dit kort op een rijtje gezet. Ook een aantal andere zaken die mij opvielen staan hieronder beschreven.

Voor het kiezen van de kleuren heb ik gebruik gemaakt van de volgende twee bronnen: 
https://londonimageinstitute.com/how-to-empower-yourself-with-color-psychology/
https://www.creativebloq.com/web-design/12-colours-and-emotions-they-evoke-61515112

### Voice 1:
De stem klinkt soms erg bazig door de snelle maar duidelijke uitspraak. Je moet luisteren wat ik te zeggen heb. Daarom heb ik ervoor gekozen om voice1 een groter font-size te geven dan voice2. Ik heb gekozen voor zwarte bold captions met een donkergrijze achtergrond. De kleur zwart wordt geassocieerd als 'Powerful'. Ik vond deze stem krachtig klinken dus vond ik bold tekst in de kleur zwart een goed idee. Om de tekst toch leesbaar te houden met de body achtergrondkleur heeft de tekst een donkergrijze kleur gekregen. 

### Voice 2: 
Deze voice klinkt erg eentonig, vaak weinig emotie. Klinkt wel als een menselijke stem en niet robotachtig. 
Maar de stem klinkt diep en eentonig ook door de vele herhalingen van zinnen. Daarom heb ik de captions van voice2 de kleur grijs gegeven. Grijs wordt namelijk als neutrale kleur gezien. En vaak vinden we eentonige stemmen heel saai en de kleur grijs is ook wel een beetje saai. 

### Voice 3:
Het is maar één zin: "Fuckoff Skinjob". De stem schreeuwt niet de tekst alsof iedereen het kan horen. Het klinkt als of degene van zich afbijt.
Bijna binnenmonds iemand van zich afbijten klinkt diep maar wel heel vlot gesproken. Op o.a. social media lezen we capital letters als schreeuwen. Doordat de tekst niet hardop wordt uitgeschreeuwd, maar wel heel erg gemeen klinkt heb ik ervoor gekozen om de tekst wel een capital letters te maken, maar met een kleiner font

### "Cells"
Ongeveer vanaf 34 seconden in de video hoor je een aantal keer "cells". Wat mij opvalt is dat dit woord een aantal keer herhaald wordt.
De eerste keer dat cells gezegd wordt het heel snel gezegd(> letter-spacing -2px). Daarna hoor je het voor de 2e keer. Wat een herhaling is van de eerste keer maar het klinkt een stukje langzamer.(> letter-spacing 5px) 

### Voice 4:
De vierde stem is heel kort te horen. De stem klinkt neutral maar beslist. Ik wilde voor elke voice minstens een andere kleur gebruiken, zodat er makkelijk onderscheid te maken is wie wat zegt. Omdat groen ook wel als stabiele kleur wordt gezien heb ik gekozen voor een donkere tint groen. Zo is de tekst stabiel, maar toch hard en beslissend als de zwarte kleur. 

### Voice 5: 
In de tweede scene worden er naar mijn mening andere stemmem gebruikt.Zo wordt voice 2 komt wel weer terug maar de andere stem klinkt heel anders. Daarom heb ik ervoor gekozen om dit voice5 te noemen. Ik heb gekozen voor een blauwe kleur en normal font-weight. De stem klinkt namelijk veel kalmer, zachter en vriendelijker dan voice1. Bij voice1 wordt alles heel snel gezegd. De tone of voice van voice5 is het tegenovergestelde van voice1. De captions hebben een blauwe kleur gekregen, omdat de kleur blauw staat voor vertrouwen. 


## Toelichting op de gemaakte visuele elementen in CSS.

0:00 - 
    Het schudden van de videoframe. Het komt voor mij toch echt binnen als ooeh nu gaat er wat spannends gebeuren nu moet je goed opletten als kijker. Om de aandacht te trekken koos ik voor een shake animatie. Ik hoorde ook een beetje wat trillends terug ik het geluid soort bzzzz opstijgend geluid.
    
0:09 - alarm geluid
    Vanaf 9 seconden hoor je een alarm geluid. Het deed mij heel erg denken aan een rood alarm zwaailicht, daarom heb gekozen voor een rode gradient achtergrondkleur

0:12 - 2e alarm geluid:
    Vanaf 12 seconden hoor je nog een alarm geluid. Alleen klinkt dit alarm anders dan de eerste. Het deed mij niet denken aan een zwaailicht, maar aan een soort van sirene. 

0:15 - buzzer
    Dit geluid klonk voor mij als bzzzzzzzzz. Het deed het mij een beetje denken aan het trillen van je telefoon, maar dan gedempter. Omdat het kort te horen is wilde ik het gebruiken als een overgang naar de warningstripes. Of te wel de waarschuwingsstrepen. 
    De geluiden van 0:15 lopen natuurlijk ook kort in elkaar over. 

0:16 - warningstripes
    Toen ik dit geluid voor het eerst hoorde deed het mij heel erg denken aan een warning alarm. Je mist alleen nog een stem die zegt:"warning, warning". Omdat we natuurlijk als vanaf 9 seconden een zwaailicht hadden gebruikt zat ik te denken wat doet mij nog meer denken aan waarschuwing. Een toen kwam ik op zwarte en gele of zwart orangje waarschuwingstrepen. Ik koos uiteindelijk voor de zwartorangje strepen, omdat de kleur geel net iets te fel was. 

0:24 - buzzer herhalign
    Mijn idee voor de irritante piep was om een noise effect toe te voegen aan de achtergrond zoals in dit voorbeeld: 
    Ik had ook wel gekeken naar andere methodes, maar deze begreep ik niet of was iets te ingewikkeld
https://www.youtube.com/watch?v=niEsB80l754  

1:15 - pieptoon stopt, knal van stilte
    Plotseling compleet witte achtergrond om de stilte te benadrukken. In games zoals Call of Duty wordt het scherm helemaal wit door de knal van een flashbang. De speler wordt hierdoor 'verblind' door de knal. In dit geval wordt de kijker 'verblind' door de knal van stilte. 
Op dit moment heb ik ook een clip-path gebruikt, omdat de zwarte balken van de video op dit moment heel erg storend waren. Door de zwarte balken weg te halen ontstaat er meer balans in de plotselinge stilte die je wilt visualiseren.

1:26 - mysterieuze soundwaves
    Het achtergrondgeluid vanaf 1:26 klonk voor mij heel erg mysterieus. Ik kreeg het gevoel dat er iets stond te gebeuren, maar wat dat weet je niet. Volgens de kleuren psychologie wordt staat de kleur paars voor mysterieus. Daarom leek het mij logisch om de kleur paars te gaan gebruiken. Ik wilde een soort van waves maken die zachtjes meebewegen met het geluid. Hoe groter hoe harder het geluid. En op het einde net zoals bij de irritante piep plotseling niks, niks van stilte. 

## Bronnen
Hieronder heb ik de bronnen genoteerd die ik geraadpleegd heb om een aantal elementen te maken in CSS.

Waarschuwingsstrepen
https://codepen.io/pigparlor/pen/wvMBPvO & https://stripesgenerator.com/ 

Shaking video frame
 https://www.w3schools.com/howto/howto_css_shake_image.asp

Noise effect
https://www.youtube.com/watch?v=niEsB80l754 

Ik had ook wel gekeken naar andere methodes, maar deze begreep ik niet of was iets te ingewikkeld
https://css-tricks.com/grainy-gradients/
https://www.youtube.com/watch?v=z1ES-oz4SbM 

Kleuren psychologie
https://londonimageinstitute.com/how-to-empower-yourself-with-color-psychology/
https://www.creativebloq.com/web-design/12-colours-and-emotions-they-evoke-61515112