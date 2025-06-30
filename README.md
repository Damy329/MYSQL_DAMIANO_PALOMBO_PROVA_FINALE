ToysGroup è un’azienda che distribuisce articoli (giocatoli) in diverse aree geografiche del mondo. 


E' stato progettato fisicamente un database che modelli lo scenario garantendo l’integrità referenziale e la minimizzazione della ridondanza dei dati. 

Proposto poi una progettazione concettuale e logica della base dati. La progettazione concettuale include tutte le entità coinvolte e le relazioni tra queste.

Descrizione della struttura delle tabelle utili e sufficienti a modellare lo scenario proposto tramite la sintassi DDL. Implementazione fisica delle tabelle utilizzando il DBMS SQL.

Popolazione delle tabelle utilizzando dati a mia discrezione con poche righe per tabella e esplicitando le query utilizzate.

Esecuzione di una serie di Query

1)     Verifica dei campi definiti come PK siano univoci. Lo faccio con una query per determinare l’univocità dei valori di ciascuna PK (una query per tabella implementata).

2)     Esposizione dell’elenco delle transazioni indicando nel result set il codice documento, la data, il nome del prodotto, la categoria del prodotto, il nome dello stato,
3)  il nome della regione di vendita e un campo booleano valorizzato in base alla condizione che siano passati più di 180 giorni dalla data vendita o meno (>180 -> True, <= 180 -> False)

4)     Esposizione dell’elenco dei prodotti che hanno venduto, in totale, una quantità maggiore della media delle vendite realizzate nell’ultimo anno censito.
5) (ogni valore della condizione sarà il risultato di una query e non inserito a mano). Nel result set compaiono solo il codice prodotto e il totale venduto.

6)     Esposizione dell’elenco dei soli prodotti venduti e per ognuno di questi il fatturato totale per anno.

7)     Esposizione del fatturato totale per stato per anno. Ordinamento del risultato per data e per fatturato decrescente.

8)     Risposta alla seguente domanda: qual è la categoria di articoli maggiormente richiesta dal mercato?

9)     Risposta alla seguente domanda: quali sono i prodotti invenduti? Con conseguente proposta di due approcci risolutivi differenti.

10)     Creazione di una vista sui prodotti in modo tale da esporre una “versione denormalizzata” delle informazioni utili (codice prodotto, nome prodotto, nome categoria)

11)     Creazione di una vista per le informazioni geografiche


All' interno del file sono contenute anche analisi extra.
