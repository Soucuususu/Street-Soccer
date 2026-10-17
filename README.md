# Street Soccer — protótipo offline

Jogo de futebol 2D com visual pixelado, pensado para celular e PC. O menu funciona em pé; a partida pede o celular na horizontal.

## Abrir no GitHub Pages
1. Crie um repositório público no GitHub chamado `street-soccer`.
2. Envie os quatro arquivos desta pasta para a raiz do repositório: `index.html`, `style.css`, `game.js` e `README.md`.
3. No repositório, entre em **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, branch `main` e pasta `/ (root)`, depois salve.
5. Aguarde o link do Pages aparecer nessa mesma tela.

## Controles
- Celular: analógico esquerdo move; analógico direito mira; toque em **PASSE** para passar; segure **CHUTE** para carregar e solte para chutar.
- PC: WASD/setas movem; mouse/toque nos analógicos também funcionam; `E` passa; barra de espaço carrega/solta chute; `Esc` pausa.

## Já implementado
- Partida local contra adversários controlados pelo jogo, placar e cronômetro.
- Bola dominada junto ao jogador, passes, chute carregado, gols e reinício após gol.
- Perfil, posição, cor de uniforme, histórico, estatísticas e criação de time guardados no `localStorage` do navegador.
- Interface responsiva em cinza escuro, branco e verde.

## Ainda não implementado
Multiplayer real, servidor, login, chat online, matchmaking, convites e times compartilhados. GitHub Pages hospeda os arquivos estáticos; recursos online exigirão backend/servidor.
