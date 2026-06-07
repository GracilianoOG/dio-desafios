# 📖 Miniguia de Estudos - TypeScript

## 📚 Contexto e Objetivos

Neste projeto, escolhi estudar **TypeScript**, uma linguagem baseada em JavaScript que adiciona tipagem estática ao desenvolvimento.

### Objetivos de estudo

- Entender os conceitos básicos do TypeScript;
- Aprender a declarar tipos, interfaces e funções;
- Conhecer as vantagens do TypeScript em projetos maiores;
- Praticar a utilização junto com JavaScript.

## 🤖 Engenharia de Prompts e Aprendizados

### Prompt 1

Eu comecei a testar alguns prompts mais simples para ver o que a IA do NotebookLM retorna:

> "Explique o que é TypeScript de forma simples para iniciantes."

_O resultado dessa resposta acaba sendo bastante massante de ler, então eu decidi refazer o prompt pedindo que a resposta seja mais concisa._

> "Explique o que é TypeScript de forma simples para iniciantes de forma concisa, em um parágrafo."

**Resultado:**

_"O TypeScript é uma linguagem de programação que funciona como um superset (supersuporte) do JavaScript, o que significa que ele contém tudo o que existe no JavaScript e adiciona recursos extras. Sua principal funcionalidade é a tipagem estática, permitindo que você defina explicitamente se uma informação é um texto, número ou outro formato específico. Isso ajuda a capturar diversos erros de programação precocemente durante a fase de escrita, antes mesmo do código ser executado. Ao final do processo, o TypeScript é compilado para JavaScript puro, removendo as anotações de tipo para que o resultado final funcione em qualquer navegador ou ambiente que suporte JavaScript. Dessa forma, ele atua como uma camada de proteção que traz muito mais segurança, confiança e produtividade para o desenvolvedor."_

Caso o prompt não seja feito de forma adequada, a IA acaba gerando um resultado indesejado, como uma resposta longa ou fora do foco da pergunta (que faltou detalhes). A falta desses detalhes cria uma resposta pobre, por mais longa que seja.

### Prompt 2

> "Mostre exemplos práticos de interfaces em TypeScript."

_O resultado desse prompt é, mais uma vez, uma resposta longa que aborda partes mais complexas sobre interfaces. Caso o objetivo seja obter exemplos mais simples, o prompt precisaria ser modificado._

> "Mostre exemplos práticos de interfaces em TypeScript. Crie exemplos simples, foque nos conceitos iniciais."

_A resposta melhora um pouco, mas permanece longa, e ainda aborda React, que é uma framework citada em uma das fontes. O prompt precisa ser modificado novamente para gerar um resultado mais conciso e focado._

> "Mostre exemplos práticos de interfaces em TypeScript. Crie exemplos simples, foque nos conceitos iniciais. Gere uma resposta curta e simples de entender. Foque no essencial e não aborde nada sobre frameworks."

**Resultado:**

A resposta acabou saíndo mais curta, focada no essencial do TypeScript e sem ir para outros assuntos como frameworks.

**Trecho da resposta:**

1. Estrutura Básica de Objeto
   O uso mais comum é definir quais campos um objeto deve ter e de que tipo eles são.

```ts
interface Usuario {
  id: number;
  nome: string;
}

const novoUsuario: Usuario = {
  id: 1,
  nome: "Alice",
};
```

## 🗒️ Conceitos Principais para Estudo

Os conceitos que acho importante entender no começo dos estudos em TypeScript são:

- Tipagem estática;
- Tipos primitivos;
  - Number
  - String
  - Boolean
  - Any
  - Null e Undefined
  - Void e Unknown
- Interfaces;
- Types;
- Funções tipadas;
  - Tipagem de parâmetros
  - Tipagem de retorno
- Classes;
- Generics.

## 📝 Glossário

| Termo            | Significado                                                |
| ---------------- | ---------------------------------------------------------- |
| Interface        | Estrutura para definir objetos                             |
| Type             | Define tipos personalizados                                |
| Compiler         | Traduz TypeScript para JavaScript                          |
| Tipagem Estática | Verificação de tipos antes da execução                     |
| JavaScript       | Linguagem de programação interpretada                      |
| Classe           | Molde (plantas) usadas na programação orientada a objetos. |

## 💡 Prompts Reutilizáveis

- [Tipos Primitivos em TypeScript](./prompts/tipos-primitivos.txt)
- [O Que é TypeScript (em um parágrado)](./prompts/o-que-eh-typescript.txt)
- [Diferença entre JavaScript e TypeScript](./prompts/js-ts-diferenca.txt)
- [Exemplos de Interfaces](./prompts/interfaces-exemplos.txt)
- [Diferença entre Interfaces e Types](./prompts/interface-type-diferenca.txt)

## 🔎 Fontes Utilizadas

Fontes utilizadas no NotebookLM:

1. [Documentação Oficial TypeScript](https://www.typescriptlang.org/docs/)
2. [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
3. [MDN Web Docs - JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
4. [Learn TypeScript - Full Course for Beginners](https://www.youtube.com/watch?v=SpwzRDUQ1GI)
5. [TypeScript Crash Course](https://www.youtube.com/watch?v=BCg4U1FzODs)
6. [TypeScript - Glossary](https://developer.mozilla.org/en-US/docs/Glossary/TypeScript)
7. [Effective TypeScript](https://effectivetypescript.com/)

## 🚀 Conclusão

O estudo de TypeScript com o auxilio do NotebookLM acelerou meu aprendizado, proporcionando-me um melhor entendimento da linguagem TypeScript e da ferramenta em si para criar resumos e questionários sobre o assunto.
