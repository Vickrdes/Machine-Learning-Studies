# 🌸 Iris Species Classification (SVM)
### Reavaliação de Dataset via Kaggle Notebook

Este projeto consiste na implementação de um modelo de classificação utilizando o algoritmo **Support Vector Machine (SVM)**, com foco em um fluxo de trabalho (workflow) reprodutível e documentado diretamente na plataforma Kaggle.

---

## 🎯 Objetivos da Atividade
* **Integração com Kaggle:** Criação do notebook vinculado diretamente ao dataset oficial.
* **Análise Exploratória (EDA):** Identificação de padrões, correlações e separabilidade das classes (*Setosa*, *Versicolor* e *Virginica*).
* **Modelagem Técnica:** Implementação do SVM utilizando a biblioteca Scikit-learn.
* **Métricas de Performance:** Avaliação baseada em Acurácia e Matriz de Confusão.

## 🛠️ Requisitos Técnicos e Workflow
Seguindo as diretrizes da disciplina, o projeto foi estruturado nas seguintes etapas:

1. **Importação via Path Oficial:** Leitura dos dados diretamente do diretório `/kaggle/input/` para garantir a integridade da fonte.
2. **EDA (Exploratory Data Analysis):** - Estudo das características das pétalas e sépalas.
   - Visualização de dispersão para entender a fronteira de decisão entre as espécies.
3. **Pré-processamento:** Separação de features (X) e labels (y), seguida de `train_test_split`.
4. **Modelagem SVM:** - Utilização da classe `SVC`.
   - Documentação da escolha do **Kernel** (ex: Linear ou RBF) e justificativa dos parâmetros.
5. **Avaliação:** Cálculo de `accuracy_score` e geração da `confusion_matrix`.

---

## 📂 Arquivos
- `Iris-Species-Validation.ipynb`: Notebook completo com todas as células de código e explicações em Markdown.
- `README.md`: Documentação técnica do exercício.

---
> **Dataset Utilizado:** [Iris Species - Kaggle](https://www.kaggle.com/datasets/menegidio/iris-species)  
> **Data de Conclusão:** 24 de Março de 2026
