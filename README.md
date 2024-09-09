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
##### Number é um encapsulado que permite trabalhar com valores numéricos

javascript
let inteiro = 42;
let decimal = 3.14;


### 4. *Switch Case*
##### O switch case é uma estrutura de controle utilizada em diversas linguagens de programação, como C, C++, Java e JavaScript, que permite verificar um valor contra várias condições de forma eficiente e organizada


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
##### A estrutura de código if-else é um conceito fundamental na programação que permite que um programa tome decisões com base em condições específicas. 


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
##### o prompt de comando é um programa que emula o campo de entrada em uma tela de interface de usuário baseada em texto com a interface gráfica do usuário (IU) do Windows. 


javascript
let nome = prompt('Qual é o seu nome?');
console.log('Olá, ${nome}!`);


### 7. *Concatenação*
##### Concatenação é a operação de unir duas ou mais cadeias de caracteres em uma única cadeia. 

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

atividades

https://codepen.io/Nicolle-Nico/pen/wvLeMEO
https://codepen.io/Nicolle-Nico/pen/eYwyQQW
https://codepen.io/Nicolle-Nico/pen/dyBVyLy
https://codepen.io/Nicolle-Nico/pen/MWMOrOq
https://codepen.io/Nicolle-Nico/pen/eYwyQQW
