# 4. gyakorlat

## Autós kártyajáték

A játék kétszemélyes.
A csv fájlból olvassuk be az autók adatai, és ezek alapján hozzuk létre a kártyákat (egy sor egy autót reprezentál)
Ezután osszuk szét a kártyákat a két játékos között.

Egy kör:
- Random választunk egy autót, majd annak az autónak kiválasztjuk egy tulajdonságát.
- Ezután a gépi játékos kártyái közül is random választunk egyet és megnézzük, hogy a megadott tulajdonság alapján melyik játékos kártyájának jobb (az adott tulajdonság)értéke
- A győztes megkapja mind a két kártyát

Addig ismételjük a köröket amíg valakinek el nem fogy a lapja (vagy egy megadott darabszám alá nem kerül)
