# FenixBox
Fenixbox är en enkel jQuery plugin för att förstora bilder.
##Requirements
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
```html
<script type="text/javascript">
	$(document).ready(function (){
	    $('.fenixbox').fenixBox();
	});
</script>
```

