# 🔢 Contador  

## 📌 Descrição  
Este projeto é um contador simples onde o usuário informa dois números inteiros. O programa subtrai o menor número do maior e imprime os números incrementais até o resultado da subtração.  

Além disso, foi implementado **tratamento de exceção personalizada**, garantindo que o primeiro número informado seja **menor** que o segundo. Caso o primeiro número seja maior que o segundo, é lançada uma exceção personalizada chamada `ParametrosInvalidosException`, que é tratada e uma mensagem de erro é exibida para o usuário.

O intuito deste projeto é praticar o **tratamento de exceção** em Java, explorando seu funcionamento e a aplicação de exceções personalizadas.

## 🚀 Tecnologias Utilizadas  
- ☕ Java  
- 🎯 Tratamento de exceções com `try-catch` e exceção personalizada `ParametrosInvalidosException`  
- ⌨️ Entrada de dados com `Scanner`  

## 🎯 Funcionalidade  
✅ O usuário informa dois números inteiros.  
✅ O programa verifica se o primeiro número é menor que o segundo.  
✅ Se a condição for atendida, imprime os números de `1` até a diferença entre os dois valores.  
✅ Se o primeiro número for **maior**, uma exceção personalizada (`ParametrosInvalidosException`) é lançada e tratada.  
