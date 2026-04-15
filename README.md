# Space Invader

Jogo clássico estilo Space Invaders desenvolvido com HTML5 Canvas e JavaScript (ES Modules).

## Funcionalidades

- Nave controlada pelo jogador com movimento lateral.
- Tiros do jogador e dos inimigos.
- Sistema de pontuação por tipo de inimigo.
- Tela de vitória e tela de game over.
- Reinício de partida.
- Pausa durante o jogo.

## Controles

- `Seta Esquerda` ou `A`: mover para esquerda
- `Seta Direita` ou `D`: mover para direita
- `Espaço`: atirar
- `P`: pausar/continuar

## Estrutura do projeto

- `index.html`: interface principal do jogo.
- `src/javascript/index.js`: loop do jogo e estados (início, pausa, vitória e derrota).
- `src/javascript/Player.js`: movimentação e tiro do jogador.
- `src/javascript/EnemyController.js`: lógica da formação de inimigos.
- `src/javascript/BulletController.js`: controle de disparos e colisões.

## Como executar

Como o projeto é modular (`type="module"`), o ideal é rodar com servidor local.

Exemplo com Python:

```bash
python -m http.server 5500
```

Depois abra no navegador:

`http://localhost:5500`

## Melhorias recentes

- Correção de acúmulo de listeners de teclado após reinícios.
- Suporte às teclas `A/D` além das setas.
- Pausa com tecla `P` e mensagem visual no canvas.

## Repositório

Projeto no GitHub: [AiraVidal/Space_invader](https://github.com/AiraVidal/Space_invader)
