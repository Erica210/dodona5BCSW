## Goud

Stel, je hebt $n$ stapels goudstukken, met ook $n$ goudstukken in elke stapel. De goudstukken zien er allemaal hetzelfde uit, maar toch zijn de goudstukken uit exact één stapel vervalst. Je kent het gewicht van de echte goudstukken en je weet dat het verschil in gewicht tussen echte en vervalste muntstukken exact 1 gram bedraagt (je weet wel niet welk van de twee het zwaarst weegt).

Om te bepalen welke goudstukken vervalst zijn, is het voldoende één enkele weging te doen. Neem één goudstuk van de eerste stapel ,twee goudstukken van de tweede stapel, drie goudstukken van de derde stapel, …tot en met alle goudstukken van de laatste stapel. Weeg al deze goudstukken samen in één keer. Het verschil tussen het gemeten gewicht en het gewicht dat de goudstukken zouden hebben mochten ze allemaal echt zijn, geeft aan hoeveel goudstukken je van de vervalste stapel genomen hebt.

Schrijf een programma dat bepaalt welke stapel vervalste goudstukken bevat. Je vraagt daarvoor als invoer drie strikt positieve natuurlijke getallen, elk op een afzonderlijke regel:

- het aantal stapels (en ook het aantal goudstukken in elke stapel)

- het gewicht van een echt goudstuk (in gram)

- het gewicht van alle goudstukken (in gram) die je samen hebt gewogen als je de weegstrategie uit de inleiding toepast

Het programma print daarna het aantal goudstukken dat uit de vervalste stapel is genomen.

### Voorbeeld

#### invoer

```console?lang=python&prompt=>>>
10
1
60
```

#### uitvoer

```

5
```

### 
