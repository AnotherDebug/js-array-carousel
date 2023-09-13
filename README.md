# js-array-carousel


## Consegna:
**Carosello Mono Array**
- Dato un array contenente una lista di cinque immagini, creare un carosello come nello screenshot allegato.

1. Creo il mio markup dove inserisco un'immagine al centro, il tutto in modo statico;

2. Creo i due bottoni che mi serviranno per cambiare le immagini;
3. Creo tutti gli stili e le classi di cui ho bisogno per svolgere l'esercizio;
4. Dopo aver completato le prime due fasi, tolgo l'immagine statica e creo una collection di immagini che poi andrò ad inserire in modo dinamico;
5. Creo un ciclo che gestisce le immagini, che di default saranno nascoste tranne la prima;
6. Gestisco due eventi diversi, uno per il bottone che va indietro e uno che va in avanti, in modo che al click del bottone corrispondente la prima immagine visualizzata viene nascosta e la successiva viene mostrata, poi nascosta al click e cosi via;


====================================


## Fasi codice

1. Salvo tutti i percorsi all'interno delle variabili di cui ho bisogno;

2. Creo la mia lista di immagini;

3. Creo il ciclo dove gestisco la collection images;

4. Rimuovo dal mio item la classe 'hide' per vsualizzare l'immagine;

5. Creo una variabile counter per gestire la classe 'hide';

6. Creo l'evento al click per nascondere/mostrare le immagini;

    a. Quando vado avanti rimuovo hide dal bottone di sinistra;

    b. Nascondo il bottone di destra una volta terminate le immagini;

7. Creo l'evento al click per nascondere/mostrare le immagini al contrario, quindi decremento il counter;
   
   a. Quando torno indetro rimuovo hide dal bottone destro;

   b. Nascondo il bottone di sinistra quando il contatore ritorna allo 0;