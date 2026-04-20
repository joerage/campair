<!-- l10n-sync: source-file="README.md" -->
🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎯 Soc Ops

**Um jogo de Bingo Social — e o workshop onde você vai construí-lo com agentes de IA.**

[![Python](https://img.shields.io/badge/Python-3.13+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-latest-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![HTMX](https://img.shields.io/badge/HTMX-powered-3D72D7)](https://htmx.org/)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-Agent%20Mode-24292e?logo=github&logoColor=white)](https://github.com/features/copilot)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[📚 Guia do Lab](https://copilot-dev-days.github.io/agent-lab-python/docs/) · [🚀 Início Rápido](#-início-rápido) · [🗺️ Visão Geral do Workshop](#️-visão-geral-do-workshop)

</div>

---

## 🎮 O que é Soc Ops?

Soc Ops é um **jogo de Bingo Social** para encontros presenciais — encontre pessoas que correspondam às perguntas no seu cartão e consiga 5 em linha para ganhar!

Mas é muito mais do que um jogo. É a **plataforma de aprendizado** deste workshop prático. Você usará o Agent Mode do VS Code com GitHub Copilot para transformar um app FastAPI funcional, mas simples, em algo verdadeiramente incrível — praticando os mesmos fluxos de trabalho agênticos usados por desenvolvedores profissionais.

```
Jogador entra → Recebe um cartão de bingo 5×5 único → Encontra pessoas que correspondam → Primeiro a fazer BINGO ganha!
```

---

## ✨ O que Você Vai Construir

Ao final deste workshop você terá entregue:

- 🎨 **Uma UI redesenhada** — criada por meio de iteração de design assistida por IA, não templates padrão
- 🧩 **Um tema de quiz personalizado** — suas próprias perguntas geradas por um agente especializado
- 🕹️ **Novos modos de jogo** — Caça ao Tesouro e Embaralhar Cartas, construídos com test-first
- ⚙️ **Uma base de código bem configurada** — com context engineering que torna a IA genuinamente útil

---

## 🧠 O que Você Vai Aprender

| Habilidade | Descrição |
|------------|-----------|
| **Context Engineering** | Escreva instruções de workspace que fazem a IA entender sua base de código |
| **Primitivos Agênticos** | Use sessões CLI, agentes na nuvem e fluxos de trabalho de agentes personalizados |
| **Desenvolvimento Design-First** | Guie a IA em iteração criativa de UI em direção a uma visão real |
| **Desenvolvimento Orientado a Testes** | Construa funcionalidades com confiança usando fluxos de trabalho TDD com agentes |

---

## 🗺️ Visão Geral do Workshop

> ⏱️ **Tempo total:** ~1 hora &nbsp;·&nbsp; **Nível:** Intermediário &nbsp;·&nbsp; **Stack:** Python · FastAPI · Jinja2 · HTMX

| Parte | Título | Tempo | O que acontece |
|-------|--------|-------|----------------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Visão Geral & Lista de Verificação | — | Verifique sua configuração e entenda o plano |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto | 15 min | Ensine a IA sobre seu projeto com instruções de workspace |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Frontend Design-First | 15 min | Redesenhe toda a UI com iteração de design agêntica |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min | Gere um tema de quiz personalizado usando seu próprio agente |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agente | 20 min | Adicione novos recursos ao jogo usando TDD + agentes de design em conjunto |

> 📝 Os guias do lab também estão disponíveis na pasta [`workshop/`](workshop/) para leitura offline.

---

## ✅ Pré-requisitos

- **VS Code v1.107+** (sem atualizações pendentes)
- **GitHub Copilot** — Free, Pro, Business ou Enterprise
  > ⚠️ Usuários do plano gratuito: Cloud Agents não estão disponíveis nos planos gratuitos. Instruções alternativas são fornecidas ao longo do workshop.
- **Git**, **Python 3.13+** e **[uv](https://docs.astral.sh/uv/)**
- Painel de Chat aberto e Agent Mode pronto

> 💡 Use o **DevContainer** para um ambiente sem configuração — sem instalações locais necessárias!

---

## 🚀 Início Rápido

```bash
# 1. Crie seu próprio repositório a partir deste template (botão acima ↑)

# 2a. Local — clone e abra no VS Code
git clone https://github.com/SEU-USUARIO/soc-ops
code soc-ops

# 2b. Cloud — abra no Codespaces
# Code → Codespaces → Criar codespace no main
```

Então abra o painel de Chat do VS Code e execute `/setup` para configurar seu ambiente.

➡️ Continue em **[Parte 00: Visão Geral & Lista de Verificação](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview)** para começar.

---

<div align="center">

Feito com ☕ e GitHub Copilot &nbsp;·&nbsp; [Contribuindo](CONTRIBUTING.md) &nbsp;·&nbsp; [Código de Conduta](CODE_OF_CONDUCT.md)

</div>
