# Exercícios com Numba e Cupy

## 1. Função JIT Simples
Crie uma função que calcule a soma de todos os elementos em uma lista de números inteiros. Use o decorador `@jit` do Numba para acelerar a execução e compare o tempo de execução com e sem a compilação JIT;

## 2. Multiplicação de Matrizes com JIT
Crie uma função para multiplicar duas matrizes `500x500` usando o decorador `@jit`. Gere duas matrizes aleatórias, multiplique-as e meça o tempo de execução com e sem JIT;

## 3. Cálculo de Números Primos com JIT
Crie uma função que retorne todos os números primos até um número `n` fornecido pelo usuário. Utilize Numba com JIT para otimizar a função e compare o tempo de execução para valores grandes de `n`;

## 4. Multiplicação de Matrizes com Cupy
Crie duas matrizes `1000x1000` usando Cupy e calcule o produto das duas diretamente na GPU;

## 5. Produto Externo de Vetores com Cupy
Usando Cupy, calcule o produto externo entre dois vetores de tamanho `10000`;
