# Projeto-Ciência-de-dados-ResTIC36

# Treinamento de Modelo KNN com Informações do Instagram
Este projeto apresenta o passo a passo para treinar e avaliar um modelo de K-Nearest Neighbors (KNN) utilizando um dataset com informações de influenciadores do Instagram. O objetivo é classificar ou prever categorias relacionadas às métricas de engajamento, seguidores, ou outras variáveis disponíveis no dataset.

Pré-requisitos
Certifique-se de que você tem as seguintes dependências instaladas no ambiente:

Python 3.7 ou superior
Bibliotecas Python:
 - numpy
 - pandas
 - matplotlib
 - seaborn
 - scikit-learn
 - import pandas as pd
 - seaborn
 - matplotlib
 - StandardScaler

# Passos para Utilização

Carregar o Dataset:
dataframe = pd.read_csv("nome do arquivo.csv")

Certifique-se de que o dataset está no mesmo diretório que o notebook.
O dataset será carregado e explorado para entender suas variáveis principais.
Pré-processamento dos Dados:

Conversão de colunas contendo valores com sufixos (k, m, b) para valores numéricos.
Normalização das variáveis contínuas para garantir melhor desempenho do modelo.
Treinamento do Modelo KNN:

Definição das variáveis de entrada (features) e das categorias a serem previstas.
Configuração e treinamento do modelo KNN.
Visualização da Fronteira de Decisão:

Geração de gráficos mostrando como o modelo KNN separa os dados com base nas variáveis escolhidas.

Avaliação do Modelo:
 ###Métricas como acurácia e matriz de confusão serão geradas para validar o desempenho do modelo.

# Visualização
###O notebook inclui visualizações úteis para entender os dados e o comportamento do modelo, como:

Gráficos de dispersão das variáveis.
Fronteiras de decisão do modelo KNN.
