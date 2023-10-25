## Maak een quiz!

Jullie maken nu zelf jullie eigen quiz! Kies zelf 10 vragen met 10 juiste antwoorden. Voor elk juist antwoord kan 1 punt verdiend worden. 

Implementeer nu deze quiz in Python. Zorg er hierbij voor dat de gebruiker na elke vraag een antwoord kan geven, en ook direct te weten komt of hij juist of fout was. 

Laat de gebruiker op het einde weten hoeveel vragen hij in totaal correct heeft beantwoord.

Let bij het schrijven van dit programma ook op de naamkeuze voor variabelen en gebruik commentaar in je code!

#### Hoofdletters

Python houdt standaard rekening met hoofdletters. 2 strings zullen dus niet gelijk zijn aan elkaar indien er in de ene string een hoofdletter staat en in de andere string niet. Zorg ervoor dat bij je quiz python geen rekening houdt met hoofdletters.

Stel dat je vraagt in welke klas je zit, en het juiste antwoord is 5BCSW, dan moet je ervoor zorgen dat 5bcsw en 5Bcsw ook als correct worden aanvaard.

Bij volgende code zou enkel 5BCSW correct zijn, 5bcsw of 5Bcsw niet.

```python
antwoord = str(input("In welke klas zit je?"))
if(antwoord == "5BCSW"):
    print("Je antwoord is juist")
else:
    print("Je antwoord is fout")
```

Door achter elke string **.lower()** te schrijven, worden in deze strings alle hoofdletters kleine letters. In volgend voorbeeld zal daardoor het antwoord 5Bcsw en 5bscw ook correct zijn.

```python
antwoord = str(input("In welke klas zit je?"))
if(antwoord.lower() == "5BCSW".lower()):
    print("Je antwoord is juist")
else:
    print("Je antwoord is fout")
```


