# TalentLyft Angular Interview a02
Potrebno je kreirati Angular aplikaciju pomoću `Angular CLI-a` koja simulira svakodnevno korisničko ponašanje.

Aplikacija se treba sastojati od toolbar-a na vrhu ekrana koji ima dva linka za dvije rute.
Defaultno se prikazuje `Form page`.
Klikom na `Form page`, otvara se prva ruta, klikom na `List page` otvara se druga ruta.

### Na prvom ekranu se nalazi:
1) **Jednostavna forma za unos podataka**. Ona se sastoji od:
   - Unosa imena
   - Unosa prezimena
   - Unosa email-a
   - Unosa hobija (minimalno 3 hobija, recimo nogomet, košarka, rukomet)
   
   Klikom na button `Reset` treba resetira vrijednosti forme na inicijalnu vrijednost.
   Klikom na button `View` treba prikazati unesene vrijednosti forme u donjem dijelu prvog ekrana kao prikaz podataka.

2) **Jednostavni prikaz podataka**

    Potrebno je prikazati unesene podatke iz forme u proizvoljnom formatu i s proizvoljnim stilovima.
    Na `slici na vrhu` možete vidjeti primjer prikaza unesenih podataka.
    
    Klikom na button `Remove` podatci se uklanjaju iz prikaza.
    Klikom na button `Save`, trenutni podatci iz forme se spremaju u memoriju (trebat će nam za prikaz na drugom ekranu).

## Na drugom ekranu se nalazi:
Na drugoj ruti se nalazi lista do sada spremljenih podataka u proizvoljnom formatu i s proizvoljnim stilovima.
