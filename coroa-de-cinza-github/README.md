# Coroa de Cinza — instalar no iPhone

## 1. Pôr o jogo online (GitHub Pages, grátis)
1. Cria uma conta em github.com (se ainda não tiveres).
2. Toca em **New repository**, dá-lhe o nome `coroa-de-cinza`, deixa-o **Public** e cria.
3. Toca em **Add file → Upload files** e envia estes ficheiros (não envies a pasta nem o .zip):
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`, `.nojekyll`, `README.md`
4. Toca em **Commit changes**.
5. Vai a **Settings → Pages**. Em *Branch* escolhe `main` e `/ (root)` e guarda.
6. Espera 1 a 2 minutos. O jogo fica em `https://O-TEU-UTILIZADOR.github.io/coroa-de-cinza/`

## 2. Instalar no iPhone
1. Abre esse endereço no **Safari** (tem de ser o Safari).
2. Toca em **Partilhar** e depois em **Adicionar ao ecrã principal**.
3. Abre o jogo pelo ícone da coroa: fica em ecrã inteiro, sem barras, e funciona sem internet depois da primeira vez.

## Atualizar o jogo
Envia o novo `index.html` para o mesmo repositório (substitui o antigo). Na próxima vez que abrires a app com internet, ela atualiza sozinha. O progresso fica guardado no iPhone.

## Jogar com amigos (multijogador)
1. Todos abrem o jogo pelo endereço do GitHub Pages (ou pela app instalada) e entram com o seu herói.
2. Um de vocês vai a **Opções → 👥 Jogar com amigos → Criar sala**. Aparece um código de 5 letras (ex.: `K7PQ2`).
3. Os outros vão ao mesmo menu, escrevem o código em **Entrar numa sala** e tocam em **Entrar**.
4. Até 4 jogadores. Cada um vê os outros no mapa (com nome, vida, montada, grifo e barco), com setas na borda do ecrã a apontar para quem está longe.
5. Os inimigos e chefes que atacam juntos perdem vida em todos os ecrãs, e quando um morre conta para todos.
6. No mesmo menu há **Ir ter** (vais para junto de um amigo) e **mensagens rápidas** ("Olá!", "Ajuda aqui!"…).

Precisa de internet. A ligação é direta entre os telemóveis (WebRTC/PeerJS), sem servidor vosso. Se não ligarem em redes móveis diferentes, experimentem todos na mesma rede Wi-Fi.
