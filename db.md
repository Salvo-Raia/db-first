| Nome colonna                  | Tipo di dato | Attributi                       | Indice      |
| ----------------------------- | ------------ | ------------------------------- | ----------- |
| id                            | BIGINT       | UNIQUE, NOT NULL, AUTOINCREMENT | PRIMARY KEY |
| marca                         | VARCHAR(20)  | NOT NULL                        | Index       |
| modello                       | VARCHAR(20)  | NOT NULL                        | Index       |
| numero_di_telaio              | CHAR(17)     | UNIQUE, NOT NULL                |             |
| targa                         | CHAR(7)      | UNIQUE, NOT NULL                |             |
| anno_immatricolazione         | YEAR         | NOT NULL                        | Index       |
| numero_proprietari_precedenti | TINYINT      | DEFAULT(1), UNSIGNED, NOT NULL  |             |
| condizioni                    | VARCHAR(20)  | NOT NULL                        | Index       |
| scadenza_revisione            | DATE         | NOT NULL                        |             |
| chilometraggio                | INT          | UNSIGNED, NOT NULL              | Index       |
| alimentazione                 | VARCHAR(10)  | DEFAULT 'Benzina', NOT NULL     | Index       |
| cilindrata_cc                 | INT          | NOT NULL                        | Index       |
| cambio_principale             | VARCHAR(12)  | DEFAULT 'Manuale', NOT NULL     | Index       |
| trazione                      | VARCHAR(10)  | DEFAULT 'Posteriore', NOT NULL  |             |
| numero_porte                  | TINYINT      | DEFAULT(5), UNSIGNED, NOT NULL  |             |
| numero_posti                  | TINYINT      | DEFAULT(4), UNSIGNED, NOT NULL  |             |
| colore_principale             | VARCHAR(15)  | NOT NULL                        |             |
| colore_secondario             | VARCHAR(15)  | NULL                            |             |
| classe_emissioni              | CHAR(6)      | NOT NULL                        | Index       |
| prezzo                        | INT          | UNSIGNED, NOT NULL              | Index       |
| descrizione                   | TEXT         | NULL                            |             |
| url_img_principale            | VARCHAR(255) | NOT NULL                        |             |
