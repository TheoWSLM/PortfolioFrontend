# Theo Weber · Portfólio

Portfólio pessoal de AI Engineering, desenvolvido em Vue 3 e Vite.

## Desenvolvimento

```sh
npm ci
npm run dev
```

O Vite usa `/PortfolioFrontend/` como caminho base para funcionar no GitHub Pages. A URL local aparece no terminal ao iniciar o servidor.

## Publicação

Um push na branch `main` aciona o workflow em `.github/workflows/deploy-pages.yml`, que executa o build e publica `dist` em <https://theowslm.github.io/PortfolioFrontend/>.

```sh
npm run build
```

O currículo oferecido para download fica em `public/dev-theo-weber.pdf`. A foto editada para o topo fica em `public/theo-portrait.png`; a arte original permanece em `public/icon-main.png`.
