# Technologie NoSQL

<!--
Kilka przykładowych agregacji korzystających z danych
[zipcodes](http://media.mongodb.org/zips.json) oraz
[imieniny](data/wbzyl/imieniny.csv) opisano w [Aggregation Pipeline Examples](Aggregations_in_JS.md).
-->

![Elasticsearch logo](images/elasticsearch-logo.png)


Terminy rozliczania się z [zadań](http://wbzyl.inf.ug.edu.pl/nosql/zadania):

| zadanie | opis                 | termin     |
|---------|--------------------- |------------|
| 0.      | Neo4j                | 25.10.2014 |
| 1 a-c   | EDA                  | 15.11.2014 |
| 1 d.    | GeoJSON              | 29.11.2014 |
| 2.      | Aggregation Pipeline |  6.12.2014 |
| 3*.     | MapReduce            | 10.01.2015 |

**\*** – zadanie na egzamin; wersję z podłączonym monitorowaniem bazy
[MMS](https://mms.mongodb.com/) ([MMS Cloud Docs](https://docs.mms.mongodb.com/)),
można przygotować w zespole 2–3 osobowym.


### Neo4j, MongoDB i Elasticsearch

**[15.11.2014]** 12.11. pojawiła się wersja [2.8.0-rc0](http://docs.mongodb.org/manual/release-notes/2.8/).
Do tabelek w rozwiązaniach zadań 1a, 1c, 2 dodać wiersze
dla tej wersji (lub późniejszej) MongoDB.
W wynikach uwzględnić *storageEngines* MMAPv1
i [WiredTiger](http://www.wiredtiger.com/).

Dane należy wpisać według schematu:

    1. [Nazwisko, Imię](link do repo z zadaniem **Neo4j**).
       [Tytuł 1](link do repo z zadaniem **EDA** + **GeoJSON**),
       [Tytuł 2](link do repo z zadaniem **Agregacje**).

### Zaliczone (zadania oddane po terminie)

1. Dunikowski, Jacek / 25.10
    - [Zadanie 1](https://github.com/jaca22/NOSQL)
1. Falęcki, Jacek / 25.10
   - [Zadanie 1 i 2](https://github.com/jfalecki/projekty)
1. [Pająkowski, Adrian](https://github.com/apajakowski/neo4j "neo4j public repo")
   - [Zadanie 1](https://github.com/apajakowski/zad1)
   - [Zadanie 2](https://github.com/apajakowski/zad2)
1. [Perkowski, Maciej](https://github.com/mperkowski/Neo4j "neo4j public")
   - [Zadanie 1](https://github.com/mperkowski/Mongo)
   - [Zadanie 2](https://github.com/mperkowski/AggregationPipeline)
1. Michał Turzyński
   - [Zadanie 1 a-d](https://bitbucket.org/michal-at-bb/mongo_zadania/overview)
   - [Zadania (mongo)](https://bitbucket.org/michal-at-bb/mongo_zadania)
1. [Wardzińska, Justyna](https://github.com/wardzinskaj/neo4jzadania "neo4j private repo")
   - [Zadanie 1](https://github.com/wardzinskaj/geojson)
1. Zduniak, Daniel
   - [Zadanie 1](https://github.com/dzduniak/NoSQL)

----

1. Hinz, Karol
   - [Zadanie 1 a-d](https://github.com/khinz/MongoDB)
1. [Michalski, Mateusz](https://github.com/matismatis93/neo4j "neo4j private repo")
   - [Zadanie 1](https://github.com/matismatis93/MongoDB)

1. Basiak, Paweł
1. Barański, Kamil 8.11
1. Całus, Maciej 8.11
1. Duchna, Przemysław
1. Gonera, Ewa
1. Miszczykowski, Mariusz 25.10
1. Rawicki, Wojciech 25.10
1. Wasilewski, Tomasz 25.10
1. Zielke, Adam


## Egzamin – 10.01, 17.01 2015

> A good demo is disproportionately valuable in big data science.<br>
> — [Storytelling](http://en.wikipedia.org/wiki/Storytelling)

[MapReduce, Zadanie 3](http://wbzyl.inf.ug.edu.pl/nosql/zadania)
(projekt indywidualny) albo MapReduce+[MMS](https://mms.mongodb.com/) (projekt zespołowy).

Oczwiście, że funkcjie map i reduce opisane w zadaniu 3 można zastąpić
swoimi funkcjami map i reduce i użyć ich do obliczeń na swoich danych.

Zamiast bazy MongoDB, można przygotować przykłady lub wtyczki lub agregacje
dla bazy [Elasticsearch](http://www.elasticsearch.org/overview/).
Na początek należy się przyjrzeć narzędziu
[Kibana](http://www.elasticsearch.org/overview/kibana), następnie poczytać
o [wtyczkach](http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/modules-plugins.html)
a na koniec o [agregacjach](http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/search-aggregations.html).

Dane należy wpisać według schematu (całość w jednym wierszu):

    1. Nazwisko, Imię. [Tytuł](link do repo z zadaniem 3).

Lista:

1. Budka, Kamil. [Elasticsearch](https://bitbucket.org/superUnknown/elasticsearch/overview)
1. Denejko, Wojciech. [Zadanie 3](https://bitbucket.org/wdenejko/zadanie3/overview)
1. Franckiewicz, Tomasz. [Zadanie 3](https://github.com/tfranckiewicz/nosql/tree/zadanie3)
1. Falęcki, Jacek. [Zadanie 3](https://github.com/jfalecki/projekty)
1. Hinz, Karol
1. Kalarus, Marcin
1. Massalska, Emilia
1. Mazur, Michał. [Zadanie 3](https://github.com/MajkelMatusaf/Zadanie3NoSql)
1. Michalski, Mateusz
1. Miszczykowski, Mariusz
1. Olszer, Krzysztof. [Zadanie 3](https://bitbucket.org/kolszer/mapreduce/overview)
1. Pająkowski, Adrian. [Zadanie 3](https://github.com/apajakowski/zad3)
1. Paprocki, Adam. [Zadanie 3](https://github.com/paprot/zad3nosql)
1. Pastuszka, Anna. [Zadanie 3](https://github.com/apastuszka/Zadanie3)
1. Perkowski, Maciej
1. Rawicki, Wojciech
1. Szykuła, Artur
1. Turzyński, Michał
1. Wardzińska, Justyna
1. Wasilewski, Tomasz
1. Wołek, Łukasz
1. Zduniak, Daniel. [Zadanie 3](https://github.com/dzduniak/NoSQL3)
1. Zielke, Adam


## Simple Rules for Reproducible Computations

Provide public access to scripts, runs, and results:

1. Version control all custom scripts:
  - avoid writing code
  - **write thin scripts** and use standard tools and use standard UNIX
    commands to chain things together.
1. Avoid manual data manipulation steps:
  - use a build system, for example [**make**](http://bost.ocks.org/mike/make/),
    and have all results produced automatically by build targets
  - if it’s not automated, it’s not part of the project,
    i.e. have an idea for a graph or an analysis?
    automate its generation
1. Use a markup, for example
   [**Markdown**](http://daringfireball.net/projects/markdown/syntax),
   to create reports for analysis and presentation output products.

And two more rules:

1. Record all intermediate results, when possible in standardized formats.
1. Connect textual statements to underlying results.


## Różne rzeczy

1. Do automatycznego wygenerowania spisu treści w zadaniach można użyć narzędzia
[Table of Contents Preprocessor](https://github.com/aslushnikov/table-of-contents-preprocessor).
1. Scott Chacon, Ben Straub. [Pro Git](http://git-scm.com/book/en/v2)
  - [6.2 GitHub – Contributing to a Project](http://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project)
1. [Git – kilka rzeczy dla średniozaawansowanych](Git_intermediate.md)


## Big Collections

1. [Stanford Large Network Dataset Collection](https://snap.stanford.edu/data/)
by Jure Leskovec: Online Reviews (Amazon, Movies, Beer)
1. [GetGlue and Timestamped Event Data](http://getglue-data.s3.amazonaws.com/getglue_sample.tar.gz)
(ok. 11 GB); próbka 100 jsonów [getglue101](/data/wbzyl/getglue101.json).
Dane pochodzą z lat 2007–2012 – tylko filmy i przedstawienia TV.
Przykładowe aggregacje: ilu jest różnych użytkowników
w danych? jakie jest 10 najpopularniejszych filmów i przedstawień TV?
ile jest różnych akcji?
1. [GeoNames](http://www.geonames.org/export/) i [Postal Codes](http://www.geonames.org/postal-codes/).
