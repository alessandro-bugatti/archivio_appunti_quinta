# Esercizi sul database ATP

### Tennisti di una certa nazionalità

```GET /atp/tennisti/nazione/{flag_code}```


Restituisce l’elenco dei tennisti appartenenti alla nazionalità indicata.

### Tennisti mancini
```GET /atp/tennisti/mano/sinistra```


Restituisce tutti i tennisti che giocano con la mano sinistra.

### Tennisti con rovescio a una mano
```GET /atp/tennisti/rovescio/una-mano```


Restituisce i tennisti che utilizzano il rovescio a una mano.

### Tennisti nati in un determinato anno
```GET /atp/tennisti/nati/{anno}```


Restituisce i tennisti nati nell’anno specificato.

### Tennisti nati dopo un certo anno
```GET /atp/tennisti/nati-dopo/{anno}```


Restituisce i tennisti nati dopo l’anno indicato.

### Tennisti con altezza e peso minimi
```GET /atp/tennisti/fisico/{altezza}/{peso}```


Restituisce i tennisti con altezza (in cm) maggiore o uguale a {altezza} e peso (in kg) maggiore o uguale a {peso}.

### Tennisti diventati professionisti prima di un anno
```GET /atp/tennisti/pro/{anno}```


Restituisce i tennisti che sono diventati professionisti prima dell’anno indicato.

### Tennisti nati in un certo mese
```GET /atp/tennisti/nati/mese/{mese}```


Restituisce i tennisti nati nel mese specificato (1–12).

### Tennisti di una nazione nati dopo un certo anno
```GET /atp/tennisti/nazione/{flag_code}/nati-dopo/{anno}```


Restituisce i tennisti della nazionalità indicata nati dopo l’anno specificato.

### Tennisti residenti in una certa città
```GET /atp/tennisti/residenza/{citta}```


Restituisce i tennisti che risiedono nella città indicata.

## Estensioni facoltative

- Limitare il numero di risultati restituiti dalla query

- Ordinare i risultati (ad esempio per altezza, anno di nascita o peso)

- Gestire risposte vuote, mostrando un messaggio appropriato quando nessun record soddisfa i criteri di ricerca