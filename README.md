# Database Intro



## TRACCIA
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.Cosa consegnare:
    inserisci nome della tabella,
    inserisci le colonne per definire il modello
    assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna


- Nome Tabella : `small_cars`

Columns:

- id : INT - PRIMARY_KEY - AUTO_INCREMENT
- model : VARCHAR(20) - NOTNULL
- brand : VARCHAR(50) - NOTNULL
- fuel_type : VARCHAR(20) - NOTNULL
- engine_size : MEDIUMINIT - NOTNULL
- power : VARCHAR(20) - NULL
- year: YEAR - NULL
- color : VARCHAR(10) - NULL
- emissions_class : CHAR(6) - NULL
- mileage : MEDIUMINIT - DEFAULT(0)
- is_new: TINYINT - DEFAULT(0)
- gearbox: VARCHAR(20) - DEFAULT(manual)
- dimension: VARCHAR(20) - NULL
- num_seats : TINYINT - DEFAULT (2)
- num_doors: TINYINT - DEFAULT (3)
- trunk_capacity : VARCHAR(20) - NULL
- preparation: VARCHAR(50) - NULL
- price: MEDIUMINT - NULL
- description : TEXT(500) - NULL