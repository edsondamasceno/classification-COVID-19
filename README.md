# 🫁 COVID-19 Detection from CT Scans using Deep Learning and Genetic Algorithms

Este projeto apresenta uma metodologia computacional para **classificação automática de COVID-19 a partir de imagens de Tomografia Computadorizada (CT)**, combinando **Deep Learning, otimização Bayesiana de hiperparâmetros e seleção de características via Algoritmo Genético.**

A abordagem utiliza uma **CNN leve e eficiente**, projetada para cenários com bases de dados médicas reduzidas, extraindo características discriminativas das imagens. Em seguida, os hiperparâmetros da rede são otimizados com **Tree-Structured Parzen Estimator (TPE)**, e um **Algoritmo Genético (GA)** é aplicado para selecionar o subconjunto mais relevante de features. A classificação final é realizada com diferentes algoritmos de **Machine Learning**, incluindo **MLP, SVM, Random Forest e XGBoost**.

Os experimentos foram conduzidos em **bases públicas de CT scans (SARS-CoV-2 CT-Scan e COVID-CT)**, alcançando **altos índices de acurácia, kappa, AUROC e AUPRC**, superando modelos pré-treinados e métodos do estado da arte. Os resultados demonstram que a metodologia pode **auxiliar profissionais de saúde no rastreio e diagnóstico da COVID-19**, com baixo custo computacional.

🔹 Principais contribuições

* CNN customizada e de baixa complexidade para imagens médicas
* Otimização automática de hiperparâmetros via TPE
* Seleção eficiente de características com Algoritmo Genético
* Alto desempenho em múltiplos classificadores
* Aplicação prática em sistemas de apoio à decisão clínica

