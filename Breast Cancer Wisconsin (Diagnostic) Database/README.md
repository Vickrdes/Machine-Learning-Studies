# 🧬 Classificação de Câncer de Mama (SVM)
### Desafio 2: Exploração da Fronteira de Decisão

Este projeto utiliza o dataset clássico **Breast Cancer Wisconsin (Diagnostic)** para classificar tumores como malignos ou benignos. O foco principal foi o ajuste de hiperparâmetros do modelo **SVM (Support Vector Machine)** para lidar com dados de alta dimensionalidade.

---

## 🎯 Objetivo do Desafio
O conjunto de dados possui mais de 30 características técnicas (raio, textura, concavidade, etc.). O objetivo foi:
* Testar a eficácia de diferentes **Kernels** (Linear vs RBF).
* Ajustar o parâmetro de regularização **C** para equilibrar a fronteira de decisão.
* Otimizar o compromisso entre **Precisão** (evitar alarmes falsos) e **Recall** (não deixar nenhum caso positivo passar despercebido).

## 🛠️ Tecnologias e Técnicas
* **Linguagem:** Python (Google Colab / Kaggle)
* **Biblioteca Principal:** Scikit-learn
* **Algoritmo:** SVM (Support Vector Machine)
* **Pré-processamento:** Normalização de dados (StandardScaler), essencial para o funcionamento do SVM.

## 📊 Experimentos Realizados

### 1. Kernels Comparados
- **Linear:** Testado para verificar a separabilidade linear dos dados.
- **RBF (Radial Basis Function):** Utilizado para capturar relações não-lineares mais complexas entre as 30 variáveis.

### 2. Ajuste do Parâmetro C
Busquei o valor ideal de **C** para:
- Evitar o *overfitting* (C muito alto).
- Garantir que o modelo não fosse simples demais (*underfitting*) a ponto de perder casos reais de câncer (Recall baixo).

---

## 📈 Conclusões
Através da análise da **Matriz de Confusão**, foi possível observar como a variação do Kernel e do parâmetro C impacta diretamente na detecção de casos malignos, priorizando um Recall alto dado a natureza crítica do diagnóstico médico.

---
> **Dataset Original:** [UCI Machine Learning Repository / Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
