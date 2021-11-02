# JavaScript Intro

- JavaScript is een programmeertaal voor het web.

- JavaScript kan zowel HTML als CSS bijwerken en wijzigen.

- JavaScript kan gegevens berekenen, manipuleren en valideren.

## Datatypes

JavaScript heeft verschillende datatypes.

| Datatype    | Omschrijving                                               |
| ----------- | :--------------------------------------------------------- |
| `String`    | Tekst.                                                     |
| `Number`    | Een getal of kommagetal.                                   |
| `Boolean`   | Waar of niet waar, dus "true" of "false".                  |
| `Object`    | Een collectie data die je door "keys" kunt verkrijgen.     |
| `Array`     | Een collectie van andere datatypes.                        |
| `undefined` | Een datatype waarvan de variabele niet is geïnitialiseerd. |
| `null`      | Geeft een null-waarde aan.                                 |

## Variabelen

In JavaScript kun je variabelen maken, variabelen kun je zien als een stukje brein. Een variabele slaat data op dat het aangewezen is in je PC's memory (RAM).

Er bestaan 2 verschillende variabelen in JavaScript, constante en manipuleerbare. Constante variabelen hun waarde kun je niet aanpassen, manipuleerbare wel.

Dit is hoe je variabelen kunt toewijzen in JavaScript.

```js
// Een constante variabele met een nummer als waarde.
const a = 1;

// Een manipuleerbare variabele met een string als waarde.
let b = "Dit is een tekst.";
```

## Functies

In JavaScript kun je functies aanmaken. Functies zijn stukken code die je kunt uitvoeren, je kunt ze ook parameters toegeven. Functies voeren hun "body" uit. De body van een functie is de code die in de functie is geschreven.

Als voorbeeld een `groet` functie.

```js
function groet(naam) {
  return "Hallo, " + naam + "!";
}
```

Met het keyword `function` vertel je JavaScript dat je een nieuwe functie wilt maken. Na dit keyword geef je de naam van de functie en eventuele parameters. In de body van de functie heb ik `return "Hallo, " + naam + "!";` geschreven, dit betekent letterlijk: Geef mij een string terug met de naam die ik doorgeef als ik de functie uitvoer.

Je kunt de functie uitvoeren als volgt.

```js
groet("Ronnie");
```

Als je de functie uitvoert in je console <kbd>F12</kbd>, dan zie je dat het `undefined` terug geeft. Dit is omdat het iets `return`ed. Als je `return` gebruikt geeft een functie iets terug, deze waarde kun je in een variabele zetten als volgt.

```js
const begroeting = groet("Ronnie");
```

Nu kun je als je dit in je console runt `begroeting` weergeven.