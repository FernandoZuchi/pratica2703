**Roteiro de Aula Prática: Algoritmos em JavaScript e C#**

**Tema da Aula:** Algoritmos em JavaScript e C# - Comparativo prático entre linguagem tipada e não tipada.

**Duração:** 1 hora

**Objetivos:**
- Apresentar as diferenças conceituais e práticas entre JavaScript e C#.
- Compreender a importância da tipagem de dados para a programação.
- Praticar a construção de algoritmos simples nas duas linguagens.

---

**1. Boas-vindas e Introdução (5 minutos)**

"Hoje vamos colocar em prática a lógica de programação usando duas linguagens que vocês encontrarão muito no mercado: JavaScript e C#. Vamos entender como cada uma trata os dados, como elas se comportam na execução de algoritmos simples, e o que isso significa na prática." 

---

**2. Diferenças entre JavaScript e C# (10 minutos)**

**JavaScript:**
- Linguagem interpretada e dinamicamente tipada.
- Executada diretamente em navegadores ou no Node.js.
- Flexível, ideal para desenvolvimento frontend e aplicações rápidas.

**C#:**
- Linguagem compilada e estaticamente tipada.
- Usada para desenvolvimento de softwares robustos (backend, desktop, jogos com Unity).
- Fornece maior controle sobre tipos e desempenho.

**Explicação adicional:**
Enquanto o JavaScript permite maior liberdade, o C# exige mais estrutura e rigidez, o que é ótimo para aplicações complexas e escaláveis.

---

**3. Tipagem de Dados: Tipada vs Não Tipada (10 minutos)**

**JavaScript (não tipada):**
```javascript
let valor = 10;
valor = "dez"; // Nenhum erro ocorre
console.log(valor); // imprime "dez"
```

**C# (tipada):**
```csharp
int valor = 10;
valor = "dez"; // Erro de compilação
```

**Explicação:**
No JavaScript, uma mesma variável pode armazenar diferentes tipos em momentos diferentes. Isso torna o código mais flexível, mas também mais propenso a erros lógicos. Já o C# exige que você defina e mantenha o tipo de dado, o que ajuda na previsibilidade e confiabilidade da aplicação.

---

**4. Exemplos Práticos de Algoritmos (25 minutos)**

**Exemplo 1: Soma de dois números**

*JavaScript:*
```javascript
let a = 5;
let b = 3;
let soma = a + b;
console.log("Soma:", soma);
```

*C#:*
```csharp
int a = 5;
int b = 3;
int soma = a + b;
Console.WriteLine("Soma: " + soma);
```

**Exemplo 2: Laço for de 1 a 5**

*JavaScript:*
```javascript
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
```

*C#:*
```csharp
for (int i = 1; i <= 5; i++) {
  Console.WriteLine(i);
}
```

**Exemplo 3: Verificação de par ou ímpar**

*JavaScript:*
```javascript
let numero = 10;
if (numero % 2 === 0) {
  console.log("É par");
} else {
  console.log("É ímpar");
}
```

*C#:*
```csharp
int numero = 10;
if (numero % 2 == 0) {
  Console.WriteLine("É par");
} else {
  Console.WriteLine("É ímpar");
}
```

---

**5. Exercícios para Alunos (10 minutos)**

**Exercício 1:** Receba dois números e informe o maior.

*JavaScript:*
```javascript
let a = 8;
let b = 12;
if (a > b) {
  console.log("Maior: " + a);
} else {
  console.log("Maior: " + b);
}
```

*C#:*
```csharp
int a = 8;
int b = 12;
if (a > b) {
  Console.WriteLine("Maior: " + a);
} else {
  Console.WriteLine("Maior: " + b);
}
```

**Exercício 2:** Calcule a média de 3 notas e diga se o aluno foi aprovado (média >= 7).

*JavaScript:*
```javascript
let n1 = 6, n2 = 7, n3 = 9;
let media = (n1 + n2 + n3) / 3;
if (media >= 7) {
  console.log("Aprovado com média: " + media);
} else {
  console.log("Reprovado com média: " + media);
}
```

*C#:*
```csharp
float n1 = 6, n2 = 7, n3 = 9;
float media = (n1 + n2 + n3) / 3;
if (media >= 7) {
  Console.WriteLine("Aprovado com média: " + media);
} else {
  Console.WriteLine("Reprovado com média: " + media);
}
```

**Exercício 3:** Imprima a tabuada de um número.

*JavaScript:*
```javascript
let num = 5;
for (let i = 1; i <= 10; i++) {
  console.log(num + " x " + i + " = " + (num * i));
}
```

*C#:*
```csharp
int num = 5;
for (int i = 1; i <= 10; i++) {
  Console.WriteLine(num + " x " + i + " = " + (num * i));
}
```

---

**6. Encerramento e Dúvidas (5 minutos)**

"Muito bem! Hoje vocês viram como a mesma lógica pode ser aplicada em diferentes linguagens, cada uma com suas características. Isso é fundamental para desenvolver o raciocínio de programação. Continuem praticando!"

---

Foco nos estudos!
