# Cartão de Crédito Válido

## Índice

* [1. Introdução](#1-Introdução)
* [2. Resumo do projeto](#2-resumo-do-projeto)

## 1. Introdução

O [algoritmo de Luhn](https://en.wikipedia.org/wiki/Luhn_algorithm), também
chamado de módulo 10, é um método de soma de verificação, usado para validar
números de identificação, como o IMEI de telefones celulares, cartões de crédito
etc.

Esse algoritmo é simples. Obtemos o inverso do número a ser verificado (que
contém apenas dígitos [0-9]); todos os números que ocupam uma posição par devem
ser multiplicados por dois; se esse número for maior ou igual a 10, devemos
adicionar os dígitos do resultado; o número a verificar será válido se a soma de
seus dígitos finais for um múltiplo de 10.

![gráfico do algoritmo de
Luhn](https://www.101computing.net/wp/wp-content/uploads/Luhn-Algorithm.png)

## 2. Resumo do projeto

Neste projeto foi criado um aplicativo Web que permite ao usuário
validar o número de um cartão de crédito.  Além disso, foi implementado a funcionalidade de
ocultar todos os dígitos de um cartão, exceto
os quatro últimos.

![image](https://github.com/julirmatos/SAP010-card-validation/assets/106282913/64d6befb-1883-4e0e-888e-d74eb9726a6c)
![image](https://github.com/julirmatos/SAP010-card-validation/assets/106282913/eeca326e-418a-463a-af61-5a817581c8a2)
![image](https://github.com/julirmatos/SAP010-card-validation/assets/106282913/8ed8cc16-2442-4e80-9c77-45e2dae8bfc6)
![image](https://github.com/julirmatos/SAP010-card-validation/assets/106282913/97d3f223-ffe2-4474-b292-a00e6c4d9f17)
![image](https://github.com/julirmatos/SAP010-card-validation/assets/106282913/bd324960-b440-47d2-9fd0-7b0cc1c6a8db)

(https://sap010-card-validation.julirmatos.repl.co/index.html)





