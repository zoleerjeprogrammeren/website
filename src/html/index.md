# Html (HyperText Markup Language)

Deze tutorial leert je Html op een eenvoudig manier.<br>

- HTML is de standaard opmaaktaal voor het maken van webpagina's
- HTML beschrijft de structuur van een webpagina
- HTML bestaat uit een reeks elementen
- HTML-elementen vertellen de browser hoe de inhoud moet worden weergegeven
- HTML-elementen labelen stukjes inhoud zoals "dit is een kop", "dit is een alinea", "dit is een link", enz.
- HTML-elementen moeten worden weergegeven.

## Html Voorbeeld

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

## HTML Responsive Web Design

### What is Responsive Web Design:

Responsive webdesign gaat over het maken van webpagina's die er goed uitzien op alle apparaten!

Een responsive webdesign past zich automatisch aan verschillende schermformaten en viewports aan.
<img src=""></img>

### Het kijkvenster instellen:

Om een ​​responsieve website te maken, voegt u de volgende `meta`-tag toe aan al uw webpagina's:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

Hiermee wordt de viewport van uw pagina ingesteld, die de browser instructies geeft over hoe de afmetingen en schaal van de pagina te bepalen.

Hier is een voorbeeld van een webpagina zonder de viewport-metatag en dezelfde webpagina met de viewport-metatag

## Responsieve afbeeldingen

Responsieve afbeeldingen zijn afbeeldingen die mooi worden geschaald om in elke browsergrootte te passen.

## De breedte-eigenschap gebruiken

Als de CSS width-eigenschap is ingesteld op 100%, zal de afbeelding responsief zijn en omhoog en omlaag schalen:

```html
<img src="img_girl.jpg" style="width:100%;" />
```

## Responsieve tekstgrootte

De tekstgrootte kan worden ingesteld met een "vw"-eenheid, wat de "viewport-breedte" betekent.

Op die manier volgt de tekstgrootte de grootte van het browservenster:

```html
<h1 style="font-size:10vw">Hallo wereld</h1>
```

## Voorbeeld:

```html
<!DOCTYPE html>
<html>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link rel="stylesheet" href="https://www.zoleerjeprogrameren.com/html" />
  <lichaam>
    <div class="con-groen">
      <h1>Demo</h1>
      <p>Verklein deze responsieve pagina!</p>
    </div>

    <div class="row-padding">
      <div class="third">
        <h2>Londen</h2>
        <p>Londen is de hoofdstad van Engeland.</p>
        <p>
          Het is de dichtstbevolkte stad van het Verenigd Koninkrijk, met een
          grootstedelijk gebied van meer dan 13 miljoen inwoners.
        </p>
      </div>

      <div class="third">
        <h2>Parijs</h2>
        <p>Parijs is de hoofdstad van Frankrijk.</p>
        <p>
          De omgeving van Parijs is een van de grootste bevolkingscentra van Europa,
          met meer dan 12 miljoen inwoners.
        </p>
      </div>

      <div class="third">
        <h2>Tokio</h2>
        <p>Tokio is de hoofdstad van Japan.</p>
        <p>
          Het is het centrum van de Greater Tokyo Area, en de meest bevolkte
          grootstedelijk gebied ter wereld.
        </p>
      </div>
    </div>
  </body>
</html>
```

</body>
</html>
