# ⚡ Análise Exploratória e Modelagem Preditiva do Consumo Elétrico Residencial

Este projeto tem como objetivo compreender padrões de **consumo energético residencial** e aplicar **modelos de aprendizado de máquina** para prever a demanda elétrica total.  

O estudo utiliza o conjunto de dados **Household Electricity Consumption Data** (Kaggle), composto por cerca de **240.000 registros** com medições de potência, tensão, corrente e submedidores de consumo em diferentes áreas da residência.

---

## 🚀 Objetivos

- Realizar uma **análise exploratória de dados (EDA)** sobre o comportamento de consumo elétrico ao longo do tempo.  
- Identificar **relações entre potência, tensão e corrente** em contextos horários e sazonais.  
- Aplicar o modelo **XGBoost Regressor** para **previsão do consumo ativo global (Global Active Power)**.  
- Avaliar o desempenho preditivo com métricas como **RMSE** e **R²**.  
- Gerar **insights voltados à eficiência energética** e otimização do uso residencial.

---

## 🧠 Metodologia

### 1. Pré-processamento dos Dados
- Limpeza e tratamento de valores ausentes.  
- Conversão de tipos de dados e padronização temporal.  
- Criação de variáveis derivadas e estatísticas descritivas.  

### 2. Análise Exploratória (EDA)
- Exploração visual das variáveis **Global Active Power**, **Voltage**, **Intensity** e **Sub-meterings**.  
- Análise de padrões **diários e semanais** de consumo.  
- Correlação entre variáveis elétricas através de **heatmaps** e **gráficos de dispersão**.  

### 3. Modelagem Preditiva
- Divisão dos dados em **treinamento e teste**.  
- Treinamento do modelo **XGBoost Regressor** para previsão da potência ativa global.  
- Avaliação do desempenho com **erro quadrático médio (RMSE)** e **coeficiente de determinação (R²)**.  
- Interpretação dos resultados e identificação das variáveis de maior impacto.

---

## 📈 Principais Insights

- O **consumo elétrico** apresenta **padrões horários bem definidos**, com picos concentrados no período da noite.  
- Existe **correlação positiva entre corrente e potência ativa**, e relação inversa entre tensão e consumo.  
- Determinadas áreas da residência (ex.: **cozinha e lavanderia**) possuem **maior contribuição no consumo total**.  
- O modelo **XGBoost** demonstrou **bom desempenho preditivo**, mostrando potencial para aplicações em **monitoramento inteligente e economia de energia**.  

---

## 🧩 Tecnologias Utilizadas
- **Python**  
- **Pandas / NumPy** – manipulação e tratamento de dados  
- **Matplotlib / Seaborn** – visualização de padrões e correlações  
- **Scikit-learn / XGBoost** – modelagem e avaliação preditiva  
- **Jupyter Notebook** – documentação e execução do estudo  

---

## 📚 Fonte
Dataset: [Household Electricity Consumption Data – Kaggle](https://www.kaggle.com/datasets)

---

💡 *Este projeto integra a coleção de estudos voltados à aplicação prática de Ciência de Dados e Aprendizado de Máquina, com foco em previsão, análise energética e sustentabilidade.*
