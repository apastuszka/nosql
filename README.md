# Technologie NoSQL

<!--
Kilka przykładowych agregacji korzystających z danych
[zipcodes](http://media.mongodb.org/zips.json) oraz
[imieniny](data/wbzyl/imieniny.csv) opisano w [Aggregation Framework Examples](Aggregations_in_JS.md).
-->

![Elasticsearch logo](images/elasticsearch-logo.png)

### Neo4j, MongoDB i Elasticsearch

Dane należy wpisać według schematu (całość w jednym wierszu):

    1. [Nazwisko, Imię](link do repo z zadaniem **Neo4j**).
       [Tytuł 1](link do repo z zadaniem **EDA**),
       [Tytuł 2](link do repo z zadaniem **Agregacje**),
       [Tytuł 3](link do repo z zadaniem **MapReduce**).

<!--
1. Barański, Kamil
1. Basiak, Paweł
1. Ćwikowski, Grzegorz
1. Dunikowski, Jacek
1. Mazur, Michał
1. Miszczykowski, Mariusz
1. Mrotek, Remigiusz
1. Paprocki, Adam
1. Rawicki, Wojciech
1. Samsoniuk, Damian
1. Turzyński, Michał
1. Wardzińska, Justyna
1. Wiergowski, Paweł
1. Zielke, Adam
-->

1. Budka, Kamil
1. Całus, Maciej
1. Denejko, Wojciech
1. Duchna, Przemysław
1. Falęcki, Jacek
1. [Franckiewicz, Tomasz](https://github.com/tfranckiewicz/nosql "neo4j private repo")
1. Gonera, Ewa
1. Hinz, Karol
1. Kalarus, Marcin
1. Massalska, Emilia
1. Michalski, Mateusz
1. Olszer, Krzysztof
1. Pająkowski, Adrian
1. Pastuszka, Anna
1. Perkowski, Maciej
1. Szykuła, Artur
1. Wasilewski, Tomasz
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
