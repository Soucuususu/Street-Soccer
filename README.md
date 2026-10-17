# Street Soccer — protótipo offline

Jogo mobile em HTML, CSS e JavaScript, preparado para GitHub Pages.

## Arquivos
- `index.html` — menu, navegação e campo.
- `style.css` — interface responsiva e controles.
- `game.js` — simulação local, física básica, controles e salvamento.

## Controles
- **Mover:** analógico esquerdo.
- **Passe:** analógico próprio; a direção aponta o passe e a distância do centro controla a força. Solte para passar.
- **Chute:** analógico próprio; a direção mira o chute e a barra de força oscila entre verde (fraco) e vermelho (forte). Solte para chutar.
- **PC:** WASD/setas para mover, E para passe, espaço para chutar, Esc para pausar.

## Publicar no GitHub Pages
Envie os arquivos para a raiz do repositório. Depois, em **Settings → Pages**, selecione **Deploy from a branch**, branch `main` e pasta `/ (root)`.

## Limitações desta versão
A partida é offline, com IA local simples. O contador online mostra `0 online / OFFLINE` porque ainda não há servidor. Comunidade e Top globais são páginas de pré-lançamento; chat, contas, matchmaking e rankings reais exigem backend.
