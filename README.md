# 📊 Análise de Dados e Modelagem Preditiva

Este repositório contém um notebook que realiza análises de regressão e classificação em diferentes conjuntos de dados relacionados a energia, redes elétricas inteligentes e radiação solar.  
O projeto foi desenvolvido como parte de uma atividade prática de aprendizado de máquina, utilizando **Python** e bibliotecas como `pandas`, `scikit-learn`, `matplotlib` e `seaborn`.

---

## 🗂 Estrutura do Projeto

- **Parte I**
  - **Regressão Linear, Árvore de Regressão e Random Forest Regressor**
  - Objetivo: prever o consumo de energia de eletrodomésticos (`Appliances`) a partir de variáveis ambientais (temperatura, umidade, pressão, etc.)
  - Métricas avaliadas: **R²**, **RMSE** e **MAE**

- **Parte II**
  - **Classificação de Estabilidade de Smart Grid**
  - Modelos utilizados: Árvore de Decisão, KNN, Regressão Logística
  - Métricas avaliadas: **Acurácia**, **F1-Score** e **Matriz de Confusão**

- **Parte III**
  - **Classificação de Nível de Radiação Solar**
  - Modelos utilizados: Árvore de Decisão, Random Forest e SVM
  - Métricas avaliadas: **Acurácia** e **Matriz de Confusão**

---

## 📂 Conjuntos de Dados

- **`energydata_complete.csv`**  
  - Dados de monitoramento de energia e variáveis ambientais em uma residência.  
  - Atributos: Temperatura, Umidade, Pressão, Velocidade do Vento, Consumo de Energia de Iluminação e Eletrodomésticos.  

- **`smart_grid_stability_augmented.csv`**  
  - Dados simulados de uma rede elétrica inteligente para prever estabilidade do sistema.  
  - Atributos: parâmetros de tensão e potência, além do rótulo de estabilidade (`stabf`: 0 = instável, 1 = estável).  

- **`SolarPrediction.csv`**  
  - Dados meteorológicos e de radiação solar ao longo do tempo.  
  - Atributos: Temperatura, Pressão, Umidade, Direção e Velocidade do Vento, Radiação Solar.  

> ⚠️ **Nota:** Caso os arquivos não estejam disponíveis, o notebook cria dados sintéticos (placeholders) para permitir a execução dos modelos sem erro.

---

## 🚀 Como Executar

1. Clone este repositório ou faça o download do arquivo `.ipynb`
2. Instale as dependências necessárias:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
