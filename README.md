# Project : Heart Failure ds Showcase 
# Data Science Showcase Project: Heart Failure Analysis with Interactive Dashboard
________________________________________
This project is a complete Data Science portfolio demonstrating essential skills: collection, exploratory analysis, pre-processing, modeling (classification and clustering), interpretability with SHAP and deploy in an interactive dashboard with Streamlit.
The differential is in integrating multiple techniques into a single flow, with rich visualizations and a user-friendly interface for data exploration and results.
________________________________________
# 🧠 Demonstrated Skills
  • Data manipulation: pandas, numpy
  • Visualization: matplotlib, seaborn, plotly
  • Pre-processing: missing, scaling, encoding treatment
  • Modeling: logistic regression, random forest, XGBoosting (performance comparison)
  • Evaluation: metrics (accuracy, precision, recall, F1, ROC-AUC), confusion matrix, ROC curve
  • Clustering: K-Means, dimensional reduction with PCA
  • Interpretability: SHAP to explain individual predictions and global importance
  • Deploy: interactive application with Streamlit
  • Project organization: modular structure, reusable and documented

# 🔍 Visão Geral do Projeto

1. Dados
  •	Fonte: Kaggle - Heart Failure Clinical Records
  •	Descrição: 299 pacientes com insuficiência cardíaca, 13 características clínicas e um alvo binário (óbito durante o período de acompanhamento).
  •	Features: idade, anemia, creatinofosfoquinase, diabetes, fração de ejeção, pressão alta, plaquetas, creatinina sérica, sódio sérico, sexo, tabagismo, tempo de acompanhamento.

2. Pipeline Implementado
  •	Carregamento e validação dos dados.
  •	Análise exploratória interativa (distribuições, boxplots, matriz de correlação).
  •	Pré-processamento: padronização das features numéricas (StandardScaler).
  •	Modelos supervisionados:
    o	Regressão Logística
    o	Random Forest
    o	XGBoost
    o	Comparação de métricas e seleção do melhor modelo (Random Forest geralmente tem melhor performance).
  •	Clusterização não supervisionada com K-Means (2 a 5 clusters) e visualização dos perfis.
  •	Interpretabilidade com SHAP: importância global das features e explicação local para novas predições.

3. Pipeline Implementado
  •	Carregamento e validação dos dados.
  •	Análise exploratória interativa (distribuições, boxplots, matriz de correlação).
  •	Pré-processamento: padronização das features numéricas (StandardScaler).
  •	Modelos supervisionados:
    o	Regressão Logística
    o	Random Forest
    o	XGBoost
    o	Comparação de métricas e seleção do melhor modelo (Random Forest geralmente tem melhor performance).
  •	Clusterização não supervisionada com K-Means (2 a 5 clusters) e visualização dos perfis.
  •	Interpretabilidade com SHAP: importância global das features e explicação local para novas predições.

5. Dashboard Streamlit
O aplicativo é dividido em quatro abas:

📊 Exploração dos Dados
  •	Visão geral do dataset (estatísticas descritivas, valores faltantes).
  •	Gráficos interativos com Plotly:
    o	Histogramas de todas as variáveis (selecionáveis)
    o	Boxplots por grupo (target)
    o	Matriz de correlação heatmap
  
🤖 Modelos Preditivos
  •	Comparação de desempenho (gráfico de barras das métricas)
  •	Matriz de confusão (para o modelo selecionado)
  •	Curva ROC com AUC
  •	Importância das features (para Random Forest)

🔬 Clusterização
  •	Escolha do número de clusters via método Elbow (inércia)
  •	Visualização dos clusters em 2D (PCA)
  •	Perfil médio de cada cluster (radar chart)

🩺 Preditor Interativo
  •	Formulário para inserir os dados de um novo paciente
  •	Escolha do modelo (Random Forest ou XGBoost)
  •	Predição da probabilidade de óbito
  •	Gráfico SHAP waterfall explicando a contribuição de cada feature para a predição


## This project uses the template - default-template-ai-projects - GitHub : https://github.com/BettoEsteves/default-template-ai-projects

