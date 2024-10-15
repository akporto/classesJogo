# Escrevendo as classes de um Jogo

Este projeto em JavaScript implementa uma classe genérica que representa um herói de aventura. Cada herói possui um nome, idade, e tipo (guerreiro, mago, monge, ninja) e pode realizar um ataque que varia conforme seu tipo.

## 🛠️ Funcionalidades

- Criação de heróis com propriedades personalizadas: `nome`, `idade`, e `tipo`.
- Método `atacar()` que exibe uma mensagem de ataque com base no tipo de herói:
  - **Mago**: "usou magia"
  - **Guerreiro**: "usou espada"
  - **Monge**: "usou artes marciais"
  - **Ninja**: "usou shuriken"
  
## 🚀 Como Usar

1. Clone o repositório ou baixe os arquivos no seu computador.
2. Abra o arquivo `.js` no seu editor de código favorito.
3. Use a classe `Heroi` para criar novos heróis e invocar o método `atacar()` para simular um ataque baseado no tipo de herói.

### Exemplo de Criação de Heróis


let heroi1 = new Heroi("Arthur", 30, "guerreiro");
let heroi2 = new Heroi("Merlin", 150, "mago");
let heroi3 = new Heroi("Shaolin", 40, "monge");
let heroi4 = new Heroi("Naruto", 25, "ninja");

Exemplo de Uso: 

heroi1.atacar(); // guerreiro atacou usando espada
heroi2.atacar(); // mago atacou usando magia
heroi3.atacar(); // monge atacou usando artes marciais
heroi4.atacar(); // ninja atacou usando shuriken

Ao executar o código acima, a saída será:

O guerreiro atacou usando espada
O mago atacou usando magia
O monge atacou usando artes marciais
O ninja atacou usando shuriken

## 🔢 Lógica de Ataque por Tipo
Mago: O ataque será "usou magia".
Guerreiro: O ataque será "usou espada".
Monge: O ataque será "usou artes marciais".
Ninja: O ataque será "usou shuriken".

## 🧑‍💻 Tecnologias Utilizadas
JavaScript: A linguagem principal utilizada para a lógica do programa.
