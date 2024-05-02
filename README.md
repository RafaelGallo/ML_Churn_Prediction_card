# Machine learning Churn Prediction card

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

![cap](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/buildings-fog.jpg)

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

## Análise dados 

## Gráfico Distribuição da Variável Alvo
![a1](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/001.png)

Aqui, essa variável representa as colunas, como churn e não churn, que são essenciais como atributos para treinar um modelo de machine learning. A coluna alvo, neste contexto, refere-se à variável que o modelo tentará prever ou classificar, como churn, que é crucial para a análise e previsão de comportamento de clientes.

## Gráfico correlação Matriz de Correlação
![a2](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/002.png)

O total de transações, o saldo rotativo total e a mudança total no número têm uma correlação negativa moderada com o alvo. Isso faz total sentido. Quanto menos transações um cliente faz, mais provável é que ele cancele. Além disso, clientes com saldos rotativos mais baixos e menos variação em seus números de transações são propensos a cancelar devido à inatividade.  A idade do cliente e os meses de permanência no livro estão fortemente correlacionados positivamente. Quanto mais velho é um cliente, mais tempo ele passa consumindo os serviços de cartão de crédito do banco e vice-versa. Assim, a empresa deve concentrar seus esforços em manter os clientes antigos e leais e aumentar a permanência dos mais jovens. O limite de crédito e a taxa média de utilização estão moderadamente correlacionados negativamente. Quanto maior o limite de crédito do cliente, menor é a taxa média de utilização. O saldo rotativo total e a taxa média de utilização estão fortemente correlacionados positivamente. Isso faz sentido.  À medida que um cliente usa mais seu cartão de crédito, ele terá que pagar saldos rotativos mais altos. Curiosamente, o gênero tem uma correlação positiva moderada com o limite de crédito. Isso pode indicar que os clientes do sexo masculino tendem a ter limites de crédito mais altos do que os do sexo feminino. Algumas características que estão naturalmente relacionadas são altamente correlacionadas, como esperado. Este é o caso do valor total da transação e do total de transações. 
Ao construir modelos lineares, devemos nos preocupar com problemas de multicolinearidade, que ocorrem quando duas ou mais variáveis independentes estão altamente correlacionadas. Embora seja diagnosticado com o fator de inflação da variância, observar a correlação de Pearson entre pares pode nos indicar esse problema. Este é o caso aqui. No entanto, uma vez que vou me concentrar no poder preditivo, usando algoritmos mais robustos como o LightGBM, não me preocuparei com isso agora. Curiosamente, o valor médio aberto para comprar e o limite de crédito estão perfeitamente correlacionados positivamente.  Isso significa que essas duas variáveis têm um relacionamento linear forte e consistente na mesma direção. Isso faz sentido, já que "aberto para comprar" significa o valor restante em seu cartão de crédito para usar e o limite significa o valor usado que ainda não foi pago. Como apresentam essa correlação perfeita, uma delas se torna redundante. Assim, vou descartar o "avg_open_to_buy" na etapa de modelagem porque o "credit_limit" é mais informativo.

## Subplots relações da correlação
![a3](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/006.png)

Curiosamente, o limite de crédito e a taxa média de utilização apresentam uma relação de decrescimento exponencial! Isso indica que, à medida que o limite de crédito aumenta, a taxa média de utilização diminui em uma taxa exponencial. Portanto, clientes com limites de crédito mais altos usam seus cartões de crédito menos frequentemente. Essa dinâmica sugere que existe uma relação não linear entre o limite de crédito e o uso do cartão, com uma diminuição mais acentuada na taxa de utilização à medida que o limite de crédito aumenta. Isso pode ser um insight valioso para o banco entender os padrões de gastos de seus clientes e ajustar suas estratégias de gerenciamento de crédito e retenção de clientes.

## Distribuição do Índice de Engajamento do Cliente
![a4](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/007.png)

Neste gráfico, observamos o cancelamento de cartões de crédito, com destaque para a categoria que apresenta um número significativo de cancelamentos. Essa observação sugere que os clientes que possuem cartões estão mais propensos a cancelar seus cartões, indicando possíveis casos de churn. Essa análise ressalta a importância de entender os motivos por trás desses cancelamentos e de implementar medidas para melhorar a retenção de clientes nessa categoria específica. Além disso, enfatiza a necessidade de um acompanhamento proativo dos clientes "Platinum" para garantir sua satisfação e fidelidade, visando manter uma base de clientes estável e lucrativa.

