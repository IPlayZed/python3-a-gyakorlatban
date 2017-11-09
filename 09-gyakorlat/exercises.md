# Feladatok

## 03web_scraping_advanced befejez�se
Maradt n�h�ny TODO, ezeket be lehet fejezni.

## T�bl�zatfeldolgoz� PIMP
A fenti f�jlban l�v� t�bl�zat feldolgoz�sa, az adatok lement�se k�nnyen kezelhet� CSV form�tumban. Az adatokb�l k�l�nb�z� statisztika
kinyer�se, h�ny hallgat� kapott egyest, kettest, h�rmast, n�gyest, �t�st. Az eredm�nyek megjelen�t�se egy webszerveren. Az oldalon l�v�
link hat�s�ra friss�tse a tartalmat, sz�molja �jra a statisztik�t.

## Web2MD
P�ld�ul a http://www.inf.u-szeged.hu/~antal/ oldal (de b�rmi lehet, ak�r wiki cikk, stb) kiment�se MD fomr�tumban (vagy lehet txt is):

- A f�oldalon l�v� linkek mindegyik�re is h�vjuk meg az �talak�t�t.
- Nem kell, hogy t�k�letes legyen: el�g ha bizonyos elemekre m�k�dik (c�m, div, a, p, span, stb, b�rmi).
- K�peket, r�vid�tsen a tinyurl.py haszn�lat�val.

## Online f�jlszerkeszt�
Egy el�re elk�sz�tett CSV f�jl online szerkeszt�se, b�rki �ltal (vagy ak�r autentik�ci� ut�n).

- Egy webes API-n kereszt�l lehessen kommunik�lni: /read - a f�jl akut�lis �llapota, kicsit megsz�p�tve, vagy ak�r JSON-nel (GET k�r�s)
- Szerkeszt�s, a t�rdel�s seg�ts�g�vel, pl. egyszerre egy sz�t cser�lhet�nk: /modify/SOR/SZ�_SZ�MA (mondjuk pontosvessz�vel t�rdelj�k). (POST k�r�s)
- A szerkeszt�sr�l j�jj�n v�lasz: melyik sz�t cser�lt�k le mire.

## WebZipDownloader
P�ld�ul a http://www.inf.u-szeged.hu/~antal/?p=prog2 oldalon l�v� �sszes link bej�r�sa, �s ha .zip a kiterjeszt�se, akkor t�ltse le:

- Ehhez haszn�ld a urllib.request.urlretrieve f�ggv�nyt. B�vebben: https://stackoverflow.com/a/7244263/5738367, https://docs.python.org/dev/library/urllib.request.html#urllib.request.urlretrieve
- Let�lt�s ut�n haszn�ld az shutils.make_archive f�ggv�nyt, hogy az �sszes zipb�l egy nagy zip f�jlt k�sz�ts! https://docs.python.org/3/library/shutil.html#shutil.make_archive
