#Projeto: Implementação e Análise do Algoritmo de K-means com o Dataset Human Activity Recognition
Nome:Luis Felipe Alves de Moura

Explicação:

Carregamento dos Dados: Carrega os dados de treinamento (features e rótulos) em dataframes Pandas.
Normalização: Normaliza os dados utilizando o StandardScaler para garantir que todas as features tenham a mesma escala.
Método do Cotovelo: Calcula a soma dos quadrados das distâncias intra-cluster (WCSS) para diferentes valores de K e plota o gráfico para identificar o ponto de inflexão (cotovelo).
Criação do Modelo K-means: Cria um modelo K-means com o número de clusters escolhido.
Ajuste do Modelo: Ajusta o modelo aos dados normalizados.
Avaliação: Calcula o silhouette score para avaliar a qualidade dos clusters.
Visualização: Utiliza PCA para reduzir a dimensionalidade dos dados para 2D e plota os clusters em um gráfico de dispersão.
