# Exercícios com Numba e Cupy

## 1. Função JIT Simples
Crie uma função que calcule a soma de todos os elementos em uma lista de números inteiros. Use o decorador `@jit` do Numba para acelerar a execução e compare o tempo de execução com e sem a compilação JIT;

## 2. Multiplicação de Matrizes com JIT
Crie uma função para multiplicar duas matrizes `500x500` usando o decorador `@jit`. Gere duas matrizes aleatórias, multiplique-as e meça o tempo de execução com e sem JIT;

## 3. Cálculo de Números Primos com JIT
Crie uma função que retorne todos os números primos até um número `n` fornecido pelo usuário. Utilize Numba com JIT para otimizar a função e compare o tempo de execução para valores grandes de `n`;

## 4. Soma de Vetores em GPU
Crie uma função usando `@cuda.jit` para somar elemento a elemento dois vetores de tamanho `100000`. Execute a soma na GPU e compare o desempenho com a execução na CPU;

## 5. Operação de Elementos ao Quadrado em GPU
Implemente uma função que eleve ao quadrado cada elemento de um vetor de `1000000` elementos usando Numba com GPU. Teste o desempenho em comparação com uma função regular;

## 6. Multiplicação de Matrizes na GPU
Utilize o `@cuda.jit` para escrever uma função que multiplique duas matrizes `100x100` e execute a operação na GPU. Compare o tempo de execução com a versão sem GPU;

## 7. Soma de Matrizes com Cupy
Use o Cupy para gerar duas matrizes de `500x500` com valores aleatórios. Calcule a soma dessas matrizes diretamente na GPU e verifique o desempenho;

## 8. Multiplicação de Matrizes com Cupy
Crie duas matrizes `1000x1000` usando Cupy e calcule o produto das duas diretamente na GPU. Compare o tempo de execução com uma versão feita em Numpy na CPU;

## 9. Função Trigonométrica com Cupy
Implemente uma função que calcule o seno de cada valor em uma matriz `2000x2000` usando Cupy. Verifique o desempenho da execução na GPU;

## 10. Raiz Quadrada de Elementos com Cupy
Utilize o Cupy para calcular a raiz quadrada de cada elemento em um vetor de `1000000` valores aleatórios entre 0 e 1. Meça o tempo de execução e compare com uma solução feita em Numpy;

## 11. Produto Externo de Vetores com Cupy
Usando Cupy, calcule o produto externo entre dois vetores de tamanho `10000`. Avalie a aceleração proporcionada pela GPU em comparação com o cálculo usando Numpy na CPU;
