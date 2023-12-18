Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Nella repo dovete consegnare un file con tutti i campi della tabella, tipo di dato ed eventuali attributi per ogni campo.

Auto Usate

id - INT- UNISIGNED - PRIMARY_KEY(NOTNULL - UNIQUE) - AUTOINCREMENT
numero_telaio - VARCHAR(17) - NOTNULL - UNIQUE
targa - VARCHAR(7) - NOTNULL - UNIQUE
casa_produttrice - VARCHAR(255) - NOTNULL
modello - VARCHAR(255) - NOTNULL
anno_produzione - YEAR - NOTNULL 
km_percorsi - DOUBLE(12,2) - NOTNULL
tipo_alimentazione - VARCHAR(255) - NOTNULL
kw_vettura - SMALLINT - NULL
numero_cavalli - SMALLINT - NULL
cilindrata  - SMALLINT - NULL
numero_porte - TINYINT - NULL
numero_posti- TINYINT - NULL
larghezza_veicolo - FLOAT(4,2) - NULL
lunghezza_veicolo - FLOAT(4,2) - NULL
colore - VARCHAR(255) - NULL
incidenti_pregressi - TINYINT - NULL 
ultimo_tagliando - DATE - NOTNULL
ultima_revisione - DATE - NOTNULL
anno_immatricolzione - DATE - NOTNULL
bollo - BLOB - NOTNULL
ultimo_proprietario - VARCHAR(255) - NOTNULL
numero_proprietari - TYNYINT - NULL
prezzo_di_vendita - DECIMAL(13,2) - NOTNULL
descrizione_veicolo - TEXT - NULL
photos- VARCHAR(255) - NOTNULL
