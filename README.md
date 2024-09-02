## Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

Claro! Vamos explorar cada um desses conceitos em JavaScript:

### 1. *String*

##### Strings são sequências de caracteres, escritas entre aspas simples ou duplas.

javascript
let str1 = 'Texto simples';
let str2 = "Outro texto";
let str3 = `Texto com interpolação: ${str1}`;


### 2. *Variável*

##### As variáveis ​​podem ser usadas para armazenar dados em um programa, como strings, números, objetos JSON ou valores booleanos. Em JavaScript, existem três tipos de variáveis ​​diferentes: var , let , e const .

*var: Declara variáveis com escopo de função ou global.*
  javascript
  var idade = 30;
  

*let: Declara variáveis com escopo de bloco.*
  javascript
  let nome = "Maria";
  

*const: Declara variáveis com escopo de bloco que não podem ser reatribuídas.*
  javascript
  const pi = 3.14;
  

### 3. *Number*


javascript
let inteiro = 42;
let decimal = 3.14;


### 4. *Switch Case*


javascript
let cor = 'verde';

switch (cor) {
  case 'vermelho':
    console.log('A cor é vermelha.');
    break;
  case 'verde':
    console.log('A cor é verde.');
    break;
  case 'azul':
    console.log('A cor é azul.');
    break;
  default:
    console.log('Cor desconhecida.');
}


### 5. *If e Else*


javascript
let idade = 18;

if (idade >= 18) {
  console.log('Você é adulto.');
} else {
  console.log('Você é menor de idade.');
}



javascript
let nota = 85;

if (nota >= 90) {
  console.log('Nota A');
} else if (nota >= 80) {
  console.log('Nota B');
} else if (nota >= 70) {
  console.log('Nota C');
} else {
  console.log('Nota abaixo de C');
}


### 6. *Prompt*


javascript
let nome = prompt('Qual é o seu nome?');
console.log('Olá, ${nome}!`);


### 7. *Concatenação*


  javascript
  let primeiroNome = 'John';
  let sobrenome = 'Doe';
  let nomeCompleto = primeiroNome + ' ' + sobrenome;
  console.log(nomeCompleto); // "John Doe"
  

  javascript
  let primeiroNome = 'John';
  let sobrenome = 'Doe';
  let nomeCompleto = `${primeiroNome} ${sobrenome}`;
  console.log(nomeCompleto); // "John Doe"
