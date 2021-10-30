<style>
.heatMap {
    width: 70%;
    text-align: center;
}
.heatMap th {
background: white;
color:Black;
word-wrap: break-word;
text-align: center;
}
.heatMap tr:nth-child(1) { background-color:#FF0000; color:white; }
.heatMap tr:nth-child(2) {background-color:#00FF00; color:white; }
.heatMap tr:nth-child(3) { background-color:#0000FF
; color:white; }
.heatMap tr:nth-child(4) {background-color:#000000; color:white; }
.heatMap tr:nth-child(5) { background-color:#808080; color:white; }
.heatMap tr:nth-child(6) { background-color:#FFFFFF; color:Gray; }
.heatMap tr:nth-child(7) { background-color:#F0F8FF; color:Gray; }
.heatMap tr:nth-child(8) { background-color:#FAEBD7
; color:Gray; }
.heatMap tr:nth-child(9) { background-color:#00FFFF; color:Gray; }
.heatMap tr:nth-child(10) { background-color:#7FFFD4; color:Gray; }
.heatMap tr:nth-child(11) { background-color:#F0FFFF; color:Gray; }
.heatMap tr:nth-child(12) { background-color:#F5F5DC; color:Gray; }
.heatMap tr:nth-child(13) { background-color: #FFE4C4; color:Gray; }
.heatMap tr:nth-child(14) { background-color: red; color:Gray; }

</style>

# CSS

- CSS is de taal die we gebruiken om een HTML-document op te maken.
- CSS beschrijft hoe HTML-elementen moeten worden weergegeven.
- Deze tutorial leert je CSS op een eenvoudig manier.

## CSS Voorbeeld

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        background-color: lightblue;
      }

      h1 {
        color: white;
        text-align: center;
      }

      p {
        font-family: verdana;
        font-size: 20px;
      }
    </style>
  </head>
  <body>
    <h1>Mijn eerste CSS Voorbeeld</h1>
    <p>Dit is een paragraf.</p>
  </body>
</html>
```

## Internal CSS

### style:

- Een interne stylesheet kan worden gebruikt als één enkele HTML-pagina een unieke stijl heeft.
  -De interne stijl wordt gedefinieerd in het `<style>`-element, in de kopsectie `<head></head>`.

### body:

De `body` geeft eigenlijk altijd het standaard lettertype en grootte en achtergrond kleur weer op een website en deze kunnen we naar onze keuze veranderen met behulp van CSS.

- `background-color`: is het achtergrond kleur van onze website en je kan verschilende kleuren kiezen met de Engelse benaming van de kleur of gebruik je de Hex code gebruik hiervoor deze link [Color Picker](https://htmlcolorcodes.com/color-picker/ "Color Picker")

### h1 en P:

- De `h1` tag is de belangrijkste titel van allemaal en geeft het hoofdonderwerp van een pagina aan.
- `p`: element wordt gebruikt om een paragraaf te definiëren. je kan de grotte en kleur van de letters veranderen met `color:` voor het kleur en ` font-size: px` voor grotte en `font-family: ` voor de lettertype.

## CSS Eigenschappen

### font-family:

- Arial (sans-serif)
- Verdana (sans-serif)
- Helvetica (sans-serif)
- Tahoma (sans-serif)
- Trebuchet MS (sans-serif)
- Times New Roman (serif)
- Georgia (serif)
- Garamond (serif)
- Courier New (monospace)
- Brush Script MT (cursive)

---

### h1 en p Color en Achtergrond kleuren:

<div class="heatMap">

| Kleur naam   |   Hex   |
| ------------ | :-----: |
| Red          | #FF0000 |
| Green        | #00FF00 |
| Blue         | #0000FF |
| Black        | #000000 |
| Gray         | #808080 |
| White        | #FFFFFF |
| AliceBlue    | #F0F8FF |
| AntiqueWhite | #FAEBD7 |
| Aqua         | #00FFFF |
| Aquamarine   | #7FFFD4 |
| Azure        | #F0FFFF |
| Beige        | #F5F5DC |
| Bisque       | #FFE4C4 |

</div>

## Oefening:

- Maak een pagina met twee hoofdonderwerpen `h1` en twee paragrafen `p` en je gaat de elementen (`body`, `h1`, `p`) stylen met achtergrondkleur en lettertype en letters kleur gebruik hiervoor de boven genoemd Eigenschappen.

```html
<!DOCTYPE html>
<html>
  <head> </head>
  <body></body>
</html>

</body>
</html>
```
