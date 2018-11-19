# Tietokanta

### Luontilauseet

Sprint 1:

Tietokannassa on tässä vaiheessa yksi taulu, jolla määritellään Lukuvinkki. Käytössä on SQLite3 tietokanta.

Tietokannan alustus terminaalissa:


```sql

sqlite3 Lukuvinkkikirjasto.db


CREATE TABLE Lukuvinkki (
	vinkki_id integer PRIMARY KEY,
	otsikko varchar(100),
	kuvaus varchar(256),
	linkki varchar(200)
);
```
