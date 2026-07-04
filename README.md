# Predição  de Churn de Clientes da Vivo

Projeto de Machine Learning desenvolvido em **R** para prever a evasão (**Churn**) de clientes da empresa Vivo.

O objetivo é identificar clientes com maior probabilidade de cancelar seus serviços, permitindo a criação de estratégias de retenção mais eficientes.


##  Objetivo

Desenvolver um modelo de classificação capaz de prever se um cliente irá cancelar o serviço (Churn) a partir de informações cadastrais e comportamentais.

O projeto aborda todas as etapas de um pipeline de Ciência de Dados:

- Importação dos dados
- Análise exploratória
- Limpeza e tratamento
- Engenharia de atributos
- Balanceamento da base
- Seleção de variáveis
- Treinamento do modelo
- Avaliação dos resultados


## Tecnologias

- **R**
- tidyverse
- ggplot2
- caret
- corrplot
- cowplot
- rattle

## Etapas do Projeto

### 1. Importação dos dados

- Leitura da base CSV
- Inspeção da estrutura dos dados
- Verificação de tipos das variáveis

### 2. Limpeza dos dados

- Tratamento de valores ausentes
- Correção de inconsistências
- Remoção de registros inválidos

### 3. Pré-processamento

- Conversão de variáveis categóricas
- Transformação em fatores
- Criação de variáveis dummy
- Padronização das variáveis quando necessário

### 4. Análise Exploratória

Foram realizadas análises para compreender:

- Distribuição das variáveis
- Correlação entre atributos
- Relação entre as variáveis e o Churn

### 5. Seleção de Variáveis

Aplicação do método **Stepwise** para selecionar as variáveis mais relevantes para o modelo.

### 6. Balanceamento da Base

Foram aplicadas técnicas para reduzir o impacto do desbalanceamento entre clientes ativos e clientes que cancelaram o serviço.

### 7. Modelagem

Foi treinado um modelo utilizando:

- **Regressão Logística (GLM)**

O treinamento foi realizado com o pacote **caret**.

### 8. Avaliação

O desempenho do modelo foi avaliado utilizando:

- Validação Cruzada (Cross Validation)
- Métricas de classificação
- Matriz de Confusão

