# **Estatística - 2024** 🚀

* Projeto: **EDA (Análise Exploratória de Dados) com foco na Estatística**

* Curso: **Data Science - Santander Coders 2023 | 2º Semestre**
* Módulo: **Estatística I**
* **ADA Tech** em parceira com **Banco Santander**
* Facilitador: **Lucas Hermeto**

## Aluno: **Anderson Miranda - ID: 1116003**


----
## **1. OBJETIVO:**

Este projeto tem por objetivo realizar uma Análise Exploratória de Dados em dados reais, utilizando os recursos da disciplica de Estatística I, do Curso Data Science - Santander Coders, fazendo uso da Estatística Descritiva para gerar valor e extrair insights significativos, para aplicação em negócios reais.

#### **1.1 Objetivos Específicos:**

- Descrever estatisticamente os dados utilizados, aplicando o conhecimento da Estatística Descritiva;
- Analisar o comportamento do índice ao longo do período;
- Verificar se há correlação e em qual grau, entre a taxa de variação dos pregões diários;
- Verificar se a média da variação diária, no valor do fechamento, foi maior no período da pandemia pela COVID-19, ou após.


## **2. DATA SOURCE:**

**Mercado Financeiro**

Este estudo será realizado com dados reais de dois ativos negociados no mercado B3 - Brasil.
Os dados foram extraídos do mercado de ações através da biblioteca Yahoo Finance, correspondente ao período de Janeiro de 2020 a Dezembro de 2023.

#### **Descrição dos datasets:**
| Feature | Descrição |
|---|---|
| Adj Close | Preço de fechamento do dia, com ajuste. |
| Close | Preço de fechamento do dia, sem ajuste. |
| High | Maior preço alcançado no dia, sem ajuste. |
| Low | Menor preço alcançado no dia, sem ajuste. |
| Open | Preço de abertura do dia, sem ajuste. |
| Volume | Volume negociado na operação do dia. |

**Nota**: Todos os dados do DataFrame são do tipo float, sendo classificados como quantitativos contínuos, exceto a feature volume, que está um valor inteiro, sendo classificado como valor quantitativo discreto. 

Contudo, o index do DataFrame corresponde a data da operação, sendo uma variável do tipo datetime.

Fonte: Yahoo Finance


## **3. LIMITAÇÕES:**

Sem limites, sendo imperativo o uso das ferramentas trabalhadas na ementa do curso Santander Coders - ADA Tech. Fizemos uso de:

	Numpy
	Pandas
	Scipy
	Math
	Statsmodels
	Yfinance
	Fundamentus
	Seaborn
	Matplotlib


## **4. REFERÊNCIAS BIBLIOGRÁFICAS:**

- https://www.empiricus.com.br/explica/mercado-financeiro/
- https://blog.toroinvestimentos.com.br/trading/ciclos-de-mercado/
- https://matplotlib.org/stable/
- https://pandas.pydata.org
- https://seaborn.pydata.org/generated/seaborn.load_dataset.html


----

## **Links úteis:**

- [ADA Tech](https://ada.tech/)
- [Banco Santander - Academy](https://app.santanderopenacademy.com/pt-BR/program/bolsas-santander-santander-coders-2023-2-edicao)
- [Python](https://www.python.org)