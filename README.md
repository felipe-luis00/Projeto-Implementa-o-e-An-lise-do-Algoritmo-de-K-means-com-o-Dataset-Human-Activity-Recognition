Implementação e Análise do Algoritmo de K-means com o Dataset Human Activity Recognition

Nome: Luis Felipe Alves de Moura


Explicação do Código:
Carregamento dos Dados:

As características e rótulos são carregados diretamente dos arquivos no formato fornecido.
Normalização:

As características são normalizadas com StandardScaler para garantir escalas uniformes.
Redução de Dimensionalidade:

O PCA reduz a dimensionalidade para 2 componentes, tornando a visualização possível.
Método do Cotovelo e Silhouette Score:

O método do cotovelo determina o K ideal com base na inércia.
O Silhouette Score avalia a qualidade dos clusters.
Agrupamento com K-means:

O K-means++ é usado para inicialização eficiente.
O número de clusters ideal é escolhido com base nos gráficos.
Visualização:

Os clusters são representados em 2D com as componentes principais do PCA.
