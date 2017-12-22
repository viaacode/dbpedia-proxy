# dbpedia-proxy
This is an Mule API on top of Dbpedia spotlight engines

## Spotlight

Download latest version of spotlight here: http://downloads.dbpedia-spotlight.org/spotlight/

Download for each language a model: http://downloads.dbpedia-spotlight.org/2016-04/

Run locally:
```
java -Xmx8G -jar dbpedia-spotlight-1.0.0.jar fr http://localhost:2227/fr/rest
java -Xmx8G -jar dbpedia-spotlight-1.0.0.jar nl http://localhost:2226/nl/rest
```

or from following Docker files:
https://github.com/dbpedia-spotlight/spotlight-docker

