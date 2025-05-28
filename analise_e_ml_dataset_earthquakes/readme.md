Neste diretório faço, utilizando bibliotecas da linguagem Pyhon, uma analise exploratória e aplicação do algoritimo Árvore de Decisão no Dataset Earthquakes, obtido do site Kaggle.

O link para este Dataset também se encontra no final deste readme.

 - Primeiro realizo a importação das bibliotecas;
 - Abro o Dataset, arquivo CSV, utilizando a bibliotecas Pandas;
 - Analiso os dados, faço uma limpeza na quantidade de colunas e registros com valores nulos;
 - E aplico o algoritimo Árvore de Decisão (DecisionTreeClassifier):
  - Nos parâmetros do algoritimo setei apenas a quantidade de nós da arvore para 3:
   - Com os dados de treino observei uma Acuracia de 98%;
   - E no grafico do modelo pude observar que na grande maioria os eventos com as seguintes caracteristica não foram considerados terremotos:
    - Erro de pronfundidade com valor maior que 31.285;
    - E profundidade com valor menor ou igual a -0.065.


--------------------------------------------------------------------------------------------------


In this directory, using Pyhon language libraries, I perform an exploratory analysis and application of the Decision Tree algorithm to the Earthquakes Dataset, obtained from the Kaggle website.

The link to this Dataset is also at the end of this readme.

 - First I import the libraries;
 - In addition to the Dataset, CSV file, using Pandas libraries;
 - I analyze the data, clean the number of columns and records with null values;
 - And applies the Decision Tree algorithm:
  - In the algorithm settings, I only set the number of nodes in the tree to 3:
   - With the training data I observed an accuracy of 98%;
   - And in the model graph I could see that the vast majority of events with the following characteristics were not considered earthquakes:
    - Depth error with a value greater than 31.285;
    - And depth with a value less than or equal to -0.065.


--------------------------------------------------------------------------------------------------

https://www.kaggle.com/datasets/thedevastator/uncovering-geophysical-insights-analyzing-usgs-e

