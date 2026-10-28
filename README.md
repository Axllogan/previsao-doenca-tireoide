Classificação de Hipotireoidismo

Projeto de Ciência de Dados desenvolvido em Python para classificar registros da base de hipotireoidismo.

Objetivo

Analisar os dados, preparar as variáveis e avaliar um modelo de classificação para distinguir as classes P e N.

Base de dados

A base utilizada contém 3.772 registros e 30 colunas antes da limpeza.

Foram analisados valores ausentes, registros duplicados e a distribuição das classes.

Metodologia

O trabalho utiliza:

Python, pandas e matplotlib para análise dos dados;

scikit-learn para preparação e classificação;

DummyClassifier como modelo de referência;

Regressão Logística para classificação;

Matriz de confusão e métricas de avaliação.

Resultados

A regressão logística obteve:

Acurácia: 96,7%;

Acurácia balanceada: 95,7%;

Recall da classe N: 94,5%;

Precisão da classe N: 71,9%.

O modelo deixou de identificar quatro registros da classe N e classificou 27 registros P como N.

Arquivos

Trabalho_Hipotireoidismo.ipynb: análise, códigos, gráficos e resultados.

Base_M43_Pratique_Hypothyroid.csv: base utilizada, caso disponibilizada no repositório.

Como executar

Baixe o notebook e a base de dados.

Mantenha os dois arquivos na mesma pasta.

Abra o notebook no Jupyter Notebook.

Execute as células na ordem apresentada.

Limitações

O modelo foi avaliado com uma divisão de treino e teste da base utilizada. Não foi testado em outras bases.
