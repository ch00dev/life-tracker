# Cauã Life Tracker 📊

Tracker pessoal para acompanhar hábitos, horas de estudo, metas e progresso no roadmap técnico.

## Como usar

### Opção 1 — GitHub Pages (recomendado)

1. Crie um repositório no GitHub chamado `life-tracker` (ou qualquer nome)
2. Faça upload do arquivo `index.html`
3. Vá em **Settings → Pages → Source: main branch → / (root)**
4. Acesse via `https://seu-usuario.github.io/life-tracker`

### Opção 2 — Local

Abra o `index.html` diretamente no navegador. Funciona offline.

---

## Funcionalidades

- **Check-in diário** — hábitos, horas de estudo, humor, vitórias e notas
- **Visão semanal** — grid de hábitos + gráfico de horas por área
- **Metas** — progresso em percentual, dias ou sim/não
- **Stats** — mapa de atividade (30 dias), sequências, acumulado de horas
- **Exportar / Importar JSON** — backup dos dados entre dispositivos

## Dados

Os dados ficam salvos no `localStorage` do navegador. Para sincronizar entre dispositivos, use **Exportar JSON** e **Importar JSON** nas configurações.

## Stack

HTML + CSS + JS puro. Sem dependências externas além do Chart.js (CDN).
