PROBLEMA :
Scrivere un programma che chieda all’utente:
- Il numero di chilometri da percorrere
- Età del passeggero
Sulla base di queste informazioni dovrà calcolare il prezzo totale del biglietto di viaggio, secondo le seguenti regole:
- il prezzo del biglietto è definito in base ai km (0.21 € al km)
- va applicato uno sconto del 20% per i minorenni
- va applicato uno sconto del 40% per gli over 65.

SOLUZIONE :

SOLUZIONE:

1- Prendo in input la lunghezza del viaggio in km;
2- Prendiamo in input l'età del cliente;
3- Con una strttura di controllo IF verifichiamo se il cliente ha meno di 18 anni o più di 65;
4- Se ha 18 anni o più, ma meno di 66, diamo in output il prezzo della corsa moltiplicando la tratta per 0.21 euro.
5- Se il cliente ha meno di 18 anni, al risultato applichiamo uno sconto del 20%;
6- Se il cliente ha più di 65 anni applichiamo uno sconto del 40%;