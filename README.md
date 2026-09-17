# TPlannerConstrutor

O Terraria Build Planner é um projeto que estou desenvolvendo para facilitar o planejamento de construções no Terraria.

A ideia surgiu da dificuldade de planejar construções maiores diretamente dentro do jogo. O objetivo é ter um editor onde seja possível montar a construção antes, usando os próprios blocos e elementos do Terraria, e depois usar esse projeto como referência dentro do jogo.

## Ideia

O usuário cria um projeto definindo sua largura e altura e recebe uma área dividida em tiles.

Dentro dela será possível pesquisar e selecionar blocos, paredes e mobílias para montar a construção.

Além do editor, quero que o projeto consiga informar quais materiais foram usados e suas respectivas quantidades.

Algumas das funcionalidades que pretendo adicionar são:

- Editor baseado em tiles
- Blocos, paredes e mobílias
- Diferentes fundos/biomas
- Ferramentas como lápis, borracha, preenchimento e conta-gotas
- Sistema de camadas
- Zoom e movimentação pelo projeto
- Lista dos materiais utilizados
- Projetos salvos
- Favoritos e materiais recentes

## Terraria

Uma parte importante do projeto será tentar representar os blocos de forma próxima ao que acontece dentro do Terraria.

Blocos como Stone, Dirt e Snow mudam visualmente dependendo dos blocos que estão conectados a eles. Por isso, pretendo implementar posteriormente um sistema de framing para escolher o sprite correto de acordo com os tiles vizinhos.

Também quero adicionar informações sobre os materiais utilizados, como receitas, estações de crafting e momento da progressão em que eles podem ser obtidos.

Por exemplo, ao terminar uma construção, além da quantidade de materiais, o programa poderá informar qual é o ponto mínimo de progressão necessário para conseguir construir aquele projeto.

## Mods

Outra ideia para o futuro é permitir que o editor trabalhe com conteúdo de mods.

A intenção é criar um sistema de Content Packs, onde o Terraria Vanilla seria a base e outros conteúdos poderiam ser adicionados separadamente.

Alguns mods que pretendo estudar futuramente:

- Calamity
- Thorium
- Fargo's
- Infernum

Isso ainda não faz parte da primeira versão do projeto.

## Tecnologias

Por enquanto o projeto será desenvolvido com:

- HTML
- CSS
- JavaScript
- Canvas API

A ideia é começar com uma estrutura simples e adicionar novas tecnologias apenas quando o projeto realmente precisar delas.

## Estrutura

```text
terraria-build-planner/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── app.js
│   ├── canvas.js
│   ├── materials.js
│   └── project.js
└── assets/
    ├── tiles/
    ├── walls/
    ├── backgrounds/
    └── icons/
