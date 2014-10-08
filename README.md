# Technologie NoSQL

![Elasticsearch](images/elasticsearch-logo.png)

Kilka przykładowych agregacji korzystających z danych
[zipcodes](http://media.mongodb.org/zips.json) oraz
[imieniny](data/wbzyl/imieniny.csv) opisano w [Aggregation Framework Examples](Aggregations_in_JS.md).


### Neo4j, MongoDB i Elasticsearch

Dane należy wpisać według schematu (całość w jednym wierszu):

    1. [Nazwisko, Imię](link do repozytorium z rozwiązaniem zadania Neo4j na GitHub).
       [Tytuł](link do repozytorium z rozwiązaniem zadania Agregacje na GitHub),

1. Blum, Bartosz
1. Chylicki, Adrian
1. Dąbrowski, Krzysztof
1. Dziemiński, Grzegorz
1. Eggert, Marek
1. Jakubek, Daniel
1. Kowalska, Joanna
1. Krajnik, Martyna
1. Krzychowiec, Rafał
1. Kupniewski, Rafał
1. Lipiński, Michał
1. Mroczkowski, Jacek
1. Ponieważ, Paweł
1. Portalski, Sylwester
1. Ruchlewicz, Natalia
1. Zabrocki, Adam
1. Mocarska, Karolina
1. Neubauer, Kajetan
1. Nowak, Piotr
1. Patelczyk, Daniel
1. Schachta, Mateusz


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
