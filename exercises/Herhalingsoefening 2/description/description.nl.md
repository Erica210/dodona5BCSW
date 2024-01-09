Schrijf een programma dat aan de gebruiker 1 getal vraagt en vervolgens print hoeveel delers dit getal heeft.


Tip: Vorig trimester schreef je reeds een programma dat alle delers van een getal print. Pas deze code aan zodat het niet de delers print, maar het aantal delers telt.

Voorbeeld oplossing van een programma dat alle delers print (deze code moet dus aangepast worden!):

```python
getal = int(input("Geef een getal")) # vraag een getal aan de gebruiker

for deler in range(1,getal+1): # ga voor alle getallen kleiner dan dat getal na of ze een deler zijn
	if getal%deler == 0:   # een getal is een deler indien de rest bij deling door dit getal nul is
		print(deler)   # Indien dit een deler is, wordt het geprint
```
	