## Gráfico Distribuição do Limite de Crédito com Indicação de Churn
![a5](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/008.png)

**Análise:** Neste indicador, estamos analisando os casos relacionados ao limite de crédito dos cartões. Podemos observar que clientes com limites de até 1000 estão cancelando o cartão, o que reflete casos de churn. Além disso, podemos notar a presença de uma linha vermelha, que representa os clientes ativos com limite de crédito de até 30.000. Isso sugere uma variedade de cenários possíveis, onde diferentes fatores podem influenciar a decisão de pagar ou cancelar o cartão de crédito. Por exemplo, o pagamento do cartão pode ser influenciado por fatores como o salário mensal, os gastos regulares e as despesas familiares. É interessante notar que casais podem ter um limite de cartão mais alto do que uma pessoa solteira, refletindo diferentes estruturas de renda e necessidades de gastos. Portanto, entender essas nuances é fundamental para personalizar estratégias de retenção de clientes e promover a fidelidade dos clientes, considerando não apenas o limite de crédito, mas também outros fatores contextuais que impactam o comportamento do cliente.

## Feature engineering

Neste contexto, empreguei a técnica de feature engineering para otimizar o desempenho do modelo, especificamente transformando variáveis categóricas em numéricas por meio do Label Encoder. O Label Encoder é uma ferramenta essencial em ciência de dados, frequentemente utilizada para converter variáveis categóricas em representações numéricas. Quando lidamos com conjuntos de dados, é comum encontrar variáveis categóricas que descrevem categorias textuais, como "alto", "médio" e "baixo", ou "sim" e "não". No entanto, a maioria dos algoritmos de machine learning requer entradas numéricas para operar de forma eficaz. Portanto, é imperativo transformar essas variáveis categóricas em formatos numéricos antes de alimentá-las aos modelos. O processo de transformação realizado pelo Label Encoder atribui um valor numérico único a cada categoria presente na variável categórica. Por exemplo, as categorias "alto", "médio" e "baixo" podem ser codificadas como 1, 2 e 3, respectivamente. Isso permite que os algoritmos de machine learning processem e compreendam melhor as informações contidas nessas variáveis, contribuindo para uma modelagem mais precisa e eficiente. Além disso, ao converter variáveis categóricas em numéricas, evitamos distorções indesejadas que poderiam surgir se tratássemos diretamente as categorias como números, sem atribuir significados adequados a elas. Dessa forma, o Label Encoder desempenha um papel fundamental na preparação dos dados para análise e modelagem, facilitando a extração de insights valiosos e a tomada de decisões fundamentadas com base nos resultados obtidos.


# Machine learning 

Aqui, na quinta etapa do projeto, estou focado na implementação de modelos de machine learning. Estou desenvolvendo oito algoritmos distintos para análise, que incluem Regressão Logística, Naive Bayes, Árvore de Decisão, Random Forest, AdaBoost, Gradient Boosting, XGBoost e LightGBM. Essa diversidade de algoritmos nos permite explorar diferentes abordagens e técnicas para o problema em questão. Durante o processo de treinamento, acompanhamos de perto o desempenho de cada modelo, buscando identificar aquele que melhor se adapta aos dados e oferece as previsões mais precisas. Este estágio é crucial, pois nos permite avaliar e comparar o desempenho de cada algoritmo, selecionando assim o modelo de machine learning mais eficaz para a nossa aplicação específica.Ao longo deste estágio, estou desenvolvendo e treinando oito algoritmos de machine learning distintos. Esses algoritmos foram cuidadosamente selecionados para abranger uma ampla gama de técnicas e características, visando capturar a complexidade e nuances dos dados:s informadas.

**Regressão Logística:** Um modelo linear usado para resolver problemas de classificação binária.

**Naive Bayes:** Um modelo probabilístico baseado no teorema de Bayes, adequado para problemas de classificação com características independentes.

**Árvore de Decisão:** Um modelo que utiliza uma estrutura de árvore para representar regras de decisão hierárquicas.

**Random Forest:** Uma técnica de ensemble learning que combina múltiplas árvores de decisão para melhorar a precisão e a robustez do modelo.

