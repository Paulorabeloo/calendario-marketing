# Calendário de Marketing

Calendário de planejamento e acompanhamento de postagens e campanhas. Single-file HTML, sem backend, sem dependências, sem build.

## Funcionalidades

- **Visões**: calendário mensal e lista
- **Status**: Ideia, Agendado, Publicado (com sinal visual de Atrasado quando data passou)
- **Cores personalizadas por post** (8 swatches + seletor custom)
- **Marcar como concluído** com 1 clique (toggle ✓)
- **Filtros** por plataforma e status
- **Persistência** local (localStorage) — nada vai pra servidor
- **Importar / Exportar** JSON
- **Atalhos**: `N` novo post · `Esc` fecha modal · clique em dia vazio cria post

## Como usar

1. Abra `index.html` no navegador. Só isso.
2. Ou hospede em qualquer estático: GitHub Pages, Vercel, Netlify, Cloudflare Pages, etc.

## Deploy

### Vercel
```bash
vercel deploy --prod
```

### GitHub Pages
Ative em Settings → Pages → Branch `main` → `/root` → Save.

## Stack

HTML + CSS + JavaScript vanilla. Sem build, sem npm.

## Privacidade

Tudo roda no navegador. Os posts ficam só no `localStorage` do usuário. Nenhum dado sai da máquina.
