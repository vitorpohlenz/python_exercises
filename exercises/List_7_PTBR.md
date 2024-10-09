# Exercícios com Threads, Multiprocessing, `concurrent.futures` e `dask`

## 1. Criando uma Thread Simples
Crie uma função chamada `print_numbers` que imprima números de 1 a 5 com uma pausa de 1 segundo entre eles. Execute essa função em uma thread separada usando o módulo `threading` ;

## 2. Usando múltiplas Threads
Modifique o exercício anterior para executar duas threads que imprimam números de 1 a 5 simultaneamente. Certifique-se de que o programa espere as duas threads terminarem antes de encerrar ;

## 3. Sincronização com Threads
Implemente um contador compartilhado entre duas threads. As threads devem incrementar o contador 1000 vezes. Use um `Lock` para evitar condições de corrida e garantir que o contador final seja 2000 ;

## 4. Multiprocessing com Processos Simples
Crie um programa que inicie dois processos paralelos usando o módulo `multiprocessing`, onde cada processo calcula o quadrado de números de 1 a 5. Exiba os resultados ao final ;

## 5. Compartilhamento de Dados entre Processos
Usando o módulo `multiprocessing`, crie uma fila (`Queue`) para compartilhar dados entre dois processos. O primeiro processo deve adicionar números de 1 a 5 na fila, enquanto o segundo processo retira e imprime esses números ;

## 6. Pool de Processos
<font color = "yellow"> Atenção: </font> Faça esse exercício em um Sistema Operacional Linux (como no Google Colab). Não é recomendado usar `multiprocessing.Pool` em Windows, devido ao gerenciamento de processos do Sistema Operacional. Se executado em Windows levará muito mais tempo para executar do que um simples `for`. [Explicação aqui](https://stackoverflow.com/questions/52465237/multiprocessing-slower-than-serial-processing-in-windows-but-not-in-linux).

Implemente um programa que use `multiprocessing.Pool` para calcular os quadrados de uma lista de números. Use 4 processos no pool para paralelizar a execução ;

## 7. Uso de `concurrent.futures.ThreadPoolExecutor`
Crie uma função que calcule o fatorial de um número e execute-a em paralelo para 5 números diferentes usando `concurrent.futures.ThreadPoolExecutor`. Exiba o resultado final de cada execução ;

## 8. Uso de `concurrent.futures.ProcessPoolExecutor`
Implemente o cálculo do número de Fibonacci para 5 valores diferentes, usando `concurrent.futures.ProcessPoolExecutor` para executar o cálculo em processos paralelos. Imprima os resultados ;

## 9. Espera por Resultados Futuros
Modifique o exercício anterior para coletar e exibir os resultados conforme eles forem completados, usando o método `as_completed()` da biblioteca `concurrent.futures` ;

## 10. Introdução ao Dask - Operações Simples
Usando a biblioteca `dask`, crie um array aleatório de 1 milhão de elementos e calcule a soma total dos valores de forma paralela. Exiba o tempo de execução do código ;

## 11. Computações Pausadas com Dask
Implemente uma série de operações matemáticas (adição, multiplicação, subtração) sobre arrays Dask e execute-as de forma "lazy" (sem computação imediata). Use `compute()` para calcular os resultados ao final ;

## 12. Uso de Dask DataFrame
Carregue um grande conjunto de dados CSV usando o `dask.dataframe`. Realize uma agregação simples (como média ou soma) sobre uma coluna numérica e exiba os resultados ;