**AdaBoost:** Outro algoritmo de ensemble learning que ajusta iterativamente os pesos das observações para focar nos casos mais difíceis.

**Gradient Boosting:** Uma técnica de ensemble learning que constrói árvores de decisão sequencialmente, otimizando um critério de perda específico.

**XGBoost:** Uma implementação eficiente de gradient boosting, conhecida por sua velocidade e desempenho superior.

**LightGBM:** Outra implementação de gradient boosting, projetada para treinar modelos rapidamente e com uso eficiente de memória.


## Avaliação modelo machine learning

Cada um desses algoritmos está sendo treinado e ajustado utilizando as melhores práticas de machine learning. Após o treinamento, avaliamos o desempenho de cada modelo em um conjunto de validação, utilizando métricas adequadas ao nosso problema, como precisão, recall, F1-score, curva ROC, curentre outras. 

## Gráfico curva ROC modelo 

![f0](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/005.png)

A análise da curva ROC revelou que o modelo LightGBM apresentou uma notável aderência em comparação com outros modelos. A curva ROC é uma ferramenta fundamental na avaliação da capacidade de classificação de um modelo, mostrando a taxa de verdadeiros positivos em relação à taxa de falsos positivos em vários pontos de corte. No caso específico do LightGBM, sua curva ROC exibiu uma trajetória que indicava uma excelente capacidade de discriminação entre as classes positivas e negativas, com uma área sob a curva significativamente superior em comparação com outros algoritmos avaliados. Essa superioridade na curva ROC sugere que o LightGBM é altamente eficaz na classificação precisa dos dados, proporcionando uma separação clara entre as instâncias positivas e negativas. 

## Gráfico Matriz confussão

![f2](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/004.png)

Esses resultados representam a avaliação do desempenho de um modelo de classificação em um problema de churn em cartão de crédito. Aqui está uma análise mais detalhada:

**-Verdadeiros Positivos (TP): 1672**
Estes são os clientes que o modelo previu corretamente como propensos a churn (cancelamento) e que realmente cancelaram seus cartões de crédito. Essa é uma métrica crucial, pois indica a capacidade do modelo de identificar com precisão os clientes que estão em risco de deixar a empresa.

**-Verdadeiros Negativos (TN): 290**
Esses são os clientes que o modelo previu corretamente como não propensos a churn e que realmente permaneceram com seus cartões de crédito. Isso reflete a precisão do modelo em reconhecer os clientes satisfeitos e confiantes que continuarão usando os serviços da empresa.

**-Falsos Positivos (FP): 27**
Aqui temos os casos em que o modelo previu incorretamente que os clientes não cancelariam seus cartões de crédito, mas eles acabaram cancelando. Isso pode representar uma perda de oportunidade de retenção para a empresa, pois esses clientes poderiam ter sido alvo de ações preventivas para evitar o churn.

**-Falsos Negativos (FN): 37**
Estes são os clientes que o modelo previu erroneamente como não propensos a churn, mas que acabaram cancelando seus cartões de crédito. Isso indica uma falha do modelo em identificar corretamente os clientes em risco, o que pode resultar em perda de receita e diminuição da satisfação do cliente.

A análise dessas métricas permite uma compreensão abrangente do desempenho do modelo na previsão do churn em cartão de crédito, destacando suas áreas de sucesso e possíveis pontos de melhoria. Isso pode ajudar a empresa a direcionar estratégias eficazes de retenção de clientes e aprimorar seu serviço para reduzir o churn e manter a satisfação do cliente em níveis elevados.

## Feature Importance

Nesta etapa crucial da análise, exploramos a importância das features para entender quais variáveis têm maior impacto na predição do nosso modelo. A análise da importância das features oferece insights valiosos sobre quais aspectos dos dados são mais relevantes para a tomada de decisões do modelo.Ao aplicar a análise de feature importance podemos identificar as features que têm maior aderência e impacto nas previsões do modelo. Essas features destacam-se por sua capacidade de influenciar significativamente as decisões do modelo, fornecendo informações críticas sobre os principais impulsionadores do fenômeno que estamos estudando.

## Gráfico Feature Importance modelo LightGBM

![f1](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/009.png)

