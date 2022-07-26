# Classisficador Utilizando Árvore de Decisão

Uma árvore de decisão é um algoritmo de [Machine Learning](https://www.ibm.com/br-pt/cloud/learn/machine-learning) supervisionado que é utilizado para classificação e para regressão. 
Isto é, pode ser usado para prever categorias discretas (sim ou não, por exemplo) e para prever valores numéricos (o valor do lucro em reais).

###  Objetivo do Classificador

O dataset jogadores.csv contém dados de 150 jogadores de futebol, que estão divididos entre atacantes e defensores.
Para cada jogador, registrou-se: idade, altura, técnica, passe, chute, força e velocidade. 
As características (exceto a idade e altura) são valores discretos entre 1 e 100, onde valores maiores são melhores.
A classe (atacante ou defensor) dos primeiros 120 atletas é conhecida, e a partir destas informações, deseja-se descobrir a classe de outros 30 atletas.

###  Ferramentas Utilizadas

O classisficador foi feito utilizando a implementação do algoritmo da Árvore de Decisão da Biblioteca [Sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier.score) do Python.

- [Python](https://docs.python.org/3/).

- [Pandas](https://pandas.pydata.org/docs/user_guide/dsintro.html#dataframe).

- [Numpy](https://numpy.org/doc/stable/reference/index.html).

- [Jupyter Notebook](https://jupyter.org/).


###  Estrutura do Repositorio
