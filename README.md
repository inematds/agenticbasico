# Agentic AI — Curso + Sistema

Curso rápido e visual sobre **agentes de IA agentic** + sistema para criar e rodar **vários agentes em paralelo** direto no navegador.

🌐 **Online:** https://inematds.github.io/agenticbasico/v2/

## Conteúdo

- **v1 — Landing visual rápida** (`/index.html`): 5 pilares + demo do bot imobiliário + receita de 6 passos. ~15 min.
- **v2 — Hub completo** (`/v2/index.html`):
  - **Curso INEMA** (`/v2/curso/`) — 3 trilhas (Anatomia, Construção, Operação), 9 módulos, light/dark mode.
  - **Sistema Arena** (`/v2/sistema.html`) — CRUD de agentes + arena multi-agente (2-4 em paralelo) + modo orquestração.

## Os 5 pilares de um agente

1. 📝 **Instruções** — system prompt, tom, regras
2. 📚 **Conhecimento** — FAQs, sites, CSVs
3. 🛠️ **Ferramentas** — funções que o bot executa
4. 🎯 **Intents não resolvidos** — log do que o bot ainda não trata
5. ⚙️ **Settings** — modelo, contexto, custo, custom fields

## Stack

HTML + Tailwind CDN + JS vanilla. Tudo client-side, dados em localStorage.

## Referências de arquitetura

Diagramas e conceitos de arquitetura agêntica usados como referência:

- **AIOS — LLM Agent Operating System** (AGI Research / Rutgers)
  - Repo: https://github.com/agiresearch/AIOS
  - SDK Cerebrum: https://github.com/agiresearch/Cerebrum
  - Paper: https://arxiv.org/abs/2403.16971

<!-- inema-backlink:v1 -->
## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/121-agentic-basico/)
- [Guia: como aprender inteligência artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)
<!-- /inema-backlink:v1 -->
