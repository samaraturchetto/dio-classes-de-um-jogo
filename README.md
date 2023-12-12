# Escrevendo as classes de um jogo

## 🎯 Objetivo

Criar uma classe generica que represente um herói de uma aventura e que possua as seguintes propriedades:

- nome;
- idade;
- tipo (ex: guerreiro, mago, monge, ninja ).

Além disso, deve ter um método chamado atacar que deve atender os seguientes requisitos:

- exibir a mensagem: "o {tipo} atacou usando {ataque}");
- aonde o {tipo} deve ser concatenando o tipo que está na propriedade da classe;
- e no {ataque} deve seguir uma descrição diferente conforme o tipo, seguindo a tabela abaixo:

  - se mago -> no ataque exibir (usou magia)
  - se guerreiro -> no ataque exibir (usou espada)
  - se monge -> no ataque exibir (usou artes marciais)
  - se ninja -> no ataque exibir (usou shuriken)

Ao final deve se exibir uma mensagem:

"o {tipo} atacou usando {ataque}"
ex: mago atacou usando magia
guerreiro atacou usando espada

## 🔨 Skills

- `Lógica de programação`:
  - Variáveis;
  - Operadores;
  - Laços de repetição;
  - Estruturas de decisões;
  - Funções;
  - Classes e Objetos
- `JavaScript`: Linguagem de programação.

## 📚 Instruções para teste

1. Escolha ou crie um diretório no seu computador;
2. Abra o diretório criado em um editor de código, (ex: [Visual Studio Code](https://code.visualstudio.com/));
3. Inicie o terminal;
4. Clone o repositório usando o comando: $ **git clone https://github.com/samaraturchetto/dio-classes-de-um-jogo.git**;
5. Navegue até o diretório correto com o comando: $ **cd dio-classes-de-um-jogo**;
6. Com o [Node.js](https://nodejs.org/en) já instalado e configurado, digite no terminal: $ **node index.js**

O programa irá exibir as mensagens solicitadas.
