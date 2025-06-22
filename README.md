# 📘 Desafio de Controle de Fluxo - Java

Este projeto foi desenvolvido como parte do meu aprendizado em Java, com foco na prática de **controle de fluxo e tratamento de exceções**.

## 💡 Descrição do Desafio

O objetivo é criar um programa que receba **dois parâmetros inteiros** do usuário via terminal:

- Se o **segundo número for maior que o primeiro**, o programa imprime a quantidade de interações necessárias com base na diferença entre os dois valores.
- Se o **primeiro número for maior que o segundo**, o programa lança uma **exceção personalizada**, informando o erro de entrada.


### Exemplo 1:
Entrada:
Digite o primeiro parâmetro: 3 
Digite o segundo parâmetro: 10

Saída:
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
Imprimindo o número 6
Imprimindo o número 7

### Exemplo 2:
Entrada:
Digite o primeiro parâmetro: 3 
Digite o segundo parâmetro: 1

Saída:
O segundo parâmetro deve ser maior que o primeiro

## 🛠️ Estrutura do Projeto

- `Contador.java`: classe principal que executa a leitura dos parâmetros, realiza a verificação e imprime os valores.
- `ParametrosInvalidosException.java`: classe que representa a exceção customizada lançada em caso de erro na entrada dos dados.

## 🚀 Como Executar

1. Clone este repositório ou baixe os arquivos do projeto.
2. Compile as classes com o comando:
javac Contador.java ParametrosInvalidosException.java
3. Execute o programa:
java Contador


## 🧠 Aprendizados

- Utilização de `Scanner` para entrada de dados.
- Estrutura de repetição `for`.
- Criação de exceções personalizadas.
- Boas práticas de organização de código em Java.

---

💬 *Desenvolvido com dedicação por um estudante Java em jornada constante de evolução.*  
[são 2 da manhã do dia 22/06/2025]






