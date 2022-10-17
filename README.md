# ETL Hackathon

Os dados brutos existem em vários lugares e formas. Para realizar qualquer tipo de análise de dados, esses dados precisam ser limpos e estruturados.  Os processos de pipeline de dados **ETL – Extrair, Transformar e Carregar** é um conceito central em engenharia de dados, garantindo que os dados sejam consistentes, mantenham sua integridade e, no entanto, se esforcem para automatizar a disputa de dados. Sem uma estrutura de dados consistente e robusta, é quase impossível realizar qualquer análise significativa.



### Proposta
Uma empresa de streaming de vídeo, decidiu patrocinar um *hackathon*, onde os participantes tentam prever quais filmes de baixo orçamento que serão lançados se tornarão populares. Os participantes de um hackathon precisam de dados limpos para realizar análises de seus algoritmos. Para fornecer um conjunto de dados organizado e limpo, este projeto se concentra no processo *ETL** ou **Extrair, transformar e carregar** e inclui o seguinte:

-	**Extraindo** dados de duas fontes diferentes.
    - web scrape do site da Wikipedia para todos os filmes lançados desde 1990
    - dados do Kaggle para dados de classificação.
-	**Transformar** dados usando o Jupyter Notebook, Python, Pandas e Python RegEx.
-	**Carga** dos dados usando PostgreSQL e pgAdmin para hospedar o conjunto de dados limpo final.



### Fontes: 

Wikipedia web scrape [JSON file](Resources/wikipedia-movies.json)
Kaggle [Kaggle.com](https://www.kaggle.com/rounakbanik/the-movies-dataset) - arquivos: movies_metadata.csv and ratings.csv

