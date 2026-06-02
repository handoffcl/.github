<div align="center">
  <img src="logo.png" width="80" alt="Handoff" />
  <h1>Handoff</h1>
  <p><strong>Chat multi-modelo con contexto completo. Cambia de modelo a mitad de la conversación sin perder nada.</strong></p>

  [![Web App](https://img.shields.io/badge/Web-handoff.cl-6366f1?style=flat-square)](https://handoff.cl)
  [![VS Code](https://img.shields.io/badge/VS_Code-Extensi%C3%B3n-blue?style=flat-square&logo=visualstudiocode)](https://github.com/handoffcl/handoff-extension/releases/latest)
  [![Handoff Coder](https://img.shields.io/badge/Handoff_Coder-Open_Source-green?style=flat-square)](https://github.com/handoffcl/handoff-coder)
  [![MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](https://github.com/handoffcl/handoff-coder/blob/main/LICENSE)
</div>

---

## ¿Qué es Handoff?

**Handoff** te permite chatear con Claude, GPT, Gemini, Mistral, DeepSeek, Groq y más — cambiando de modelo en cualquier mensaje sin perder el historial. **BYOK**: tus API keys, tus datos, sin intermediarios.

- 🌐 **[handoff.cl](https://handoff.cl)** — Chat multi-LLM en producción. Cambia de modelo mid-conversación, comparte threads, contexto persistente.
- 🔌 **[Extensión VS Code](https://github.com/handoffcl/handoff-extension)** — El mismo chat dentro de tu editor, con acceso a filesystem, git y terminal.
- 🧠 **[Handoff Coder](https://github.com/handoffcl/handoff-coder)** — Modelfiles open source que convierten cualquier LLM en un ingeniero senior con metodología propia.

---

## Repositorios

| Repo | Descripción |
|------|-------------|
| [handoff-coder](https://github.com/handoffcl/handoff-coder) | Modelfiles open source para Ollama y Groq — convierten cualquier LLM de código en un ingeniero senior con protocolo propio (spec-first, full-flow, mini-flow) |
| [handoff-extension](https://github.com/handoffcl/handoff-extension) | Extensión VS Code — el chat de Handoff dentro del editor con herramientas de filesystem, git y terminal |
| [handoff-blueprint](https://github.com/handoffcl/handoff-blueprint) | Blueprint para proyectos con IA diseñado para la extensión VS Code — estructura de docs, harness de contexto y slash commands |
| [handoff-open-blueprint](https://github.com/handoffcl/handoff-open-blueprint) | Blueprint agnóstico — funciona con Claude, GPT, Gemini, Copilot, Cursor o cualquier agente con ≥ 128k contexto. Sin extensión requerida. MIT |
| [ai-app-blueprint](https://github.com/handoffcl/ai-app-blueprint) | Blueprint específico para Claude Code — estructura completa para construir apps con IA desde cero |

---

## Handoff Coder — Open Source

Un Modelfile que transforma un LLM genérico en un ingeniero de software con criterio.

```
Protocolo de trabajo:

directo    → responde de inmediato
contextual → lee contexto, responde
mini-flow  → propón en 1 línea, espera ok
full-flow  → analiza → propón → espera aprobación → implementa → verifica
```

Modelos disponibles: **Scout** (Llama 4, Groq), **Fast** (Llama 4, Groq), **Think** (Qwen3 32B, Groq), **Standard** (GPT-OSS 120B, Groq), **Pro** (Qwen3-Coder 480B, Novita).

El Modelfile es público. Úsalo, mejóralo, contribuye.

---

<details>
<summary>🌐 English</summary>

**Handoff** lets you chat with Claude, GPT, Gemini, Mistral, DeepSeek, Groq and more — switching models mid-conversation without losing context. BYOK — your API keys, your data, no middlemen.

**Handoff Coder** is an open source Modelfile collection that turns any LLM into a software engineer with methodology: spec before code, proportional workflow, explicit approval for risky actions.

**Handoff Open Blueprint** is a model-agnostic development blueprint. Works with any AI agent (Claude, GPT, Gemini, Copilot, Cursor) with ≥ 128k context. No extension required. MIT.

</details>

---

<div align="center">
  <a href="https://handoff.cl">handoff.cl</a> ·
  <a href="https://handoff.cl/handoff-coder">Handoff Coder</a> ·
  <a href="https://handoff.cl/roadmap">Roadmap</a> ·
  <a href="https://handoff.cl/vscode">VS Code</a>
</div>
