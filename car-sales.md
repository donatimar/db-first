**Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.**

| **Name**           | **Type**     | **Attributes**           | **Key**     | **Note**                                     |
| ------------------ | ------------ | ------------------------ | ----------- | -------------------------------------------- |
| ID_Auto            | BIGINT(20)   | AUTO_INCREMENT, NOT NULL | Primary Key | ID unico dell'automobile                     |
| Numero_Telaio      | CHAR(17)     | NOT NULL                 |             | Numero di telaio dell'automobile             |
| Marca              | VARCHAR(20)  | NOT NULL                 |             | Marca dell'automobile                        |
| Modello            | VARCHAR(30)  | NOT NULL                 |             | Modello dell'automobile                      |
| Anno_Fabbricazione | INT          | NOT NULL                 |             | Anno di fabbricazione dell'automobile        |
| Chilometraggio     | INT          | NOT NULL                 |             | KM percorsi dall'automobile                  |
| Colore             | VARCHAR(20)  | NOT NULL                 |             | Colore dell'automobile                       |
| Prezzo             | DECIMAL(9,1) | NOT NULL                 |             | Prezzo di vendita dell'automobile            |
| Data_Inserimento   | DATE         | NOT NULL                 |             | Data inserimento nel sistema dell'automobile |
| Disponibilità      | BOOLEAN      | NOT NULL                 |             | Disponibilità dell'automobile                |
