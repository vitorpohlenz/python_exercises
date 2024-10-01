# Exercícios com SymPy, Pandas e Plotly

## 1. Simbolismo em SymPy
Usando a biblioteca SymPy, defina duas variáveis simbólicas `x` e `y`. Em seguida, crie a expressão `x^2 + 3*y` e calcule sua derivada em relação a `x` ;

## 2. Equações Algébricas em SymPy
Usando SymPy, resolva a equação quadrática `x^2 - 4x + 3 = 0` e exiba as soluções ;

## 3. Criação de DataFrame no Pandas
Crie um DataFrame no Pandas contendo os dados de vendas de uma loja nos meses de janeiro a março. As colunas devem ser: `Month`, `Revenue`, `Expenses`. Exiba o DataFrame ;

## 4. Escrita de Arquivo CSV
Usando o Pandas, crie um DataFrame qualquer e salve o mesmo como arquivo `.csv` sem index;

## 5. Filtragem de Dados no Pandas
A partir de um DataFrame com dados de vendas, filtre os registros onde as vendas foram maiores que 500 unidades ;

## 6. Agrupamento de Dados no Pandas
Crie um DataFrame com dados de vendas por cidade e mês. Usando o Pandas, agrupe os dados por `City` e calcule a soma total das vendas por cidade ;

## 7. Adicionando e Removendo Colunas
Dado um DataFrame de vendas, adicione uma nova coluna chamada `Profit` que seja a diferença entre `Revenue` e `Expenses`. Em seguida, remova a coluna `Expenses` ;

## 8. Operações com Dados Faltantes
Crie um DataFrame contendo valores nulos. Usando o Pandas, substitua os valores nulos pela média dos valores presentes na mesma coluna ;

## 9. Ordenação de Dados
Usando o Pandas, crie um DataFrame de produtos e preços. Em seguida, ordene os produtos pelo preço de forma decrescente ;

## 10. Mesclagem de DataFrames
Usando o Pandas, crie dois DataFrames: um contendo dados de clientes e outro contendo dados de compras. Faça a junção (merge) dos dois DataFrames com base no ID do cliente ;

## 11. Gráfico de Linha com Plotly
Usando Plotly, crie um gráfico de linha para representar o crescimento populacional ao longo dos anos. O eixo `x` deve ser o ano e o eixo `y` a população ;

## 12. Gráfico de Barras com Plotly
Crie um gráfico de barras com Plotly para mostrar as vendas de diferentes produtos em um mês. Adicione um título ao gráfico e rótulos para os eixos ;

## 13. Gráfico de Dispersão com Plotly
Carrege o dataset `iris` do Ploty presente em `plotly.express.data`, e usando Plotly, crie um gráfico de dispersão para visualizar a relação entre `petal_length` e `petal_width`. Adicione rótulos aos pontos e diferencie as cores por `species` também coloque uma linha vertical e outra horizontal indicando o valor médio de cada variável;

## 14. Gráfico 3D com Plotly
Usando Plotly, crie um gráfico 3D para plotar uma função matemática `z = sin(x) * cos(y)`, onde `x` e `y` variam de -5 a 5. Adicione um título e ajuste a visualização ;

## 15. Gráfico de Pizza com Plotly
Crie um gráfico de pizza usando Plotly para representar a participação de mercado de cinco empresas. Defina a explosão do setor que tem a maior participação ;