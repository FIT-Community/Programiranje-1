# Zadatak 01

Napisati program koji učitava prirodan broj n. Program treba ispisati najmanji prirodan broj m, veći ili jednak n, koji je potencija nekog prirodnog broja, tj. ![m = k ^ l](https://latex.codecogs.com/gif.latex?m%20%3D%20k%20%5E%20l), gdje su k i l prirodni brojevi >= 2.

# Zadatak 02

Napisati program koji će omogućiti korisniku unos broja n (uz uslov 10 <= n <= 1000). Zatim simulirati unos n slučajnih vrijednosti. Simuliranje unosa ostvariti funkcijom rand() % 1000 + 1. Izračunati statističke podatke u kojem procentu se od n generisanih slučajnih vrijednosti pojavljuje prost broj.

Npr. Ako je generisano 10 brojeva (n = 10): 5,7,4,13,17,20,25,23,30,45, u ovom uzorku od 10 brojeva postoji 5 prostih brojeva pa je procenat prostih brojeva u ovom slučaju 50%.

Napomena: Po želji kreirati dodatne funkcije da se olakša rješavanje zadatka.

# Zadatak 03

Napisati program koji će omogućiti unos cijelih brojeva sa neparnih brojem cifara 
(minimalno trocifrenih) u jednodimenzionalni niz od 20 elemenata i jedan karakter u main funkciji. Zatim napraviti funkciju koja će primati kao argumente taj niz i karakter. Funkcija treba da na osnovu karaktera izvrši sortiranje niza uzlazno ili silazno po srednjoj cifri i to ako je primljeni karakter "U" sortiranje treba biti uzlazno, a ako je primljen karakter "S" onda sortiranje treba biti silazno. Ukoliko karakter nije jedan od navedenih, treba se ispisati poruka "Sortiranje nedefinisano". Obavezno voditi računa o optimizaciji code-a koja posebno utiče na broj bodova u ovom zadatku.

# Zadatak 04

Dat je 2D niz koji simulira šahovsku tablu. Omogućiti korisniku unos cjelobrojnih elemenata 2D niza tako da se u svako "crno" polje unese parni broj sa neparnim brojem cifara, a u "bijelo" polje neparni broj sa parnim brojem cifara. Provjeriti da li je matrica simetrična po glavnoj dijagonali (dakle da li je broj na poziciji 1.0 jednak broju na poziciji 0.1, na 0.2 jednak onome na 2.0, na 3.1 jednak onome na 1.3 itd.) te ako jeste simetrična na taj način izvršiti transpoziciju matrice tako što će se zamjeniti redovi i kolone (ne samo ispisati nego potpuno zamjeniti elemente). Ako nije u potpunosti simetricna ispisati koliko ima simetricnih elemenata).
    
    C - Crna
    B - Bijela
```    
    +-----+-----+-----+-----+-----+-----+-----+-----+
    | C00 | B01 | C02 | B03 | C04 | B05 | C06 | B07 |
    +-----+-----+-----+-----+-----+-----+-----+-----+
    | B10 | C11 | B12 | C13 | B14 | C15 | B16 | C17 |
    +-----+-----+-----+-----+-----+-----+-----+-----+
    | C20 | B21 | C22 | B23 | C24 | B25 | C26 | B27 |
    +-----+-----+-----+-----+-----+-----+-----+-----+
    | B30 | C31 | B32 | C33 | B34 | C35 | B36 | C37 |
    +-----+-----+-----+-----+-----+-----+-----+-----+
    | C40 | B41 | C42 | B43 | C44 | B45 | C46 | B47 |
    +-----+-----+-----+-----+-----+-----+-----+-----+
    | B50 | C51 | B52 | C53 | B54 | C55 | B56 | C57 |
    +-----+-----+-----+-----+-----+-----+-----+-----+
    | C60 | B61 | C62 | B63 | C64 | B65 | C66 | B67 |
    +-----+-----+-----+-----+-----+-----+-----+-----+
    | B70 | C71 | B72 | C73 | B74 | C75 | B76 | C77 |
    +-----+-----+-----+-----+-----+-----+-----+-----+
```