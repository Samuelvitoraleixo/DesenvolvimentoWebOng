# VerdeVivo — ONG Ambiental (Projeto Front-end)

Este repositório contém um site **SPA** acessível e responsivo para uma ONG ambiental fictícia — *VerdeVivo*. O projeto foi estruturado para atender às **Especificações Técnicas Obrigatórias** solicitadas: design system, acessibilidade (WCAG 2.1 AA), SPA básico, sistema de templates, responsividade com grid/flexbox, componentes interativos, temas (modo escuro e alto contraste), além de documentação para Git/GitHub (GitFlow, commits semânticos e releases).

## Estrutura do repositório
- `index.html` — Shell SPA
- `assets/style.min.css` — CSS (minificado)
- `assets/app.min.js` — JS (minificado, router + acessibilidade)
- `.github/ISSUE_TEMPLATE.md`, `.github/PULL_REQUEST_TEMPLATE.md`
- `CONTRIBUTING.md`, `RELEASES.md`, `README.md`, `LICENSE`

## Requisitos e como usar (resumo)
1. Clone o repositório e suba para o GitHub.
2. Siga a estratégia GitFlow: `main` para releases, `develop` para integração, `feature/*` para novas features, `hotfix/*` para correções.
3. Commits semânticos recomendados: `feat:`, `fix:`, `chore:`, `docs:`, `refactor:`.
4. Para teste local basta abrir `index.html` no navegador (é uma SPA estática). Para deploy no GitHub Pages, a branch `gh-pages` pode ser usada.

## Acessibilidade (WCAG 2.1 AA)
- Navegação por teclado em menu e formulários.
- Estrutura semântica com roles e aria-*
- Contraste mínimo e opção de alto contraste
- Modo escuro (prefers-color-scheme + toggle)
- Elementos com foco visível e mensagens aria-live para feedbacks.

## Otimização para produção
Incluí arquivos minificados (`.min.css`, `.min.js`). Para compressão de imagens e build automatizado, recomendamos configurar GitHub Actions (exemplo incluído).

## Documentos auxiliares
- `CONTRIBUTING.md` — orientações sobre GitFlow, commits e PRs.
- `RELEASES.md` — versão semântica e como gerar releases.
- `.github/` — templates de issues e pull requests.

---
Se preferir, posso preparar instruções passo-a-passo para gerar o histórico de commits semântico e exemplos de PRs, ou criar um repositório público no GitHub (se você me der autorização e um nome de repositório).
