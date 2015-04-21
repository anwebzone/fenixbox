# FenixBox
FenixBox är en simpel jQuery plugin för att förstora bilder.
##Krav
För att FenixBox ska fungera så behöver du först ladda ner och lägga till jQuery.

FenixBox är även beroende av Font-Awesome The iconic font and CSS toolkit.

##Ladda ner, installera och använda FenixBox

> git clone https://github.com/anwebzone/fenixbox.git

> Zip download https://github.com/anwebzone/fenixbox/archive/master.zip

###Installation
Se till att du har jQuery och Font-Awesome på den sida du tänkt använda pluginen på, annars kommer inte FenixBox att fungera som tänkt.

Lägg till fenixbox.css i sidans head alternativt kopiera css koden i fenixbox.css till en befintlig stylesheet.
```html
<link rel="stylesheet" type="text/css" href="fenixbox.css">
```

Lägg till fenixbox.js i sidans head direkt efter jQuery såhär:
```html
<script src="jquery.js"></script>
<script src="fenixbox.js"></script>
```

###Användning
Lägg till klassen "fenixbox" på den bild du vill att FenixBox ska förstora.

Du kan även om du vill lägga till en titel som visas när bilden förstoras.
```html
<img class="fenixbox" src="koenigsegg.jpg" alt="" title="Koenigsegg Agera R"/>
```

