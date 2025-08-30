# Om dette repoet

Dette repoet inneholder en .pdf som viser bruk av teknologene
- Neo4j
- MongoDB
- Cassandra
- Redis
- Spark

Databasene brukes mot forskjellige datasett relatert til kraftmarkedet (eks produksjon, eksport, nedbør, kraftpriser osv..).

Det vises hvordan databasene kan designes, kode for oppsett, og kode for å hente ut data.

For å lese mer om dette, klikk på pdf-filen "NOSQL.pdf".
Resolusjonen er bedre hvis du laster ned dokumentet.


## Framvisning av dataene i powerBI

Man kan se på noen av grafene at ved historisk lav magainsylling grunnet tørke, har det vært historisk høye kraftpriser

<img width="848" height="495" alt="image" src="https://github.com/user-attachments/assets/cf6fe0db-53b6-4099-a655-702a78500287" />


<img width="849" height="469" alt="image" src="https://github.com/user-attachments/assets/e73dac1f-0935-4c78-bd75-f47f190b4a5d" />


<img width="851" height="489" alt="image" src="https://github.com/user-attachments/assets/79379354-3e9c-4534-8361-8a67b5cb6d66" />

<img width="1216" height="685" alt="image" src="https://github.com/user-attachments/assets/73f90ed2-371b-4259-badf-fb309178317c" />




# Design av databasene
## Neo4j eksempel
Node for et elspotområde:

<img width="936" height="762" alt="image" src="https://github.com/user-attachments/assets/8ac67cb1-4797-499a-ab75-5dcbdd146f90" />

## MongoDB eksempel
Dokument for elspotområde

<img width="609" height="741" alt="image" src="https://github.com/user-attachments/assets/b25d67d7-6613-4004-b4bc-75200543b8f0" />

Dokument for værdata for et elspotområde

<img width="546" height="686" alt="image" src="https://github.com/user-attachments/assets/1df1b871-d5ea-423f-aead-26c043262d7d" />

<img width="521" height="304" alt="image" src="https://github.com/user-attachments/assets/c45d5610-038b-4c7d-8360-d0a1db6aa6f5" />

## Cassandra eksempel

Eksempel for et fylke:
<img width="1105" height="192" alt="image" src="https://github.com/user-attachments/assets/67947146-c0ab-477a-94e4-c641b05a80fb" />

## Redis eksempel

Eksempel for et elspotområde

Lister i databasen:

<img width="227" height="229" alt="image" src="https://github.com/user-attachments/assets/17023342-a275-4f7b-8268-9e76e75646a2" />

## Scala eksempel
Eksempel på en dataframe i scala som viser strømpriser i de forskjellige elspotområdene:

<img width="878" height="410" alt="image" src="https://github.com/user-attachments/assets/954dbf98-9db1-48b9-8490-72d826b6412b" />

Eksempel på en dataframe som viser kraftproduksjon

<img width="759" height="550" alt="image" src="https://github.com/user-attachments/assets/66643ddf-f7f0-4aaa-9308-1a8c779f19e3" />




















