# Feladatok

## Maxim�lis elem kiv�laszt�sa a reduce haszn�lat�val
L�sd: exercises.py f�jl

## Kocsi adatok
0. A feladat a `cars.csv` beolvas�sa a csv.DictReader seg�ts�g�vel. A beolvasott objektumokb�l k�sz�ts�nk `Car` objektumokat. 
Ehhez hozzuk l�tre a `Car` oszt�lyt. A `rendszamok.txt` f�jlban tal�lunk az aut�khoz rendsz�mokat. A f�jl beolvas�sa ut�n
egys�ges�ts�k a rendsz�mokat BBB-000 form�tum� rendsz�mm�, �gy "tegy�k fel" egy kocsira. Mindegyik rendsz�mot adjuk hozz�
valamelyik aut�hoz (az egyszer�s�g kedv��rt �rdemes sorban haladni. Az �gy elk�sz�lt adathalmazt:

1. Ments�k ki json f�jlba. 
2. Csak a kocsi t�pusa+rendsz�m adatokat ments�k ki a csv.DictWriter seg�ts�g�vel!
3. Sz�rj�k az aut�kat: t�roljuk el egy list�ban a 96 kW teljes�tm�ny� aut�kat (1 l�er� = 0.745699872 kilowatt)
4. V�lasszuk ki a list�b�l azt az aut�t, amelyik a leggyorsabban gyorsul fel 100 km/h-ra, a reduce() seg�ts�g�vel.
5. K�sz�ts�nk egy list�t a map() seg�ts�g�vel, amelyben legyen benne, hogy az egyes aut�k h�ny �vesek (jelenlegi �v - gy�rt�s)

## Email valid�tor 
K�sz�ts�nk egy e-mail c�m valid�tor f�ggv�nyt. T�rjen vissza igazzal, ha e-mail c�met adtunk neki param�terben, k�l�nben pedig hamissal.