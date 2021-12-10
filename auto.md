<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->


(Table) auto:

id | BIGINT - AUTO INCREMENT, PRIMARY KEY, UNIQUE, NOTNULL

marca | VARCHAR(20) - NOTNULL
modello | VARCHAR(25) - NOTNULL
model_year | YEAR - NULL
allestimento | VARCHAR(25) - NULL
prezzo(€) | DECIMAL(7,2) - NOTNULL

anno_di_immatricolazione | YEAR - NOTNULL
km_percorsi(*1000) | TINYINT - NOTNULL
condizione | VARCHAR(15) - NULL

alimentazione | VARCHAR(20) - NOTNULL
cilindrata(cc) | VARCHAR(4) - NULL
potenza(cv) | TINYINT - NULL
consumi(l/100km) | FLOAT(2,1) - NULL

colore | VARCHAR(20) - NULL
num_porte | CHAR(1) - NULL
num_posti | CHAR(1) - NULL
num_airbag | CHAR(1) - NULL

controlli | TEXT - NULL
garanzia | BIT - DEFAULT(1)
documenti | TEXT - NULL
accessori | TEXT - NULL
note | TEXT - NULL


