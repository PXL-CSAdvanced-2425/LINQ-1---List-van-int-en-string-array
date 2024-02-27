# LINQ
Los de volgende vragen op met behulp van een LINQ query.
Gebruik de volgende IEnumerable objecten:
```
List<int> driehoek = new List<int>()
{
1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1,
1, 2, 3, 4, 5, 6, 7, 8, 9, 10,
1, 3, 6, 10, 15, 21, 28, 36, 45,
1, 4, 10, 20, 35, 56, 84, 120,
1, 5, 15, 35, 70, 126, 210,
1, 6, 21, 56, 126, 252,
1, 7, 28, 84, 210,
1, 8, 36, 120,
1, 9, 45,
1, 10,
1
};
string[] tekst = new string[]
{
"langspeelfilm", "vluchtmisdrijf", "dovemansgesprek", "containerpark",
"confituur", "inox", "valavond", "enerverend", "lopen", "bank", "vieruurtje",
"waterzooi", "maaltijdcheque", "arrondissement", "eindtermen", "nieuwjaarsbrief"
};
```
a. Druk al de woorden af in de array, tekst, die langer zijn dan tien karakters.
b. Bereken het gemiddelde voor de getallen in de list driehoek die groter zijn dan 100.
c. Druk al de unieke getallen af uit de List, driehoek.
d. Druk alle unieke getallen af uit de List, driehoek, die deelbaar zijn door drie of vijf. De getallen worden in een oplopende volgorde afgedrukt.
e. Druk de woorden uit de array, tekst, af in een aflopende volgorde op basis van lengte. Verder zijn woorden met dezelfde lengte gesorteerd op een oplopende alfabetische volgorde.
f. Maak een groep op basis van de startletter van ieder woord voor al de woorden in de array, tekst.
g. Vind alle paren van getallen en woorden waar de lengte van het woord uit de array, tekst, gelijk is aan een getal uit de List, driehoek. Druk het alle gevonden paren af.
h. Maak een uitbreiding op de vorige oefening die er voor zorgt dat elk woord slechts één maal voorkomt in de resulterende paren.
i. Druk alle woorden af uit de array, tekst, die minstens drie klinkers bevatten.
