# Plucking Mango (JACA-NA-EMILIA)

Jogo de física em [p5.js](https://p5js.org/) + [matter.js](https://brm.io/matter-js/) (título interno "Plucking Mango"): o jogador arrasta uma pedra até um estilingue, mira e solta para derrubar mangas presas em uma árvore. Ao acertar uma manga, ela deixa de ser estática e cai por gravidade. A tecla espaço reposiciona a pedra no estilingue para uma nova tentativa.

## Estado do repositório

Este repositório está incompleto: `index.html` e `sketch.js` referenciam arquivos que não existem aqui — `libraries/matter.js`, `libraries/p5.js`, `libraries/p5.play.js`, os scripts `js/tree.js`, `js/stone.js`, `js/ground.js`, `js/mango.js`, `js/Stand.js`, `js/launcher.js`, e as imagens `images/boy.png` e `images/emilia.png`. O único commit do histórico removeu um zip de template (`Project-C28-template-main.zip`) sem que essas pastas de apoio tivessem sido extraídas/commitadas. Como está, a página não roda sem recriar essas dependências.

## Tecnologias

- [p5.js](https://p5js.org/) + [p5.play.js](https://p5play.molleindustria.org/) para desenho e sprites
- [matter.js](https://brm.io/matter-js/) como motor de física (corpos, colisão por distância entre pedra e mangas)
- JavaScript puro, sem build

## Estrutura presente

- `sketch.js` — lógica do jogo: setup da cena, detecção de colisão pedra/manga, controles de mouse e teclado
- `style.css` — estilo básico do canvas
- `index.html` — referencia bibliotecas e scripts auxiliares que faltam no repositório (ver acima)

## Como rodar

Não é possível rodar como está: faltam as bibliotecas, os scripts das classes (`tree`, `stone`, `ground`, `mango`, `Stand`, `launcher`) e as imagens usadas em `sketch.js`. Seria necessário recriar ou recuperar essas pastas (`libraries/`, `js/`, `images/`) antes de abrir `index.html`.
