# Tekstimuuttujat

## JOHDANTO
- Tehtävän koodi muistuttaa edellisiä tehtäviä, hyödynnä jo oppimaasi.
- Muista: Numeromuuttuja ei voi sisältää tekstiä, pelkästään numeroita.
- Alustettu muuttuja sisältää arvon luomisestaan alkaen.
  - Alustettuja muuttujia voi luoda vain yhden kerrallaan
  - esim: int luku1 = 10;
- Alustamaton muuttuja ei sisällä arvoa luontihetkellä.
        ◦ Alustamattomia muuttujia voi luoda useita samaan aikaan
        ◦ esim: int summa, erotus;
## TEHTÄVÄNANTO
- Tee konsolisovellus, jossa on yhteensä kuusi numeromuuttujaa ja neljä konsoliin tulostava "write line" -tyyppistä konsolimetodia
- Muuttujat: Kaksi ensimmäistä ovat edellisestä tehtävästä tutut int tyyppiset luku1 ja luku2. Luku1 on arvoltaan 10 ja luku2 5. Neljä muuta ovat arvoon alustamattomat tulo, erotus, summa ja osamäärä.
- Laita ohjelma laskemaan kaikille alustamattomille luvuille arvot alla olevan esimerkin tavoin:
  - summa = luku1 + luku2;
- Metodit: tulostavat muuttujat konsoliin. WriteLine tulosterivejä tulee 5 erilaista. Älä kirjoita konsolitulosteen tekstiin lukuja vaan käytä muuttujia. Ensimmäisessä tulosterivissä on vain tekstiä.
- Esimerkkituloste alla:

  
```
Peruslaskujen tulokset:
Tulo: 50
Summa: 15
Erotus: 5
Osamäärä: 2
```
> [!IMPORTANT]
> Koodin kirjoittamisen johdanto
1. Kloonaa projekti omalle koneellesi.
2. Avaa `ConsoleApp.sln`.
3. Solution-ikkunasta valitse "ConsoleApp".
4. Pääkoodi löytyy `Program.cs`-tiedostosta. Jos tarvitset, luo uudet itemit `ConsoleApp`-projektiin.
