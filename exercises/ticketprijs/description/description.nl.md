## Ticketprijs attractiepark

De prijzen voor een attractiepark zijn gebaseerd op de lengte van een persoon:

- lengte<85 cm: de inkom is gratis

- 85 cm$\leq$ lengte <1m:  €18

- lengte$\geq$1m: €48

Hierop zijn wel enkele uitzonderingen:

- Indien je 70 jaar bent of ouder betaal je maar €18

- Indien je pas na 17u toekomt, betaal je €38 (tenzij je kleiner bent dan 1 meter)

Daarnaast doet het pretpark ook een speciale actie. Iedereen mag eens aan een rad draaien. Bij dat rad zijn er 3 uitkomsten; die allemaal even waarschijnlijk zijn.

- 1: je krijgt 10% korting

- 2: Je krijgt €20 korting

- 3: Je verliest en krijgt geen korting.

We gaan het draaien aan het rad door het programma laten nadoen. Je laat python hiervoor een willekeurig getal tussen 1 en 3 genereren. De uitkomst hiervan gebruik je om de korting te berekenen. 

We gebruiken hiervoor de random.randint() functie uit de random bibliotheek [random — Generate pseudo-random numbers — Python 3.12.0 documentation](https://docs.python.org/3/library/random.html#functions-for-integers)

Om deze functie te kunnen gebruiken zal je de random bibliotheek moeten importeren door bovenaan je code **import random** te schrijven.



Onderstaand stuk code zal aan de variabele *a* een willekeurig getal tussen 5 en 8 (5 en 8 inbegrepen) toekennen.

```python
import random

a = random.randint(5,8)
```

## Oefening

Schrijf een programma dat als input de lengte, leeftijd en tijdstip van aankomst vraagt aan de gebruiker. Op basis daarvan berekent hij de prijs zonder korting en print deze naar de gebruiker. Daarna genereert het programma een willekeurig getal tussen 1 en 3. Op basis van dat getal bepaal je welke korting de klant krijg. Je print vervolgens de korting en de nieuwe prijs naar de gebruiker. 

Bij het schrijven van dit programma dien je ook rekening te houden met volgende zaken: 

Opgelet: de prijs kan nooit minder dan €0 zijn!

Let bij het schrijven van dit programma ook op de naamkeuze voor variabelen en gebruik commentaar in je code!

### Voorbeeld1

#### invoer

```console?lang=python&prompt=>>>
162
69
16
```

#### uitvoer

```console?lang=python&prompt=>>>
De oorspronkelijke prijs is: €48
Je korting is 10%
Je betaalt nog: €43.2
```

### Voorbeeld2

#### invoer

```console?lang=python&prompt=>>>
99
3
17
```

#### uitvoer

```console?lang=python&prompt=>>>
De oorspronkelijke prijs is: €18
Je korting is €10
Je betaalt nog: €8
```

### Voorbeeld3

#### invoer

```console?lang=python&prompt=>>>
84
1
12
```

#### uitvoer

```console?lang=python&prompt=>>>
De oorspronkelijke prijs is: €0
Je korting is €10
Je betaalt nog: €0
```
