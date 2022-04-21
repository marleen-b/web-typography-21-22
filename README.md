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
-  

Ik ben uiteindelijk gegaan voor het systeemfont. Ik kan namelijk soms moeilijk de knoop doorhaken, waardoor het heel lastig zou worden om een keuze te maken tussen alle font mogelijkheden. 





### De captions

De captions staan in de html, in het bestand index.html. Je kan aan elke paragraaf eventueel een of meer classes toevoegen. Bijvoorbeeld `voice1` of `voice2 soft`. Classes voeg je handmatig toe in de html.

Met JavaScript worden er een paar dingen extra gedaan: 

- er wordt aan elke paragraaf een unieke class toegevoegd (`p0`, `p1`, etc)
- Elk woord wordt in een aparte `span` gezet. Hierdoor kan je elk woord apart stylen, en eventueel ook [na elkaar laten verschijnen](https://github.com/cmda-minor-vid/web-typography-18-19/blob/master/closed-captions/css.css#L41).

### Tijdens het afspelen

Tijdens het afspelen wordt er een class `on` op de caption gezet als hij moet verschijnen, en een class `off` als hij klaar is. *Zowel class `on` als class `off` blijft op de caption staan!*

De timimg van de captions kan je aanpassen in [closed-captions/captions.js](closed-captions/captions.js).

Er verschijnen ook classes op de body op momenten dat er geluiden worden afgespeeld, zoals `sound1` en `sound2`. Je kan geluiden toevoegen in [closed-captions/sounds.js](closed-captions/sounds.js).

*let op,* de geluiden zijn niet compleet, dit zal je zelf moeten aanvullen.
