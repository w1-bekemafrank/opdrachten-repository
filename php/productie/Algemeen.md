# 0. Inleiding

## 0.1 De studieroute 

* Indeling
* De studieroutesite
* [Theorie overzicht](https://docs.google.com/presentation/d/1YyCH0ILOnx2i7GqfKxVWiofecFtXBkOagwoCEdVxaPQ/edit?usp=sharing)
* Opdrachten
* Huiswerk & voortgangsdocument
* Software (__Webmatrix__)

### 0.1.1 Opleverdata
De uiterste opleverdatums per opdracht worden in de klas gecommuniceerd. Zet de opdrachten met opleverdatums in je OUTLOOK Agenda.

### 0.1.2 Opleveren opdrachten

De opdrachten worden beoordeeld met een waardering van 0, 1 of 2.

<table><thead>
<tr>
<th></th>
<th align="left">Redenatie</th>
</tr>
</thead><tbody>
<tr>
<td>0</td>
<td align="left">Niet ingeleverd,<br>of opdracht onvoldoende uitgevoerd</td>
</tr>
<tr>
<td>1</td>
<td align="left">Te laat ingeleverd, maar wel goed uitgewerkt,<br>of opdracht matig uitgevoerd en opdracht op tijd ingeleverd.</td>
</tr>
<tr>
<td>2</td>
<td align="left">Opdracht goed en op tijd ingeleverd.</td>
</tr>
</tbody></table>

Als je te laat bent met opleveren dan krijg je dus niet de volledige waardering en heeft dit invloed op het uiteindelijke resultaat, waardoor het eindcijfer lager uit zal vallen.

Als je klaar bent met de opdrachten en de docent heeft het volgende onderwerp nog niet behandeld, dan overleg je met de docent wat je kunt gaan doen.

## 0.2 Inleiding programmeren en PHP

* Wat is programmeren?
* Is programmeren moeilijk? 
   * [![Is programmeren moeilijk?](http://img.youtube.com/vi/pvAsqPbz9Ro/0.jpg)](http://www.youtube.com/watch?v=pvAsqPbz9Ro)
* Hoe programmeer je voor het web?
* Hoe werkt het web?
* [Wat is PHP?](http://www.html-site.nl/wat-is-php/)
* Wat kun je met PHP?
* Welke voorkennis heb je nodig?
* Hoe leer je het best programmeren/PHP?
* Kun je het ook zelf online leren?
    - [zelfstudie met codecademy](https://www.codecademy.com/learn/php)
    - [mini cursus php w3schools](http://www.w3schools.com/php/)
    - [complete naslag php](http://php.net)
    - [youtube bijvoorbeeld thenewboston](https://www.youtube.com/watch?v=iCUV3iv9xOs&list=PL442FA2C127377F07)
* Wanneer gebruik je PHP?
* [Hoeveel sites gebruiken php](http://php.net/usage.php)
* [En hoeveel is dat procentueel?](https://w3techs.com/technologies/overview/programming_language/all)


## 0.3 Installeren webmatrix

[Downloaden webmatrix](https://www.microsoft.com/web/webmatrix/wmx3features.aspx)

[![Installatievideo webmatrix](http://img.youtube.com/vi/W02JcPdWjXU/0.jpg)](http://www.youtube.com/watch?v=W02JcPdWjXU)


* Hoe begin je met PHP?
Dit is je eerste php coderegel:

```php
<?php
   echo "Hallo wereld";
?>
```



---
## 0.4 Opdracht 00
Je hebt opdracht 0 af wanneer je de volgende dingen hebt gedaan:
* Je hebt webmatrix gedownload en geinstalleerd
* Je hebt een nieuwe php site gemaakt met de naam 'phpsemester1'
* Je hebt een map met de naam opdracht00 gemaakt
* In deze map heb je een php script aangemaakt met de naam helloworld.php
* Je hebt de bovenstaande code ingetypt
* Je hebt dit script in de browser gelanceerd (op bestand staan en rechtermuis klikken) en er treden geen foutmeldingen op
* Voeg ook je naam toe aan de zin en zet er ook bij in welke stad je woont en of je al eerder in php geprogrammeerd hebt of juist niet.
* Test ook dit script en zorg ervoor dat er geen foutmeldingen optreden en dat de regel netjes in de browser wordt getoond.
* Je hebt de map phpsemester1 met inhoud in een rar bestand gecomprimeerd en geupload naar je portfolio (studieroute php)
* Als de docent het heeft gezien en vind dat je je aan de opdracht hebt gehouden wordt de opdracht voor je afgetekend.


## 0.5 Debuggen en foutmeldingen

> Als er nog syntax-fouten in je PHP code zitten zal bij het runnen van je code een lege witte pagina worden getoond. Als je de php foutmelding wilt zien zodat je sneller je syntax kan herstellen, doe dan het volgende:

> Ga naar:
C:\Program Files\IIS Express\PHP\v5.3
> Het laatste onderdeel van de directory is afhankelijk van de PHP versie die in de IIS express is geïnstalleerd. Controleer dit in je site settings in webmatrix.
> Hernoem php.ini naar php.ini-backup en hernoem php.ini-development naar php.ini 

Als je bijvoorbeeld een ; aan het eind van een statement vergeet zie je nu bijvoorbeeld het volgende:

> **Parse error: syntax error, unexpected T_PRINT in C:\Users\Administrator\Documents\My Web Sites\phpsemester2\hoofdstuk1\opdracht0010.php on line 20**


## 0.6 Commentaar in je programmacode

Wen jezelf aan om je code te becommentarieren. In PHP doe je dat op de volgende manieren:
~~~php
//Manier 1 is met de dubbele // 
echo "Hello";

/* Manier 2 is wanneer je commentaar over meerdere regels gaat

Pas op deze regel stopt het commentaar*/

echo "Dag";

Als je code geen commentaar bevat zal je opdracht niet worden goedgekeurd (vanaf het moment dat het in de klas behandeld is).
~~~
#### [setSubMenuHeader]