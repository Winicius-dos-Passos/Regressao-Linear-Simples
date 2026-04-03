# 🚗 Predição Automotiva com Regressão Linear Simples

## 📖 Sobre o Projeto
Este projeto tem como objetivo demonstrar a aplicação prática de um dos algoritmos mais fundamentais de Machine Learning: a **Regressão Linear Simples**. Utilizando a linguagem Python e um conjunto de dados automotivos (`cars.csv`), o projeto explora a relação estatística entre duas variáveis contínuas, criando um modelo capaz de prever valores com base em dados históricos.

Este repositório foi criado como parte do desenvolvimento do meu portfólio em Ciência de Dados, focando em boas práticas de análise, modelagem e avaliação de resultados.

## 🎯 Objetivos
* Realizar a Análise Exploratória de Dados (EDA) para entender a distribuição e correlação das variáveis.
* Construir e treinar um modelo de Regressão Linear Simples.
* Avaliar a performance do modelo utilizando métricas estatísticas de regressão.
* Visualizar a reta de regressão e a dispersão dos dados de forma clara e intuitiva.

## 📂 Estrutura do Repositório
* `Regressão_Linear_Simples.ipynb`: Notebook principal contendo todo o código, desde a importação dos dados até a geração de gráficos e avaliação do modelo.
* `cars.csv`: O conjunto de dados utilizado para treinar e testar o algoritmo.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Linguagem:** Python
* **Ambiente de Desenvolvimento:** Google Colab
* **Manipulação de Dados:** `pandas`, `numpy`
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn`

## 📊 Metodologia e Resultados
1. **Entendimento dos Dados:** Leitura do arquivo `cars.csv` e verificação de valores nulos ou inconsistentes.
2. **Análise de Correlação:** Utilização de gráficos de dispersão (scatter plots) para confirmar a tendência linear entre a variável dependente (alvo) e a variável independente (preditora).
3. **Treinamento do Modelo:** Divisão dos dados (treino e teste) e ajuste da reta de regressão utilizando o `LinearRegression` do scikit-learn.
4. **Avaliação do Modelo:** O desempenho do modelo foi medido utilizando o Coeficiente de Determinação ($R^2$). O modelo obteve um **$R^2$ de 0.651**, o que indica que aproximadamente 65,1% da variância da nossa variável dependente é explicada pelo modelo linear.

## 🚀 Como Executar o Projeto
1. Clone este repositório para a sua máquina local ou abra-o diretamente no Google Colab.
   ```bash
   git clone [https://github.com/Winicius-dos-Passos/Regressao-Linear-Simples.git](https://github.com/Winicius-dos-Passos/Regressao-Linear-Simples.git)
2. Certifique-se de que o arquivo cars.csv esteja no mesmo diretório que o Notebook (ou faça o upload do arquivo caso esteja utilizando o Colab).

3. Execute as células do Regressão_Linear_Simples.ipynb sequencialmente.

## 👨‍💻 Autor
Desenvolvido por **Winicius dos Passos**

Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/winicius-dos-passos/)
