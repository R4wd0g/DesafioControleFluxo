# Desafio de Controle de Fluxo - Trilha Java Básico

Projeto desenvolvido como parte do curso de Java Básico na [Digital Innovation One](https://www.dio.me/).

## Autores

- Gleyson Sampaio (instrutor)

## Descrição do Desafio

O objetivo deste projeto é exercitar os conceitos apresentados no módulo de Controle de Fluxo, implementando um sistema simples que receba dois parâmetros via terminal e realize uma contagem incremental entre eles. Além disso, o sistema deve validar as entradas e tratar exceções personalizadas.

### Cenário

O sistema deve receber dois números inteiros via terminal. Com esses números, o sistema irá:

- Realizar uma contagem usando um loop `for`, imprimindo no console cada número da sequência entre os dois valores fornecidos.
- Se o primeiro parâmetro for **maior** que o segundo, deverá ser lançada uma exceção customizada (`ParametrosInvalidosException`) com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".

### Exemplo

- Entrada: 12 e 30  
  Saída: Imprime os números de 1 a 18 no console, como:  
  `"Imprimindo o número 1"`, `"Imprimindo o número 2"`, até `"Imprimindo o número 18"`.

- Se o primeiro número for maior que o segundo (exemplo: 30 e 12), o sistema deve lançar a exceção `ParametrosInvalidosException` com a mensagem: `"O segundo parâmetro deve ser maior que o primeiro"`.

## Estrutura do Projeto

1. **Classe `Contador.java`**  
   Contém a lógica principal do sistema. Responsável por capturar os parâmetros de entrada e realizar a contagem.

2. **Classe `ParametrosInvalidosException.java`**  
   Representa a exceção customizada para validar os parâmetros fornecidos.

## Como Executar

1. Clone este repositório em sua máquina local.
2. Compile as classes `Contador.java` e `ParametrosInvalidosException.java`.
3. Execute o programa via terminal e insira os dois números conforme solicitado.

## Pré-requisitos

- JDK 8 ou superior
- IDE de sua escolha (IntelliJ, Eclipse, etc.) ou editor de texto simples com compilação manual via terminal.
