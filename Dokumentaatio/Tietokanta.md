# Tietokanta

### Luontilauseet

Sprint 1:

Tietokannassa on tässä vaiheessa yksi taulu, jolla määritellään Lukuvinkki. Käytössä on SQLLite3 tietokanta.


```sql

CREATE TABLE Lukuvinkki (
	vinkki_id integer PRIMARY KEY,
	otsikko varchar(100),
	kuvaus varchar(256),
	linkki varchar(200)
);
```
