# Contributing & Git workflow

## GitFlow (resumo)
- `main` — branch estável com releases numeradas (vX.Y.Z)
- `develop` — integração diária (features mergeadas aqui)
- `feature/<nome>` — ramificações para novas features; merge para `develop`
- `release/<version>` — preparar release; merge para `main` e `develop`
- `hotfix/<nome>` — correções urgentes em `main`; merge para `main` e `develop`

## Commits semânticos (exemplos)
- `feat: adicionar componente de modal acessível`
- `fix: corrigir tabindex no menu`
- `docs: atualizar README com checklist de acessibilidade`
