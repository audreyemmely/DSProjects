# Desafio - Análise de sentimento
Quando uma empresa deseja entender o que estão falando sobre ela e qual a reputação de seus produtos online, uma das formas de se fazer isso é utilizando machine learning, assim como sua subárea chamada Deep Learning. Nesse sentido, uma das técnicas recomendadas é a análise de sentimentos, que consiste em extrair informações de textos a partir de linguagem natural.

Apesar de não ser a única, a análise de sentimentos é a ferramenta de classificação de textos mais comum que analisa uma mensagem recebida e informa seu sentimento implícito. 

## Descrição
Elabore um serviço que seja capaz de detectar se uma determinada frase inserida corresponde a um destes sentimentos (felicidade, tristeza e raiva)

Exemplo:

> Não quero saber de nada, te odeio! ---> raiva

> Sinto sua falta ---> tristeza

## Sobre o arquivo CSV
O arquivo contém 2 colunas preenchidas com frases e sentimentos, todas as frases foram retiradas de diferentes websites.

## Sobre a utilização do projeto
Para utilizar o projeto, primeiramente, é preciso clonar o repositório. Abra o seu terminal, configure o caminho onde você deseja salvar o repositório na sua máquina local e digite o seguinte comando:

`git clone https://github.com/audreyemmely/DSProjects.git`

Em seguida, acesse a pasta `analise-sentimento` e abra o arquivo `.ipynb` com o [Google Colab](https://colab.research.google.com/) ou algum outro ambiente que suporte essa extensão.

Para um ambiente local, como o [Jupyter](https://jupyter.org/install), por exemplo, faz-se necessário a instalação das seguintes bibliotecas, caso não estejam instaladas:
```
pandas
scikit-learn
```
Saiba como instalá-las aqui:

[Pandas](https://pandas.pydata.org/docs/getting_started/install.html)

[Scikit-learn](https://scikit-learn.org/stable/install.html)

## Referências
[Análise de Sentimentos com Machine Learning](https://www.datageeks.com.br/analise-de-sentimentos/)

[6 passos fáceis para aprender o algoritmo Naive Bayes (com o código em Python)](https://www.vooo.pro/insights/6-passos-faceis-para-aprender-o-algoritmo-naive-bayes-com-o-codigo-em-python/#:~:text=Existem%20tr%C3%AAs%20tipos%20de%20modelo,problema%20de%20classifica%C3%A7%C3%A3o%20de%20texto.)

[O que é acurácia? Entenda o conceito e sua importância](https://blog.idwall.co/o-que-e-acuracia/)

[Minerando dados](https://github.com/minerandodados/mdrepo/blob/master/Classifica%C3%A7%C3%A3o_tweets.ipynb)

[Scikit Learn - User Guide](https://scikit-learn.org/stable/user_guide.html)

[Pandas crosstab](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.crosstab.html)
