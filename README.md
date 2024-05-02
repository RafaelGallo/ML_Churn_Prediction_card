# Machine learning Churn Prediction Telecon

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
[![author](https://img.shields.io/badge/author-RafaelGallo-red.svg)](https://github.com/RafaelGallo?tab=repositories) 
[![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-374/) 
[![](https://img.shields.io/badge/R-3.6.0-red.svg)](https://www.r-project.org/)
[![](https://img.shields.io/badge/ggplot2-white.svg)](https://ggplot2.tidyverse.org/)
[![](https://img.shields.io/badge/transformers-white.svg)](https://huggingface.co/docs/transformers)
[![](https://img.shields.io/badge/Google_Cloud-white.svg)](https://huggingface.co/docs/transformers)
[![](https://img.shields.io/badge/dplyr-blue.svg)](https://dplyr.tidyverse.org/)
[![](https://img.shields.io/badge/readr-green.svg)](https://readr.tidyverse.org/)
[![](https://img.shields.io/badge/ggvis-black.svg)](https://ggvis.tidyverse.org/)
[![](https://img.shields.io/badge/Shiny-red.svg)](https://shiny.tidyverse.org/)
[![](https://img.shields.io/badge/plotly-green.svg)](https://plotly.com/)
[![](https://img.shields.io/badge/XGBoost-red.svg)](https://xgboost.readthedocs.io/en/stable/#)
[![](https://img.shields.io/badge/Tensorflow-orange.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/Keras-red.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/CUDA-gree.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/Caret-orange.svg)](https://caret.tidyverse.org/)
[![](https://img.shields.io/badge/Pandas-blue.svg)](https://pandas.pydata.org/) 
[![](https://img.shields.io/badge/Matplotlib-blue.svg)](https://matplotlib.org/)
[![](https://img.shields.io/badge/Seaborn-green.svg)](https://seaborn.pydata.org/)
[![](https://img.shields.io/badge/Matplotlib-orange.svg)](https://scikit-learn.org/stable/) 
[![](https://img.shields.io/badge/Scikit_Learn-green.svg)](https://scikit-learn.org/stable/)
[![](https://img.shields.io/badge/Numpy-white.svg)](https://numpy.org/) 

# Descrição projeto Churn Telecon
## Problema de Negócio: Churn de Cartões de Crédito e Aplicação de Machine Learning de Classificação
O churn de cartões de crédito é uma preocupação constante para as instituições financeiras, pois a perda de clientes pode resultar em uma diminuição significativa da receita e na perda de participação de mercado. Diante desse desafio, as empresas buscam compreender os fatores que levam os clientes a encerrarem seus cartões de crédito e desenvolver estratégias eficazes para prevenir o churn. Uma abordagem promissora para lidar com o churn de cartões de crédito é a aplicação de técnicas de machine learning de classificação. Essas técnicas permitem prever se um cliente é propenso a cancelar seu cartão de crédito com base em uma variedade de variáveis, como histórico de transações, comportamento de pagamento, interações com o serviço ao cliente e informações demográficas.

A aplicação de machine learning de classificação no contexto do churn de cartões de crédito envolve várias etapas. Primeiro, é necessário coletar e preparar os dados relevantes para a modelagem, garantindo que eles estejam limpos, completos e prontos para análise. Isso pode envolver a integração de dados de várias fontes, a seleção de características relevantes e a codificação de variáveis categóricas.

Em seguida, os dados preparados são divididos em conjuntos de treinamento e teste, e um algoritmo de classificação, como regressão logística, árvores de decisão, florestas aleatórias ou redes neurais, é treinado nos dados de treinamento. Durante o treinamento, o algoritmo aprende os padrões nos dados que estão associados ao churn e ajusta seus parâmetros para otimizar o desempenho do modelo. Após o treinamento, o modelo é avaliado usando os dados de teste para verificar sua capacidade de generalização para novos dados. Isso envolve a análise de métricas de desempenho, como precisão, recall, F1-score e área sob a curva ROC, para determinar quão bem o modelo é capaz de prever o churn. Com base na avaliação do modelo, é possível ajustar os parâmetros do algoritmo e refinar o modelo para melhorar sua precisão e generalização. Uma vez que um modelo satisfatório tenha sido desenvolvido, ele pode ser implantado em produção e usado para prever o churn em tempo real, permitindo que as empresas identifiquem clientes em risco e implementem medidas proativas de retenção.

Em resumo, a aplicação de machine learning de classificação no contexto do churn de cartões de crédito oferece uma abordagem poderosa e eficaz para prevenir a perda de clientes e manter a lucratividade a longo prazo. Ao prever o churn com precisão, as instituições financeiras podem tomar medidas proativas para reter clientes, melhorar a satisfação do cliente e impulsionar o crescimento do negócio.longo prazo.

## Dicionário de dados

- **CLIENTNUM:** Número de identificação único para cada cliente.
- **Attrition_Flag:** Indica se o cliente cancelou o cartão de crédito (churn). Pode ter valores como "Existing Customer" (Cliente Existente) ou "Attrited Customer" (Cliente Cancelado).
- **Customer_Age:** Idade do cliente.
- **Gender:** Gênero do cliente.
- **Dependent_count:** Número de dependentes do cliente.
- **Education_Level:** Nível de educação do cliente.
- **Marital_Status:** Estado civil do cliente.
- **Income_Category:** Categoria de renda do cliente.
- **Card_Category:** Categoria do cartão de crédito (por exemplo, "Blue", "Silver", "Gold", "Platinum").
- **Months_on_book:** Número de meses desde que o cliente abriu a conta.
- **Total_Relationship_Count:** Número total de produtos bancários que o cliente possui.
- **Months_Inactive_12_mon:** Número de meses em que o cliente esteve inativo nos últimos 12 meses.
- **Contacts_Count_12_mon:** Número de contatos que o cliente teve com a instituição nos últimos 12 meses.
- **Credit_Limit:** Limite de crédito do cliente.
- **Total_Revolving_Bal:** Saldo total de crédito rotativo do cliente.
- **Avg_Open_To_Buy:** Média do valor disponível para compra.
- **Total_Amt_Chng_Q4_Q1:** Mudança percentual no valor da transação do último trimestre para o primeiro trimestre.
- **Total_Trans_Amt:** Valor total das transações feitas pelo cliente.
- **Total_Trans_Ct:** Total de transações feitas pelo cliente.
- **Total_Ct_Chng_Q4_Q1:** Mudança percentual no número de transações do último trimestre para o primeiro trimestre.
- **Avg_Utilization_Ratio:** Razão média de utilização do crédito.
- **Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1:** Valor derivado do modelo de Naive Bayes para prever o churn (não utilizado para análise).
- **Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_2:** Outro valor derivado do modelo de Naive Bayes para prever o churn (não utilizado para análise).

## Stack utilizada

**Ciência de dados:** Python, Sklearn, Transforns, Google Cloud

## Variáveis de Ambiente

Para preparar o ambiente Python deste projeto, instale as seguintes bibliotecas utilizando o gerenciador de pacotes conda:


## Instalação

Instalação das bibliotecas para esse projeto no python.

```bash
  conda install pandas 
  conda install scikitlearn
  conda install numpy
  conda install scipy
  conda install matplotlib
  conda install transformers
  conda install torch

  python==3.6.4
  numpy==1.13.3
  scipy==1.0.0
  matplotlib==2.1.2
  transformers==1.1.0
  torch==2.3.0
```
A criação de um ambiente virtual para este projeto, o que facilitará a administração e evitará conflitos de dependências. Se precisar de orientações sobre como criar ambientes virtuais em Python, consulte este guia.

Para criar um ambiente virtual no diretório do seu projeto, execute o seguinte comando:

```bash
python -m venv .env
```
Para ativar o ambiente virtual, utilize:
```bash
source .env/bin/activate
```
Agora, você pode instalar o scikitlearn com o seguinte comando:

```bash
pip install scikitlearn
```
Se estiver trabalhando apenas com CPU, você pode instalar o scikitlearn correspondente em uma única linha. 
```bash
pip install scikitlearn
```

## Dataset Churn telco customer
[Base_dados](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)
