# Estúdio de Impressão de Fotos (PWA)

App web instalável para iPhone, iPad, Android e computador. Ajusta fotos (brilho, contraste, saturação, filtros), monta várias fotos numa só folha (grade 4×4, tamanhos fixos, várias páginas) e imprime ou salva em PDF.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `estudio-fotos`).
2. Envie **todo o conteúdo desta pasta** (`index.html`, `manifest.webmanifest`, `sw.js` e a pasta `icons/`) para a raiz do repositório.
3. Vá em **Settings → Pages**, em *Build and deployment* escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/estudio-fotos/`.

## Instalar como app
- **iPhone/iPad (Safari):** Compartilhar → *Adicionar à Tela de Início*.
- **Android (Chrome):** menu ⋮ → *Instalar app* (ou o botão 📲 Instalar do site).
- **Computador (Chrome/Edge):** ícone de instalar na barra de endereço.

Depois do primeiro acesso, funciona sem internet. Para atualizar, altere `V` em `sw.js` (ex.: `fotos-v4`).

## Impressão
- Wi‑Fi: use AirPrint (iOS) ou Mopria/driver do fabricante (Android) pela janela de impressão.
- Bluetooth: pareie a impressora no sistema; o navegador não se conecta direto a ela.
- Se o celular ignorar o tamanho da folha, escolha “Salvar PDF” e imprima pelo app da impressora.
- Ajuste: escala 100%, sem margens, gráficos de fundo ligados.
