# ETL Hackathon

### ETL 
Os dados brutos existem em vários lugares e formas. Para realizar qualquer tipo de análise de dados, esses dados precisam ser limpos e estruturados.  Os processos de pipeline de dados **ETL – Extrair, Transformar e Carregar** é um conceito central em engenharia de dados, garantindo que os dados sejam consistentes, mantenham sua integridade e, no entanto, se esforcem para automatizar a disputa de dados. Sem uma estrutura de dados consistente e robusta, é quase impossível realizar qualquer análise significativa.



### Objetivo
Uma empresa de streaming de vídeo, decidiu patrocinar um *hackathon*, onde os participantes tentam prever quais filmes de baixo orçamento que serão lançados se tornarão populares. Os participantes de um hackathon precisam de dados limpos para realizar análises de seus algoritmos. Para fornecer um conjunto de dados organizado e limpo, este projeto se concentra no processo *ETL** ou **Extrair, transformar e carregar** e inclui o seguinte:

-	**Extraindo** dados de duas fontes diferentes.
    - web scrape do site da Wikipedia para todos os filmes lançados desde 1990
    - dados do Kaggle para dados de classificação.
-	**Transformar** dados usando o Jupyter Notebook, Python, Pandas e Python RegEx.
-	**Carga** dos dados usando PostgreSQL e pgAdmin para hospedar o conjunto de dados limpo final.


### ETL 
ELT, which stands for “Extract, Load, Transform,” is another type of data integration process, similar to its counterpart ETL, “Extract, Transform, Load”. This process moves raw data from a source system to a destination resource, such as a data warehouse.


### Objective
A video streaming company has decided to sponsor a *hackathon*, where participants try to predict which low-budget movies that will be released will become popular. Participants in a hackathon need clean data to perform analysis of their algorithms. To provide an organized and clean dataset, this project focuses on the *ETL** or **Extract, Transform, and Load** process and includes the following:

- **Extracting** data from two different sources.
    - web scrape from Wikipedia site for all movies released since 1990
    - Kaggle data for ranking data.
- **Transform** data using Jupyter Notebook, Python, Pandas and Python RegEx.
- **Load** the data using PostgreSQL and pgAdmin to host the final clean dataset.




### Fontes/Sources: 

Wikipedia web scrape [JSON file](Resources/wikipedia-movies.json)
Kaggle [Kaggle.com](https://www.kaggle.com/rounakbanik/the-movies-dataset) - arquivos: movies_metadata.csv and ratings.csv

