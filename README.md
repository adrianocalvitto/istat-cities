*ISTAT-CITIES*

Simple attempt to port [this file](http://www.istat.it/it/files/2011/01/Elenco-codici-statistici-e-denominazioni-al-01_07_2016.xls), created by ISTAT and containing a list of all Italian cities, to a json file.

E.g:

```
{
  "Codice Regione": 1,
  "Codice Città Metropolitana": 201,
  "Codice Provincia (1)": 1,
  "Progressivo del Comune (2)": 1,
  "Codice Comune formato alfanumerico": 1001,
  "Denominazione in italiano": "Agliè",
  "Denominazione in tedesco": "",
  "Codice Ripartizione Geografica": 1,
  "Ripartizione geografica": "Nord-ovest",
  "Denominazione regione": "Piemonte",
  "Denominazione Città metropolitana": "Torino",
  "Denominazione provincia": "-",
  "Flag Comune capoluogo di provincia": 0,
  "Sigla automobilistica": "TO",
  "Codice Comune formato numerico": 1001,
  "Codice Comune numerico con 107 province (dal 2006 al 2009)": 1001,
  "Codice Comune numerico con 103 province (dal 1995 al 2005)": 1001,
  "Codice Catastale del comune": "A074",
  "Popolazione legale 2011 (09/10/2011)": 2.644,
  "Codice NUTS1 2010": "ITC",
  "Codice NUTS2 2010 (3)": "ITC1",
  "Codice NUTS3 2010": "ITC11",
  "Codice NUTS1 2006": "ITC",
  "Codice NUTS2 2006 (3)": "ITC1",
  "Codice NUTS3 2006": "ITC11"
}
```

Useful for building search apis, typeaheads, you could even use the "Codice Comune formato alfanumerico" field in combination with [ChanceJS](http://chancejs.com/#cf) to generate Italian Social Security Numbers (aka Codice Fiscale)