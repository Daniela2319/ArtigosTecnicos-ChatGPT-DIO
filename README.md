<div aling='center'>
<img src="./Artigo_ChatGPT/images/Slide1.jpg">
</div>

<br>

# TypeScript: Princípios de Programação Orientada a Objetos

Se você está mergulhando no mundo do desenvolvimento front-end, provavelmente já ouviu falar sobre TypeScript. Mas o que muitos não sabem é como ele pode ser poderoso quando combinado com os princípios da Programação Orientada a Objetos (POO). Neste artigo, vamos explorar como dominar o TypeScript através dos fundamentos da POO.

## O que é TypeScript: 💻

Antes de mergulharmos nos princípios da POO, vamos entender o que é o TypeScript. TypeScript é uma linguagem de programação que se baseia no JavaScript, mas adiciona recursos extras, como tipagem estática, que ajudam os desenvolvedores a escrever código mais seguro e legível. Com o TypeScript, podemos definir tipos para variáveis, parâmetros de função e até mesmo para objetos inteiros.

## O que é Programação Orientada a Objetos: 👩‍💻

Agora, vamos falar sobre Programação Orientada a Objetos. Imagine que você está construindo uma casa de Lego. Cada peça de Lego é como um objeto em POO. Cada peça tem suas próprias características (como cor, forma) e pode realizar ações específicas (como encaixar em outras peças). Da mesma forma, na POO, organizamos nosso código em objetos, que têm propriedades (características) e métodos (ações).

<div align="center">
<img src="./Artigo_ChatGPT/images/imgLego.jpg"  width="800" height="200">
 <p align="center">
    01 - Figura de demostração com Lego.
 </p>
</div>

## Como dominar TypeScript com POO:

Vamos agora combinar o TypeScript com os princípios da POO em um exemplo prático.

```
// Exemplo de uma classe Pessoa em TypeScript
class Pessoa{
nome: string;
idade: number;

constructor(nome: string, idade: number) {
this.nome = nome;
this.idade = idade;
}

apresentar() {
console.log(`Olá! Meu nome é ${this.nome} e tenho ${this.idade} anos.`);
}
}

// Usando a classe Pessoa
const pessoa1 = new Pessoa("João", 25);
pessoa1.apresentar();
```

Neste exemplo, definimos uma `classe Pessoa` com as propriedades `nome` e `idade`, e um método `apresentar()` que exibe uma mensagem com essas informações. Ao criar uma nova instância da `classe Pessoa` e chamar o método `apresentar()`, obtemos a saída desejada.

## Conclusão:

Dominar TypeScript através dos princípios da Programação Orientada a Objetos pode elevar o seu código a um novo nível. Com TypeScript, podemos escrever código mais seguro e fácil de manter, enquanto a POO nos ajuda a organizar nosso código de forma lógica e eficiente. Continue praticando e explorando esses conceitos para se tornar um desenvolvedor front-end ainda mais habilidoso! 🚀

<div aling='center'>
<img src="./Artigo_ChatGPT/images/Slide2.jpg">
</div>
