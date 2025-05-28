Neste diretório faço, utilizando bibliotecas da linguagem Pyhon, uma analise exploratória e aplicação de alguns algoritimos de Machine Learning sobre os dados do Data set de Qualidade de Vinhos.

É um trabalho um pouco longo, mas vou tentar resumir aqui tudo o que foi realizado.

	- Importação das bibliotecas Python;
	- Leitura do dataset, arquivo CSV, através da biblioteca Pandas;
	- Analise exploratória dos dados (tamanho do dataset, tipos dos dados e a estatistica descritiva);
	- Analise grafica:
		- Nesta analise observei que quanto maior a 'qualidade' do vinho maior o valor das variveis 'pH', 'sulfatos', 'alcool';
		- Porém menor o valor das variaveis 'acidez_fixa', 'acidez_volatil', 'cloretos' e 'dioxido_enxofre_total'.
	- Gerei a matriz de correlação e filtrei quais variaveis tem mais afinidade com a variavel target (qualidade);
	- Classifiquei os vinhos como bom ou ruim com base no valor da variavel target;
	- E criei um novo dataset com as variaveis com maior afinidade com a variavel target e mais a a variavel de classificação;
	- Separei os dados de treino e teste;
	- E apliquei os algoritimos dos modelos Naive Bayes, Random Forest e Regressão Logística sobre os dados:
		- Conclusão: 
			- Accuracy Naive Bayes: 0.7170
			- Accuracy Random Forest: 0.8265
			- Accuracy Regressão Logística: 0.7320

E o modelo Random Forest apresentou melhor taxa de acerto.


--------------------------------------------------------------------------------------------------


In this directory, using Pyhon language libraries, I carry out an exploratory analysis and application of some Machine Learning algorithms on data from the Wine Quality Data Set.

It's a bit of a long work, but I'll try to summarize everything that was accomplished here.

	- Import of Python libraries;
	- Reading the dataset, CSV file, through the Pandas library;
	- Exploratory data analysis (dataset size, data types and descriptive statistics);
 	- Graphical analysis:
		- In this analysis I observed that the higher the 'quality' of the wine, the higher the value of the variables 'pH', 'sulfates', 'alcohol';
		- However, the value of the variables 'fixed_acidity', 'volatile_acidity', 'chlorides' and 'total_sulfur_dioxide' is lower.
	- I generated the correlation matrix and filtered which variables have the most affinity with the target variable (quality);
	- I classified the wines as good or bad based on the value of the target variable;
	- And I created a new dataset with the variables with the greatest affinity with the target variable and the classification variable;
	- I separated the training and testing data;
	- And I applied the algorithms of the Naive Bayes, Random Forest and Logistic Regression models to the data:
  		- Conclusion:
  			- Accuracy Naïve Bayes: 0.7170
  			- Accuracy Random Forest: 0.8265
  			- Accuracy Logistic Regression: 0.7320

The Random Forest model showed a better hit rate.
