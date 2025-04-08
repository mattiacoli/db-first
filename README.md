# Database Intro



## TRACCIA
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.Cosa consegnare:
    inserisci nome della tabella,
    inserisci le colonne per definire il modello
    assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna


- Nome Tabella : `auto_utilitarie`

Colonne:
- id : INT - PRIMARY_KEY - AUTO_INCREMENT
- nome modello : VARCHART(20) - NOTNULL
- marca : VARCHART(50) - NOTNULL
- motorizzazione : VARCHART(20) - NOTNULL
- cilindrata : MEDIUMINIT - NOTNULL
- potenza : VARCHART(20) - NULL
- anno: YEAR - NULL
- kilometraggio : MEDIUMINIT - DEFAULT(0)
- nuova: TINYINT - DEFAULT(0)
- tipo cambio : VARCHAR(20) - DEFAULT(manuale)
- dimensioni: VARCHART(20) - NULL
- numero posti : TINYINT - DEFAULT (2)
- numero porte : TINYINT - DEFAULT (3)
- capienza bagagliaio : VARCHAR(20) - NULL
- allestimento: VARCHAR(50) - NULL
- prezzo: MEDIUMINT - NULL
- descrizione : TEXT(500) - NULL
