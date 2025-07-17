# projeto_ML_algoritmo
# 📊 Classificação com Árvore de Decisão - Glass Dataset

Este projeto foi desenvolvido para a disciplina de **Algoritmos e Estrutura de Dados**, com o objetivo de aplicar e avaliar o uso de uma **Árvore de Decisão** utilizando a biblioteca **scikit-learn**. O dataset utilizado é o clássico **Glass Identification Dataset**, focado em classificar tipos de vidro com base em suas propriedades químicas.

---

## ✅ Objetivos do Projeto

* Aplicar o pré-processamento de dados em um dataset real;
* Treinar uma Árvore de Decisão simples;
* Testar técnicas de balanceamento de dados como **SMOTE** e **class\_weight**;
* Avaliar o desempenho do modelo com métricas como **acurácia**, **f1-score** e **matriz de confusão**;
* Visualizar a árvore gerada para análise interpretativa.

---

## 📝 Etapas Realizadas

* 📌 **Exploração do Dataset**: análise das colunas, verificação de valores nulos e distribuição da variável alvo.
* 📌 **Separação dos Dados**: divisão em treino e teste usando `train_test_split()`.
* 📌 **Treinamento do Modelo**:

  * Árvore de Decisão sem balanceamento;
  * Árvore de Decisão com **SMOTE** (oversampling);
  * Árvore de Decisão com **class\_weight='balanced'**.
* 📌 **Avaliação**: utilização de matriz de confusão e relatório de classificação para cada modelo.
* 📌 **Visualização**: geração do gráfico da Árvore de Decisão usando `plot_tree()`.


---

## 📌 Resultados

Os modelos foram avaliados tanto por acurácia quanto pelo **f1-score**, destacando como o balanceamento melhora a previsão para classes menos representadas, mesmo com uma leve redução na acurácia total.

---

## 💻 Tecnologias Utilizadas

* Python 3
* Scikit-learn
* Pandas
* Seaborn
* Matplotlib
* Imbalanced-learn (SMOTE)

---

## 🎓 Finalidade Educacional

Este projeto foi desenvolvido para fins acadêmicos, visando a prática de aprendizado supervisionado e análise de desempenho em modelos de classificação simples usando Árvores de Decisão.
