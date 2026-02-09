# 🫁 COVID-19 Detection from CT Scans using Deep Learning and Genetic Algorithms

Este projeto apresenta uma metodologia computacional para **classificação automática de COVID-19 a partir de imagens de Tomografia Computadorizada (CT)**, combinando **Deep Learning, otimização Bayesiana de hiperparâmetros e seleção de características via Algoritmo Genético.**

A abordagem utiliza uma **CNN leve e eficiente**, projetada para cenários com bases de dados médicas reduzidas, extraindo características discriminativas das imagens. Em seguida, os hiperparâmetros da rede são otimizados com **Tree-Structured Parzen Estimator (TPE)**, e um **Algoritmo Genético (GA)** é aplicado para selecionar o subconjunto mais relevante de features. A classificação final é realizada com diferentes algoritmos de **Machine Learning**, incluindo **MLP, SVM, Random Forest e XGBoost**.

Os experimentos foram conduzidos em **bases públicas de CT scans (SARS-CoV-2 CT-Scan e COVID-CT)**, alcançando **altos índices de acurácia, kappa, AUROC e AUPRC**, superando modelos pré-treinados e métodos do estado da arte. Os resultados demonstram que a metodologia pode **auxiliar profissionais de saúde no rastreio e diagnóstico da COVID-19**, com baixo custo computacional.

## 🔹 Principais contribuições

* CNN customizada e de baixa complexidade para imagens médicas
* Otimização automática de hiperparâmetros via TPE
* Seleção eficiente de características com Algoritmo Genético
* Alto desempenho em múltiplos classificadores
* Aplicação prática em sistemas de apoio à decisão clínica

## 🔹 Publicações Associadas

### An approach to the classification of COVID-19 based on CT scans using convolutional features and genetic algorithms  
*Computers in Biology and Medicine, 2021*  
🔗 https://doi.org/10.1016/j.compbiomed.2021.104744  

- CNN customizada para extração de características  
- Otimização de hiperparâmetros com Tree-Structured Parzen Estimator (TPE)  
- Seleção de atributos via Algoritmo Genético  
- Classificação com MLP, SVM, Random Forest e XGBoost  

### Diagnosis of COVID-19 in CT image using CNN and XGBoost  
*IEEE ISCC, 2020*  
🔗 https://doi.org/10.1109/ISCC50000.2020.9219726  

- Extração de características utilizando CNN  
- Classificação baseada em XGBoost  
- Abordagem eficiente e de baixo custo computacional  

### COVID-19 diagnosis in CT images using CNN to extract features and multiple classifiers  
*IEEE BIBE, 2020*  
🔗 https://doi.org/10.1109/BIBE50027.2020.00075  

- CNN como extrator de atributos  
- Avaliação com múltiplos classificadores  
- Análise detalhada de métricas de desempenho  