Aqui podemos observar a feature importance, destacando "Total_Trans_Amt", que representa o valor total das transações realizadas pelo cliente. Esse aspecto é crucial, pois revela a importância dessa variável em relação às demais. A análise da feature importance nos permite compreender quais variáveis têm maior influência no modelo, fornecendo insights valiosos sobre os drivers subjacentes ao comportamento dos clientes. Portanto, ao identificar "Total_Trans_Amt" como a feature mais importante, ganhamos uma compreensão mais profunda dos padrões de transação e do valor que essas transações agregam ao contexto do modelo

## Seleção do Melhor Modelo

Ao final deste processo, compararemos o desempenho de todos os modelos e selecionaremos aquele que apresentar os melhores resultados de acordo com nossos critérios de avaliação. Essa escolha será fundamentada não apenas na métrica de desempenho, mas também na interpretabilidade do modelo, sua capacidade de generalização e sua adequação aos requisitos do problema em questão. Essa abordagem meticulosa e abrangente nos permitirá identificar o modelo de machine learning mais eficaz para resolver nosso problema específico, fornecendo insights valiosos e impulsionando a tomada de decisões informadas.



## Resultado modelo machine learning

![m1](https://github.com/RafaelGallo/ML_Churn_Prediction_card/blob/main/imgs/003.png)

Os resultados da avaliação dos modelos são bastante promissores. O modelo LightGBM obteve uma impressionante acurácia de 96.8%, demonstrando sua eficácia na classificação dos dados. Em seguida, o modelo Gradient Boosting apresentou um desempenho notável, com uma acurácia de 96.5%. Esses números são indicativos de que ambos os modelos são capazes de fazer previsões com alta precisão.
A alta acurácia alcançada pelo modelo LightGBM sugere que ele está pronto para ser implantado em um ambiente de produção. No entanto, ainda há oportunidades para aprimoramento, seja ajustando os hiperparâmetros para melhorar ainda mais o desempenho ou desenvolvendo pipelines mais eficientes para pré-processamento de dado.

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

# Conclusão
A conclusão deste projeto é de extrema importância, pois revelou insights valiosos sobre o churn, ou seja, a rotatividade de clientes, no contexto dos serviços de cartão de crédito. Durante a análise dos dados, identificamos insights cruciais que podem indicar se um cliente está inclinado a cancelar seu cartão de crédito ou se está interessado em adquirir novos benefícios oferecidos pelo cartão.Este projeto abordou diversas etapas essenciais, desde a análise inicial dos dados até a implementação e avaliação de modelos de machine learning. Destacam-se áreas-chave, como o pré-processamento dos dados para garantir qualidade e consistência, a engenharia de características para extrair informações relevantes, e a divisão adequada entre conjuntos de treinamento e teste para avaliar o desempenho dos modelos.Além disso, realizamos o treinamento de diversos modelos de machine learning, incluindo algoritmos como Naive Bayes, Regressão Logística, LightGBM, XGBoost, entre outros. Dentro deste conjunto, o modelo LightGBM se destacou com um desempenho excelente, fornecendo resultados que superaram as expectativas. A análise da matriz de confusão revelou que o modelo LightGBM obteve 290 True Positives, 1672 True Negatives, 37 False Positives e 27 False Negatives.No entanto, vale ressaltar que o sucesso deste projeto não se limita apenas ao desempenho do modelo final. Cada etapa do processo, desde a limpeza dos dados até a otimização dos modelos, contribuiu para uma compreensão mais profunda do fenômeno de churn e dos padrões de comportamento dos clientes.

Olhando para o futuro, há oportunidades para expandir este projeto, explorando outras técnicas de modelagem, como redes neurais, e incorporando dados adicionais para enriquecer ainda mais as previsões. Além disso, a implementação de estratégias de retenção de clientes baseadas nos insights gerados pode ajudar a mitigar o churn e promover a fidelidade dos clientes. Em suma, este projeto demonstrou o poder da análise de dados e da modelagem preditiva na identificação e compreensão do churn em serviços de cartão de crédito. Com uma abordagem abrangente e orientada para insights, podemos tomar decisões mais informadas e estratégicas para melhorar a experiência do cliente e impulsionar o sucesso do negócio.

## Dataset Credit Card Churn
[Base_dados](https://www.kaggle.com/datasets/anwarsan/credit-card-bank-churn)

## Contato

- Linkedin: https://www.linkedin.com/in/rafael-g-986a73150/
- Github: https://github.com/RafaelGallo
- Gmail: rafaelhenriquegallo@gmail.com



