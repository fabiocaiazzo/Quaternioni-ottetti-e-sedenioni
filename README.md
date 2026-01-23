Questo progetto è stato ideato da Fabio Caiazzo ed è stato realizzato con il supporto di strumenti di intelligenza artificiale, che hanno assistito nella scrittura del codice sulla base delle specifiche fornite dall'autore.

MANUALE UTENTE: VISUALIZZATORE E CALCOLATRICE ALGEBRICA
Quaternioni, Ottetti e Sedenioni

----------------------------------
1. PANORAMICA E VISUALIZZAZIONE 3D

Il software si avvia visualizzando di default l'algebra dei Sedenioni.
Il grafico 3D interattivo mostra la struttura moltiplicativa:
- La disposizione degli elementi indica il prodotto.
- Il senso di percorrenza delle punte bianche sulle linee indicano il verso "positivo" della moltiplicazione (esempio: se e_1*e_2=e_3, il punto si muove seguendo il ciclo 1-2-3).

-----------------------------------------------
2. BARRA DELLE IMPOSTAZIONI (Tasto Ingranaggio)

Dal menu impostazioni è possibile gestire l'ambiente:
- Slider Velocità: Per cambiare la velocità dell'animazione.
- Tema: Possibilità di cambiare lo sfondo tra 5 varianti diverse.
- Reset Camera: Riporta la visuale alla posizione originale.
- Animazione: Mette in pausa o riavvia l'animazione.
- Supporto: Fornisce una spiegazione sommaria del programma.

---------------------------------------
3. SELEZIONE DELL'ALGEBRA (Tasto S/O/H)

Premendo il tasto con la lettera in blackboard bold si passa tra Quaternioni (H), Ottetti (O) e Sedenioni (S).
Questo modifica:
- Il Grafico 3D: Una circonferenza con 3 punti (H), un piano di Fano con 7 punti (O) o una "piramide" con 15 punti (S).
- I cicli: Aggiorna l'elenco dei cicli nella tabella laterale.
- Divisori dello zero: Abilita/disabilita la vista dei divisori dello zero (visibili solo per Sedenioni).
- La tabella: Aggiorna la tabella delle moltiplicazioni (4x4 per i quaternioni, 8x8 per gli ottetti e 16x16 per i sedenioni).

--------------------------
4. CALCOLATRICE

Accessibile dal tasto calcolatrice, permette calcoli sulle tre algebre (selezionabili col tasto azzurro in alto a sinistra).

4.1 Gestione Variabili
- Si possono salvare fino a 5 variabili: a, b, c, d, e.
- La dimensione si adatta all'algebra (4, 8 o 16 valori).
- Richiamo rapido: Le variabili sono richiamabili dal tastierino.
- Tasti rapidi di compilazione:
  * "Azz Var": Pone la variabile a 0.
  * "Random Var": Genera coefficienti interi casuali tra -10 e 10.

4.2 Operazioni e Sintassi
- Richiamo delle variabili a, b, c, d, e.
- Operazioni base e avanzate: Modulo (|v|), Inverso (inv), Coniugato (cnj), Commutatore ([x,y]).
- Scalari: Numeri 0-9 per moltiplicazioni dirette senza salvare variabili.
- Punteggiatura:
  * Tasto ".": Punto decimale.
  * Tasto ",": Separatore per gli argomenti del commutatore.

4.3 Cronologia
- Tasto Orologio: Mostra/nasconde la cronologia risultati.
- Tasto Pulisci: Cancella la cronologia.
- Utilizzo risultati: Cliccando su "AnsX" in elenco si riutilizza il risultato.

------------------------------------
5. PANNELLO LATERALE (Tasto Tabelle)

Premendo il tasto "Tabelle" si apre il menu laterale con tre sezioni:

A. Cicli
- Mostra i cicli dell'algebra (1 per H, 7 per O, 35 per S).
- Cliccando su un ciclo, il grafico mostra solo quello.
- "Mostra tutto": Torna alla visualizzazione completa di tutti i cicli di quell'algebra.

B. Divisori dello Zero
- Visibile solo in modalità Sedenioni.
- Cliccando su una coppia, questa viene caricata nella calcolatrice (variabili "a" e "b") per verificare che il prodotto sia zero.

C. Tabella
- Mostra la tavola di moltiplicazione (convenzione: Colonna Sx * Riga Alto).
- Cliccando sulle intestazioni si evidenzia la riga/colonna.
- Cliccando su incrocio riga/colonna si evidenzia il risultato.
- Cliccando su una cella interna si evidenzia nel grafico 3D la terna corrispondente (non funziona nel caso il risultato sia 1 o -1 o nel caso uno dei due fattori sia 1).
