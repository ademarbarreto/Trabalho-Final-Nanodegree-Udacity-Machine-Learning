# README.MD - Projeto Final - Don´t Overfitting!
##   Desafio do Kaggle de 2011

### Instalação dos pacotes necessários para rodar a aplicação:

O projeto quer a versão do **Python 3.6.4** e os seguinyes pacotes instalados:

- [anaconda](https://conda.io/docs/user-guide/install/index.html)
- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/installing.html)
- [missingno](https://anaconda.org/conda-forge/missingno)
- [XGboost](https://pypi.org/project/xgboost/)
- [LightGBM](https://github.com/Microsoft/LightGBM)
- [Catboost](pip install catboost)

É necessário para rodar o a aplicação [anaconda](https://anaconda.org/anaconda/python) e [jupyter notebook](http://jupyter.org/install).

**Numpy:** Biblioteca matemática muito poderosa, facilita muito o trabalho com arrays e tem diversas funções de álgebra, estatística e computação científica no geral. É implementada em C para garantir alto desempenho, o que é muito importante quando se trabalha com uma grande quantidade de dados.


**Pandas:** Muito útil para estruturar os dados, ajuda muito na análise e na manipulação de grande quantidade de dados. Também é implementada em C para garantir alto desempenho.

**Matplotlib:** Utilizada para plotar gráficos, é uma ótima ferramenta na análise dos dados.
SciKit Learn ou SkLearn: Possui diversos algoritmos de Machine Learning. Será a principal biblioteca que utilizaremos.




### Código da aplicação

O código do jupyter notebook chama-se **`Projeto_final.ipynb`** (arquivo notebook).Para executá-lo é necessário baixar a base de dados [Downlaod do desafio Don't Overfit! da Kaggle](https://www.kaggle.com/c/overfitting/data) e baixar o arquivo de dados 'overfitting.csv'



### Como rodar a aplicação



1. A Base de dados 'overfitting.csv tem que está no diretório **..\data\raw**. 

Numa janela windows, executar a aplicação no diretório corrente da mesma :

2.Executar o comando no diretório coResultado Modelos de Baseline¶

Modelos de Baseline¶
rrente :

```jupyter notebook projeto_final.ipynb```


### Dados


[Downlaod do desafio Don't Overfit! da Kaggle](https://www.kaggle.com/c/overfitting/data) 


### Análises realizadas - Cálculo de ROC AUC e ACURÁCIA

#### - Modelos de Baseline
#### - Modelos de One-Hot Enconde
#### - Teste dos algoritmos sem stacking
#### - Ensemble
#### - Calibração dos parametros dos algoritmos com GridSearchGridCV para o modelo escolhido
#### - Preparação do para submisão ao Kaggle com os dados para o modelo escolhido
