# Exercícios com Matplotlib e SciPy

## 1. Criando um Gráfico de Linha Simples
Usando Matplotlib, crie um gráfico de linha para os valores de x de 0 a 10 e y como o quadrado de x. Adicione rótulos aos eixos e um título ao gráfico;

## 2. Gráfico de Barras
Usando Matplotlib, crie um gráfico de barras para representar as vendas de uma loja em 5 meses. Use uma lista de meses no eixo x e outra de vendas no eixo y;

## 3. Gráfico de Dispersão
Crie um gráfico de dispersão (scatter plot) com 50 pontos aleatórios usando `numpy` para gerar os valores de x e y. Use Matplotlib para plotar e definir cores para os pontos;

## 4. Histograma
Gere 1000 números aleatórios com distribuição normal usando `numpy` e crie um histograma usando Matplotlib. Defina o número de bins para 30;

## 5. Subplots em um Gráfico
Usando Matplotlib, crie dois subplots em uma única janela gráfica. O primeiro deve ser um gráfico de linha, e o segundo, um gráfico de barras.

## 6. Gráfico de Pizza
Usando Matplotlib, crie um gráfico de pizza para exibir a porcentagem de mercado de cinco produtos diferentes. Adicione rótulos aos setores e destaque o maior setor;

## 7. Função Seno e Cosseno
Usando Matplotlib, plote as funções seno e cosseno no mesmo gráfico. Adicione uma legenda para identificar cada função e diferencie-as por cores;

## 8. Ajuste de Curva com SciPy
Usando a função `curve_fit` da biblioteca SciPy, ajuste uma curva aos dados gerados pela função `y = 2x + 3` com ruído aleatório. Plote tanto os dados quanto a curva ajustada;

## 9. Resolução de Equações Diferenciais
Usando `odeint` de SciPy, resolva a equação diferencial simples `dy/dx = -2y`, onde `y(0) = 1`. Plote a solução para `y` em função de `x` de 0 a 5;

## 10. Transformada de Fourier
Usando SciPy, aplique a transformada de Fourier em um sinal simples, como `sin(x)`, e plote o espectro de frequência resultante usando Matplotlib;

## 11. Interpolação de Dados
Usando a função `interp1d` de SciPy, faça a interpolação linear de um conjunto de 5 pontos de dados. Plote tanto os dados originais quanto a curva interpolada usando Matplotlib;

## 12. Integração Numérica
Use a função `quad` de SciPy para integrar a função `f(x) = x^2` no intervalo de 0 a 2. Mostre o resultado da integração;

## 13. Gráfico de Contorno
Crie um gráfico de contorno usando Matplotlib para a função `z = sin(x) * cos(y)`, onde `x` e `y` variam de -5 a 5. Adicione uma barra de cores ao lado do gráfico;

## 14. Gráfico de Densidade
Usando Matplotlib, crie um gráfico de densidade para representar 1000 pontos gerados aleatoriamente com distribuição normal em duas dimensões;

## 15. Solução de Sistemas Lineares
Usando `linalg.solve` de SciPy, resolva o sistema linear abaixo e mostre a solução com os vetores resultantes em um gráfico Matplotlib.
$$
2x + y = 3
x - y = 1
$$
;
