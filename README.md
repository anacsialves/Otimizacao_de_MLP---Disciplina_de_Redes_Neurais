# Rota da Neuromante - Otimização de uma rede neural
#### Atividade da disciplina de Redes Neurais e Algoritmos Genéticos oferecida pelo Profº. Dr. Daniel Roberto Cassar
Neste repositório exploramos a otimização de uma rede neural tipo MLP para classificação binária. Ademais, é feita a comparação de seu desempenho com o de uma floresta aleatória e com o de uma MLP sem otimização.

## Organização do trabalho
Este trabalho foi dividido em 4 notebooks. O primeiro notebook `0 - A Rota da Neuromante - Análise do problema, discussão de resultados e conclusão` apresenta o problema e discute os resultados obtidos. Os resultados discutidos são aqueles obtidos nos notebooks `1 - MLP sem otimização`, `2 - MLP com otimização` e `3 - Random Forest`, nos quais os modelos são construídos.

## Como utilizar esse repositório?

### DataSet
Para o funcionamento adequado dos notebooks, o arquivo `Dataset_Alzheimers_sep.xlsx` deve ser baixado na mesma pasta que os notebooks. Todas as informações mais essenciais sobre o dataset (como número de observações e atributos e estudo de origem) foram disponibilizadas no primeiro notebook `0 - A Rota da Neuromante - Análise do problema, discussão de resultados e conclusão`.

### `imports`
Os seguintes módulos precisam ser instalados para o funcionamento adequado dos notebooks:
- pandas
- lightning (antigo Pytorch Lightning)
- torch
- scikitlearn
- matplotlib

