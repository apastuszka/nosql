# Technologie NoSQL

<!--
Kilka przykładowych agregacji korzystających z danych
[zipcodes](http://media.mongodb.org/zips.json) oraz
[imieniny](data/wbzyl/imieniny.csv) opisano w [Aggregation Pipeline Examples](Aggregations_in_JS.md).
-->

![Elasticsearch logo](images/elasticsearch-logo.png)


Terminy rozliczania się z [zadań](http://wbzyl.inf.ug.edu.pl/nosql/zadania):

| zadanie | opis    | termin     |
|---------|---------|------------|
| 0.      | Neo4j   | 25.10.2014 |
| 1 a-c   | EDA     | 15.11.2014 |
| 1 d.    | GeoJSON | 29.11.2014 |


### Neo4j, MongoDB i Elasticsearch

Dane należy wpisać według schematu (całość w jednym wierszu):

    1. [Nazwisko, Imię](link do repo z zadaniem **Neo4j**).
       [Tytuł 1](link do repo z zadaniem **EDA** + **GeoJSON**),
       [Tytuł 2](link do repo z zadaniem **Agregacje**),
       [Tytuł 3](link do repo z zadaniem **MapReduce**).

<!--
1. Dunikowski, Jacek 25.10
1. Mazur, Michał 25.10
1. Miszczykowski, Mariusz 25.10
1. Mrotek, Remigiusz 25.10
1. Paprocki, Adam 25.10
1. Rawicki, Wojciech 25.10
1. Samsoniuk, Damian 25.10
1. Wiergowski, Paweł 25.10
-->

1. [Franckiewicz, Tomasz](https://github.com/tfranckiewicz/nosql "neo4j private repo")
    - [Zadanie 1](https://github.com/tfranckiewicz/nosql/tree/zadanie1)
1. [Kalarus, Marcin](https://github.com/mkalarus/Neo4j-zal "neo4j repo")
1. [Massalska, Emilia](https://github.com/emassalska/neo4j "neo4j")
1. [Michalski, Mateusz](https://github.com/matismatis93/neo4j "neo4j private repo")
1. [Olszer, Krzysztof](https://github.com/kolszer/Neo4j)
1. [Pająkowski, Adrian](https://github.com/apajakowski/neo4j "neo4j public repo")
1. [Pastuszka, Anna](https://github.com/apastuszka/Neo4j "Baza Neo4j")

----

1. Basiak, Paweł
1. Barański, Kamil
1. Budka, Kamil 25.10
1. Ćwikowski, Grzegorz
1. Całus, Maciej
1. Denejko, Wojciech 25.10
1. Duchna, Przemysław
1. Falęcki, Jacek 25.10
1. Gonera, Ewa
1. Hinz, Karol 25.10
1. Perkowski, Maciej
1. Szykuła, Artur
1. Turzyński, Michał
1. Wardzińska, Justyna
1. Wasilewski, Tomasz 25.10
1. Zielke, Adam
1. Zduniak, Daniel


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
1. Jak sobie radzić z [nieczystymi committami](Git_Pull_Requests.md)?


## Big Collections

1. [Stanford Large Network Dataset Collection](https://snap.stanford.edu/data/)
by Jure Leskovec: Online Reviews (Amazon, Movies, Beer)
1. [GetGlue and Timestamped Event Data](http://getglue-data.s3.amazonaws.com/getglue_sample.tar.gz)
(ok. 11 GB); próbka 100 jsonów [getglue101](/data/wbzyl/getglue101.json).
Dane pochodzą z lat 2007–2012 – tylko filmy i przedstawienia TV.
Przykładowe aggregacje: ilu jest różnych użytkowników
w danych? jakie jest 10 najpopularniejszych filmów i przedstawień TV?
ile jest różnych akcji?
