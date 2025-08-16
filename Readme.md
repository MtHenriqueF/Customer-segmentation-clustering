# Projeto de Segmentação de Clientes com Clustering

**Análise e desenvolvimento de um modelo de aprendizado não supervisionado para agrupar clientes de uma empresa automobilística com base em seus perfis.**

---

## 📝 Visão Geral

Este projeto foi desenvolvido como parte de um estudo em Machine Learning, focado em técnicas de **aprendizagem não supervisionada (clustering)**. O objetivo é analisar os dados de clientes de uma empresa automobilística para identificar segmentos de mercado distintos. A empresa planeja entrar em novos mercados e deseja utilizar a mesma estratégia de segmentação que se provou eficaz em seu mercado atual.

Nossa missão é utilizar os dados dos clientes atuais, que já foram classificados em 4 segmentos (A, B, C, D), para validar um modelo de clustering. Uma vez validado, este modelo será usado para prever os segmentos de 2627 novos clientes em potencial.

## 🎯 Problema de Negócio

Uma empresa automobilística obteve grande sucesso ao classificar seus clientes em 4 segmentos distintos e personalizar suas estratégias de marketing. Para expandir, a empresa identificou um novo mercado com comportamento similar e precisa segmentar 2627 novos clientes potenciais para aplicar a mesma estratégia bem-sucedida. O desafio é criar um modelo confiável que possa atribuir cada novo cliente a um dos quatro segmentos existentes.

## 💾 Dataset

O dataset utilizado neste projeto é o **"Automobile customer segmentation"**, disponível no Kaggle.

* **Fonte:** [Customer Segmentation no Kaggle](https://www.kaggle.com/datasets/kaushiksuresh147/customer-segmentation)
* **Conteúdo:** O dataset é dividido em `Train.csv` e `Test.csv`, contendo informações demográficas e profissionais dos clientes, como gênero, idade, estado civil, profissão, etc. Para este projeto de clustering, os dois arquivos foram unificados para maximizar a quantidade de dados disponíveis para encontrar padrões.

## 🛠️ Metodologia

Embora o problema seja apresentado como uma tarefa de classificação, optamos por uma abordagem de **aprendizagem não supervisionada (clustering)**. O objetivo é validar se os 4 segmentos definidos pelo negócio emergem naturalmente dos dados, sem que o modelo seja "ensinado" sobre eles. Isso torna a solução mais robusta e confirma a validade da segmentação original.

O fluxo de trabalho seguiu os seguintes passos:

1.  **Pré-processamento e Limpeza:**

2.  **Análise Exploratória de Dados (EDA):**

3.  **Modelagem com K-Means Clustering:**

4.  **Validação e Avaliação do Modelo:**
    
