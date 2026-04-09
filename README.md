# 📈 Regressão Linear e Regularização L2: Implementação Manual

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

Este repositório contém a resolução de exercícios práticos focados nos fundamentos de aprendizado de máquina, especificamente **Regressão Linear Univariada e Multivariada**, utilizando a solução analítica de **Mínimos Quadrados Ordinários (OLS)** e técnicas de regularização.

---

## 🚀 Objetivo

O objetivo principal deste projeto foi implementar e validar algoritmos de regressão utilizando álgebra linear pura (`NumPy`), **sem o uso de bibliotecas de alto nível** como `scikit-learn`. O foco foi entender a mecânica da otimização de parâmetros "por baixo dos panos" e o impacto da complexidade do modelo no erro.

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **NumPy:** Processamento de matrizes e cálculos algébricos.
* **Matplotlib:** Visualização de dados e análise gráfica dos erros.

## 📋 Conteúdo do Notebook

O arquivo `lista01.ipynb` aborda os seguintes tópicos:

### 1. Regressão Linear Simples (OLS)
* Leitura e manipulação de dados artificiais (`artificial1d.csv`).
* Implementação manual da solução analítica: 
$$\mathbf{w} = (\mathbf{X}^T \mathbf{X})^{-1} \mathbf{X}^T \mathbf{y}$$
* Cálculo do Erro Quadrático Médio (**MSE**).

### 2. Regressão Polinomial e Generalização
* Expansão de características (features) para diferentes graus de polinômios.
* Análise detalhada do dilema entre **Overfitting** (sobreajuste) e **Underfitting** (subajuste).

### 3. Regularização L2 (Ridge Regression)
* Implementação da regularização para controle do crescimento dos pesos.
* Visualização do erro (**RMSE**) em conjuntos de treinamento e teste para diferentes complexidades de modelo.

## 📊 Resultados

O projeto inclui visualizações gráficas que demonstram o comportamento do **RMSE (Root Mean Square Error)** conforme o grau do polinômio aumenta. Os gráficos evidenciam a importância da **Regularização L2** para manter a capacidade de generalização do modelo, impedindo que ele apenas "decore" os dados de treino e falhe ao prever dados não vistos.

---

## 💻 Como Executar

1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
