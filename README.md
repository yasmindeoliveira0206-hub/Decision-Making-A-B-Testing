# Data-Driven Decision Making

This repository contains the final project for the ninth sprint of the TripleTen Data Analytics program. The focus of this project was **Data-Driven Decision Making**, using hypothesis prioritization techniques and rigorous **A/B Test** analysis for a large online retail company.

## Business Context

Working alongside the marketing department, the objective was to increase the online store's revenue by validating hypotheses aimed at improving the product. The project was divided into two main parts: prioritizing ideas for testing and analyzing the results of an experiment that had already been conducted.

## Technologies and Tools

* **Python 3.x**
* **Pandas:** Data manipulation and calculation of cumulative metrics.
* **NumPy:** Support for mathematical and statistical operations.
* **Matplotlib:** Creation of line charts for cumulative metrics and scatter plots for outlier identification.
* **SciPy (stats):** Execution of statistical significance tests (Mann-Whitney U Test).

## Technical Challenges Overcome

This project required a comprehensive analytical approach to ensure the reliability of the results:

* **Hypothesis Prioritization:**

  * Application of the **ICE** (Impact, Confidence, Ease) and **RICE** (Reach, Impact, Confidence, Effort) frameworks.
  * Analysis of how the **Reach** metric dramatically changes the priority of initiatives.
* **A/B Test Analysis:**

  * Calculation and visualization of cumulative revenue and cumulative average order value by group.
  * Calculation of cumulative conversion rates and analysis of the relative difference between groups.
  * **Outlier Treatment:** Identification of users with atypical behavior (excessive purchases or unusually high order values) through percentile analysis (95th and 99th percentiles).
* **Statistical Significance:**

  * Execution of the Mann-Whitney U test to compare conversion rates and average order values between groups, using both "raw" and "filtered" datasets.
  * Decision-making based on p-values and metric stability.

## Key Insights

* Identification of the winning hypothesis for immediate implementation based on the RICE score.
* Conclusion of the A/B Test: Group B demonstrated a statistically significant higher conversion rate than Group A, despite no significant difference in average order value.
* Recommendation to stop the test and declare Group B as the winner, saving resources and accelerating the implementation of improvements.

## Repository Structure

* `notebook.ipynb`: The Jupyter Notebook containing the entire process of prioritization, data cleaning, cumulative analysis, and statistical testing.
* `README.md`: This file, providing an overview of the project.

---

*This project is part of my Data Analytics training at TripleTen Brazil.*


_____________________________________________________
#Tomada de Decisões Baseada em Dados 

Este repositório contém o projeto final da nona sprint do curso de Análise de Dados da TripleTen. O foco deste projeto foi a **Tomada de Decisões Baseada em Dados**, utilizando técnicas de priorização de hipóteses e análise rigorosa de **Testes A/B** para uma grande loja online.

## Contexto do Negócio
Trabalhando em conjunto com o departamento de marketing, o objetivo foi aumentar a receita da loja online através da validação de hipóteses de melhoria no produto. O projeto foi dividido em duas partes principais: a priorização de ideias para testes e a análise dos resultados de um experimento já realizado.

## Tecnologias e Ferramentas
*   **Python 3.x**
*   **Pandas:** Manipulação de dados e cálculos de métricas acumuladas.
*   **NumPy:** Suporte a operações matemáticas e estatísticas.
*   **Matplotlib:** Criação de gráficos de linha para métricas acumuladas e gráficos de dispersão para identificação de outliers.
*   **SciPy (stats):** Realização de testes de significância estatística (Teste de Mann-Whitney).

## Desafios Técnicos Superados
Este projeto exigiu uma abordagem analítica completa para garantir a confiabilidade dos resultados:
*   **Priorização de Hipóteses:**
    *   Aplicação dos frameworks **ICE** (Impact, Confidence, Ease) e **RICE** (Reach, Impact, Confidence, Effort).
    *   Análise de como a métrica de "Alcance" (Reach) altera drasticamente a prioridade das tarefas.
*   **Análise de Teste A/B:**
    *   Cálculo e visualização da receita acumulada e do tamanho médio do pedido acumulado por grupo.
    *   Cálculo da conversão acumulada e análise da diferença relativa entre os grupos.
    *   **Tratamento de Outliers:** Identificação de usuários com comportamento atípico (compras excessivas ou valores muito altos) através de percentis (95º e 99º).
*   **Significância Estatística:**
    *   Realização do teste de Mann-Whitney para comparar conversão e tamanho do pedido entre os grupos, tanto com dados "sujos" quanto com dados "filtrados".
    *   Tomada de decisão baseada em p-values e na estabilidade das métricas.

## Principais Insights
*   Identificação da hipótese vencedora para implementação imediata baseada no score RICE.
*   Conclusão do Teste A/B: O grupo B apresentou uma conversão estatisticamente superior ao grupo A, apesar de não haver diferença significativa no tamanho médio do pedido.
*   Recomendação de interromper o teste e declarar o Grupo B como vencedor, economizando recursos e acelerando a implementação das melhorias.

## Estrutura do Repositório
*   `notebook.ipynb`: O notebook Jupyter contendo todo o processo de priorização, limpeza, análise acumulada e testes estatísticos.
*   `README.md`: Este arquivo com a apresentação do projeto.

---
*Este projeto faz parte da minha formação como Analista de Dados na TripleTen Brasil.*
