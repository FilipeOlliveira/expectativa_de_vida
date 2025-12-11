# expectativa_de_vida

🧠 Previsão de Expectativa de Vida
Projeto da disciplina Aprendizado de Máquina

Este repositório contém o projeto final desenvolvido para a disciplina de Aprendizado de Máquina, no qual aplico técnicas de análise exploratória e modelos de regressão para prever a expectativa de vida de diversos países com base em variáveis socioeconômicas e de saúde pública. O foco deste trabalho está no aprendizado prático de técnicas de regressão e análise de dados aplicadas a um conjunto de dados real.

O trabalho foi totalmente desenvolvido no Google Colab, utilizando Python e as principais bibliotecas de Machine Learning.

📊 Objetivo do Projeto

O objetivo principal é construir um modelo de Machine Learning capaz de prever a expectativa de vida de um país a partir de variáveis como:

PIB per capita

Índice de desenvolvimento

Taxa de mortalidade infantil

Gastos com saúde

Escolaridade média

Entre outras…

O foco do projeto é aprender o ciclo completo de ML:

Importação e limpeza dos dados

Análise exploratória (EDA)

Pré-processamento

Seleção e treinamento de modelos

Avaliação

Conclusões e aprendizados

🗂 Dataset

O dataset utilizado foi obtido no Kaggle:

📦 Life Expectancy (WHO) – Kaggle: https://www.kaggle.com/datasets/paperxd/cleaned-life-expectancy-dataset/data

📚 Etapas Atendidas (Conforme Solicitação do Professor)

🔹 1ª Unidade – Pré-processamento e Análise Exploratória

✔️ 1. Carregamento dos Dados

Utilização da biblioteca Pandas para importar o dataset.

Visualização inicial das colunas, tipos de dados e primeiras linhas.

✔️ 2. Tratamento de Dados Ausentes

Identificação de valores ausentes por coluna.

Seleção da estratégia adequada conforme o tipo de variável:

Imputação com média/mediana

Remoção de linhas (se justificável)

Preenchimento por agrupamentos (quando relevante)

✔️ 3. Análise Exploratoria dos Atributos

Foram gerados gráficos adequados para cada variável, como:

Histogramas

Boxplots

Gráficos de dispersão

Heatmap de correlação

Distribuições e relações entre variáveis preditoras e a variável-alvo

✔️ 4. Identificação de Outliers

Análise via boxplots,

Z-Score,

IQR (Interquartile Range),

Discussão sobre possíveis remoções ou tratamento.

🔹 2ª Unidade – Modelagem e Otimização
✔️ 5. Divisão em Treino e Teste

Divisão adequada utilizando train_test_split.

✔️ 6. Escolha de Três Modelos de ML

Os seguintes algoritmos foram utilizados (exemplo — adapte):

Regressão Linear

Random Forest Regressor

Gradient Boosting Regressor
(Você pode substituir pelos modelos realmente utilizados.)

✔️ 7. Divisão do Conjunto de Treino para Validação

Criação de subconjunto de validação para ajuste de hiperparâmetros.

Uso de validação cruzada (opcional, se você utilizou).

✔️ 8. Otimização Bayesiana

Utilização da técnica de Otimização Bayesiana para ajustar hiperparâmetros.

Comparação de valores ótimos vs. valores padrão.

✔️ 9. Comparação dos Modelos

Avaliação com métricas adequadas ao problema de regressão:

MAE

RMSE

R²

Comparação entre:

Modelos sem otimização

Modelos com hiperparâmetros otimizados

Discussão dos resultados e modelo final escolhido.

🧰 Tecnologias Utilizadas

Google Colab

Python 3

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn
Link: (adicione o link do dataset)

Este dataset reúne indicadores de saúde e desenvolvimento humano compilados pela OMS.


🎓 Considerações Finais

O notebook demonstra todo o processo completo de machine learning solicitado na disciplina, desde a compreensão dos dados até o ajuste e comparação de modelos otimizados.
O projeto reforça conceitos como análise exploratória, preparação de dados, regressão, otimização e avaliação de modelos.




