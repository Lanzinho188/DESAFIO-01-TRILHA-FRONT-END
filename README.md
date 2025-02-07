# DESAFIO-01-TRILHA-FRONT-END
1) Crie uma variável chamada nome e atribua seu nome a ela. Em seguida, exiba o valor dessa variável.
```js
let nome = 'Raislan';
console.log(`Olá ${nome}`);
```
2) Crie duas variáveis: uma chamada idade e outra chamada altura. Atribua a idade o valor 25 e a altura o valor 1.75. Exiba ambos os valores.
```js
let idade = 25;
let altura = 1.75;

console.log(`Idade: ${idade} anos\nAltura: ${altura} metros`);
```
3) Crie uma variável chamada preco com o valor 50 e uma variável desconto com o valor 0.2 (20%). Calcule o preço com desconto e exiba o valor final.
```js
let preco = 50;
let desconto = 0.2;

let precoComDesconto = preco - (preco * desconto);
console.log(`Preço com desconto: R$${precoComDesconto.toFixed(2)}`);
```
4) Crie uma variável chamada temperatura e atribua o valor 30. Se a temperatura for maior que 25, exiba a mensagem "Está calor!". Caso contrário, exiba "Está fresco!".
```js
let temperatura = 30;

if (temperatura > 25) {
   console.log('Está calor!');
} else {
   console.log('Está fresco!');
}
```
5) Crie uma variável idade e atribua um valor. Se a pessoa for maior de idade (18 ou mais), exiba "Você é maior de idade". Caso contrário, exiba "Você é menor de idade".
```js
let idade = 20;

if (idade >= 18) {
   console.log('Você é maior de idade');
} else {
   console.log('Você é menor de idade');
}
```
6) Crie uma variável chamada nota e atribua um valor entre 0 e 10. Se a nota for maior ou igual a 7, exiba "Aprovado". Se for entre 5 e 6, exiba "Recuperação". Caso contrário, exiba "Reprovado".
```js
let nota = 5;

if (nota >= 7) {
   console.log('Aprovado');
} else if (nota >= 5) {
   console.log('Recuperação');
} else {
   console.log('Reprovado');
}
```
7) Crie duas variáveis, numero1 e numero2, e atribua valores a elas. Verifique se os dois números são iguais e, caso sejam, exiba "Os números são iguais". Caso contrário, exiba "Os números são diferentes".
```js
let numero1 = 15;
let numero2 = 12;

if (numero1 == numero2) {
   console.log('Os números são iguais');
} else {
   console.log('Os números são diferentes');
}
```
8) Crie uma variável chamada nome e uma variável chamada idade. Exiba a mensagem "Olá, meu nome é [nome] e eu tenho [idade] anos", utilizando concatenação.
```js
let nome = "Raislan";
let idade = 20;

console.log('Olá, meu nome é ' + nome + ' e tenho ' + idade + ' anos');
```
9) Crie um loop que imprima os números de 1 a 10 na tela.
```js
for (let i = 1; i <= 10; i++) {
   console.log(i);
}
```
10) Crie um loop que peça ao usuário para digitar um número até que ele digite o número 5.
```js
let input = 0;
while (input != 5) {
   input = parseInt(prompt("Digite um número"));
}
```
11) Crie um loop que imprima a tabuada do número 7, de 1 a 10.
```js
for (let i = 1; i <= 10; i++) {
   let resultado = 7 * i;
   console.log(`7 x ${i} = ${resultado}`);
}
```
12) Crie um loop que exiba todos os números pares de 0 a 20.
```js
for (let i = 0; i <= 20; i++) {
   if (i % 2 == 0) {
      console.log(i);
   }
}
```
13) Escreva um código que calcule a área de um círculo. Utilize uma função para realizar o cálculo. A função deve receber o raio como parâmetro e retornar a área.
```js
function calcularAreaDoCirculo(raio) {
   // Fórmula para calcular área do círculo: A = pi * raio²
   return Math.PI * Math.pow(raio, 2);
}

let raio = 5.9;
let area = calcularAreaDoCirculo(raio);

console.log('Calculando a área de um círculo');
console.log(`Raio: ${raio} metros\nÁrea: ${area.toFixed(2)} metros quadrados`);
```
14) Comente seu código explicando o que cada parte faz. Crie um programa simples que calcule a soma de dois números e imprima o resultado.
```js
// Cria uma função para somar dois números
// Recebe os números a ser somado como parâmetros
function somarDoisNumeros(num1, num2) {
   return num1 + num2;  // Retorna a soma dos números
}

// Cria uma variável para armazenar o primeiro número
let num1 = 15;

// // Cria uma variável para armazenar o segundo número
let num2 = 18;

// Cria uma variável para armazenar o resultado da soma retornado pela função somarDoisNumeros(num1, num2)
let resultadoSoma = somarDoisNumeros(num1, num2);

// Imprime no console o resultado da soma utilizando template string
console.log(`O resultado da soma é: ${resultadoSoma}`);
```
15) Refatore o código abaixo para que seja mais legível, usando boas práticas de nomenclatura e separando o código em funções:
```js
x = 10

y = 20

z = x+y

console.log(z)
```
```js
function somarDoisNumeros(numero1, numero2) {
   return numero1 + numero2
}

let numero1 = 10;
let numero2 = 20;

let resultadoDaSoma = somarDoisNumeros(numero1, numero2);
console.log(`O resultado da soma é: ${resultadoDaSoma}`);
```
