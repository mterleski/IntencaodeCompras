# Previsão de Intenção de Compra
Modelo para prever se um cliente de e-commerce realizará uma compra com base em seu comportamento.

Neste projeto, nosso objetivo é criar um sistema inteligente para antecipar a intenção de compra dos clientes em um site de e-commerce. Para isso, vamos aplicar e comparar técnicas dos modelos preditivos classificatórios de RandomForest e Regressão Logística.

Esse modelos serão aplicado em uma base de dados que contém informações detalhadas sobre os clientes, incluindo dados demográficos (idade, renda, etc.) e informações sobre compras anteriores

## 🧠 Técnicas Utilizadas

- Análise exploratória de dados (EDA)
- Pré-processamento e tratamento de dados (padronização, remoção de outliers e seleção de features)
- Balanceamento de classes com **SMOTE** (para o modelo de Regressão Logística)
- Treinamento e avaliação com os modelos:
  - **Logistic Regression**
  - **Random Forest**
- Métricas de avaliação:
  - Acurácia
  - Precisão, Recall, F1-Score
  - Cross Validation
 
 ## 🧪 Resultados

Os modelos foram avaliados com base em sua capacidade de prever corretamente a intenção de compra. O **modelo de Random Forest** apresentou o melhor desempenho geral. Ele foi capaz de prever corretamente 90% das tendencias de compras online e encontrou 94% dos clientes que tinham a intenção de realizar suas compras.

## 📁 Como Executar

1. Clone o repositório:
   git clone https://github.com/mterleski/IntencaodeCompras.git
   
   cd repositorio
   
   pip install -r requirements.txt
   
   jupyter notebook nome_do_notebook.ipynb
