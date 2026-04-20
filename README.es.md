<!-- l10n-sync: source-file="README.md" -->
🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎯 Soc Ops

**Un juego de Bingo Social — y el taller donde lo construirás con agentes de IA.**

[![Python](https://img.shields.io/badge/Python-3.13+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-latest-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![HTMX](https://img.shields.io/badge/HTMX-powered-3D72D7)](https://htmx.org/)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-Agent%20Mode-24292e?logo=github&logoColor=white)](https://github.com/features/copilot)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[📚 Guía del Lab](https://copilot-dev-days.github.io/agent-lab-python/docs/) · [🚀 Inicio Rápido](#-inicio-rápido) · [🗺️ Resumen del Taller](#️-resumen-del-taller)

</div>

---

## 🎮 ¿Qué es Soc Ops?

Soc Ops es un **juego de Bingo Social** para encuentros presenciales — ¡encuentra personas que coincidan con las preguntas de tu tarjeta y consigue 5 en fila para ganar!

Pero es también mucho más que un juego. Es la **plataforma de aprendizaje** de este taller práctico. Usarás el Agent Mode de VS Code con GitHub Copilot para transformar una aplicación FastAPI funcional pero sencilla en algo verdaderamente genial, practicando los mismos flujos de trabajo agénticos que usan los desarrolladores profesionales.

```
El jugador se une → Recibe una tarjeta de bingo 5×5 única → Encuentra personas que coincidan → ¡El primero en BINGO gana!
```

---

## ✨ Lo Que Construirás

Al finalizar este taller habrás creado:

- 🎨 **Una UI rediseñada** — creada mediante iteración de diseño asistida por IA, no plantillas predeterminadas
- 🧩 **Un tema de quiz personalizado** — tus propias preguntas generadas por un agente especializado
- 🕹️ **Nuevos modos de juego** — Búsqueda del Tesoro y Barajar Cartas, construidos con desarrollo test-first
- ⚙️ **Una base de código bien configurada** — con context engineering que hace que la IA sea genuinamente útil

---

## 🧠 Lo Que Aprenderás

| Habilidad | Descripción |
|-----------|-------------|
| **Context Engineering** | Escribe instrucciones de espacio de trabajo que hacen que la IA entienda tu código |
| **Primitivas Agénticas** | Usa sesiones CLI, agentes en la nube y flujos de trabajo de agentes personalizados |
| **Desarrollo Design-First** | Guía a la IA en la iteración creativa de UI hacia una visión real |
| **Desarrollo Orientado a Tests** | Construye características de forma fiable usando flujos de trabajo TDD con agentes |

---

## 🗺️ Resumen del Taller

> ⏱️ **Tiempo total:** ~1 hora &nbsp;·&nbsp; **Nivel:** Intermedio &nbsp;·&nbsp; **Stack:** Python · FastAPI · Jinja2 · HTMX

| Parte | Título | Tiempo | Qué ocurre |
|-------|--------|--------|------------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Visión General y Lista de Verificación | — | Verifica tu configuración y comprende el plan |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Configuración y Context Engineering | 15 min | Enseña a la IA sobre tu proyecto con instrucciones de espacio de trabajo |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Desarrollo Frontend Orientado al Diseño | 15 min | Rediseña toda la UI con iteración de diseño agéntica |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min | Genera un tema de quiz personalizado usando tu propio agente |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agente | 20 min | Añade nuevas características de juego usando TDD + agentes de diseño en tándem |

> 📝 Las guías del laboratorio también están disponibles en la carpeta [`workshop/`](workshop/) para lectura sin conexión.

---

## ✅ Requisitos Previos

- **VS Code v1.107+** (sin actualizaciones pendientes)
- **GitHub Copilot** — Free, Pro, Business o Enterprise
  > ⚠️ Usuarios del nivel gratuito: Los Cloud Agents no están disponibles en los planes gratuitos. Se proporcionan instrucciones alternativas a lo largo del taller.
- **Git**, **Python 3.13+** y **[uv](https://docs.astral.sh/uv/)**
- Panel de Chat abierto y Agent Mode listo

> 💡 ¡Usa el **DevContainer** para un entorno sin configuración — no se requieren instalaciones locales!

---

## 🚀 Inicio Rápido

```bash
# 1. Crea tu propio repositorio desde esta plantilla (botón de arriba ↑)

# 2a. Local — clona y abre en VS Code
git clone https://github.com/TU-USUARIO/soc-ops
code soc-ops

# 2b. Cloud — abre en Codespaces
# Code → Codespaces → Crear codespace en main
```

Luego abre el panel de Chat de VS Code y ejecuta `/setup` para configurar tu entorno.

➡️ Continúa en **[Parte 00: Visión General y Lista de Verificación](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview)** para comenzar.

---

<div align="center">

Hecho con ☕ y GitHub Copilot &nbsp;·&nbsp; [Contribuir](CONTRIBUTING.md) &nbsp;·&nbsp; [Código de Conducta](CODE_OF_CONDUCT.md)

</div>
