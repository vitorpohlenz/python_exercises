# Exercícios PyTorch

## 1. Regressão com o Dataset Penguins
Utilize o dataset `penguins` disponível na biblioteca `seaborn` para construir um modelo de regressão com PyTorch.

O objetivo é prever a massa corporal (`body_mass_g`) dos pinguins com base em atributos como o comprimento do bico (`bill_length_mm`) e a profundidade do bico (`bill_depth_mm`).

Carregue o dataset utilizando `seaborn.load_dataset('penguins')` e então treine um modelo linear e avalie o resultado no conjunto de teste, após treine um modelo não linear e avalie o resultado no conjunto de teste. 

> Por que existe essa diferença?
;

## 2. Classificação com o Dataset Iris
Treine um modelo de classificação com PyTorch para prever a espécie de cada flor no dataset Iris com base em suas características.
Para tal, carregue esse data set utilizando a função `load_iris()` disponível em `sklearn.datasets`;