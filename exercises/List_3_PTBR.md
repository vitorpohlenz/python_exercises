# Lista de Exercícios sobre Orientação a Objetos, Herança e Bibliotecas em Python

## 1. Criando uma Classe Simples
Crie uma classe chamada `Dog` que tenha os atributos `name` e `age`. Acesse esses atributos;

## 2. Classe com método
Crie uma classe chamada `Car` com atributos `brand`, `model` e `year`. Crie um método que exiba essas informações;

## 3. Herança Simples
Crie uma classe `Vehicle` com o método `run()`. Em seguida, crie uma classe derivada `Bicycle` que sobrescreva o método `run()` para mostrar a mensagem `"The bike is running"`;

## 4. Uso do `super()`
Crie uma classe `Animal` que tenha um método `sound()` que imprima `"The Animal makes sound"`. Em seguida, crie uma classe `Dog` que herde de `Animal` e sobrescreva o método `sound()` para imprimir `"The Dog barks"`. Utilize o `super()` para chamar o método da classe pai dentro da classe `Dog`;

## 5. Verificando o Tipo de Objeto
Crie um objeto da classe `Dog` e utilize a função `type()` para verificar o tipo do objeto;

## 6. Verificando Instância de Classe
Crie duas classes: `Person` e `Student`, onde `Student` herda de `Person`. Crie uma instância de `Student` e verifique se ela é uma instância tanto de `Student` quanto de `Person` utilizando `isinstance()` e `issubclass()`;

## 7. Atributos e métodos de Classe
Cheque se a classe `list` possui os métodos `append` e `drop`;

## 8. Utilizando a módulo `os`
Liste os diretórios da pasta anterior de onde o códio Python está sendo executado;

## 9. Importando Módulos do Numpy
Implemente uma função que use o `numpy` para gerar uma matriz de números aleatórios e exiba seus valores;

## 10. Importando e Usando Pandas
Implemente um programa que use o `pandas` para criar um DataFrame com os dados de uma lista de dicionários e exiba-o;

## 11. Importando e Usando Random
Crie um programa que use o módulo `random` para gerar um número inteiro aleatório entre 1 e 100;

## 12. Utilizando o módulo `datetime`
Veja qual será a data de 10 dias após o momento da execução do código atual;

## 13. Utilizando o módulo `re`
Remova todas as pontuações de uma string usando `re`;

## 14. Método Mágico `__str__()`
Crie uma classe `Book` com os atributos `title` e `author`. Sobrescreva o método `__str__()` para retornar uma string formatada ao imprimir o objeto;

## 15. Herança Múltipla
Crie duas classes `Animal` e `Aquatic`. Crie uma terceira classe `Dolphin` que herda das duas primeiras e implemente métodos/atributos específicos;

## 16. Usando `dir()` para Verificar Atributos e Métodos
Crie uma instância de qualquer classe e use a função `dir()` para listar seus métodos e atributos;