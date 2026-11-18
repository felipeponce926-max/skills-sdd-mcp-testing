# skills-sdd-mcp-testing

Repertorio de Skills para Arquitectura SDD, Construcción de Servidores MCP (Python FastMCP / TypeScript), Testing E2E con Playwright y Co-Autoría de Especificaciones.

## Skills Incluidas (3)

| Skill (`SKILL.md`) | Descripción y Disparador | Comando Upstream (`npx skills`) |
| :--- | :--- | :--- |
| `mcp-builder` | Step-by-step guide for designing, building, and testing Model Context Protocol (MCP) servers in Python (FastMCP) or TypeScript (@modelcontextprotocol/sdk). | `npx skills add anthropics/skills --skill mcp-builder` |
| `webapp-testing` | Toolkit for interacting with and testing local web applications using Python Playwright: verify UI behavior, capture screenshots, and inspect browser console logs. | `npx skills add anthropics/skills --skill webapp-testing` |
| `doc-coauthoring` | Guide users through a structured three-stage workflow for co-authoring technical specs, RFCs, PRDs, proposals, and decision documents. | `npx skills add anthropics/skills --skill doc-coauthoring` |

## Cómo usar este repositorio en Cursor AI y Gemini CLI

1. **Instalación directa desde tu repositorio en cualquier proyecto nuevo:**
   ```bash
   npx skills add felipeponce926-max/skills-sdd-mcp-testing --all
   ```
2. **Instalación global en tu equipo (disponible en todos tus proyectos de Cursor):**
   ```bash
   npx skills add -g felipeponce926-max/skills-sdd-mcp-testing --all
   ```
3. **Estructura incluida:**
   - `skills/<skill>/SKILL.md`: Estructura estándar para distribución con `npx skills` y `gemini skills install`.
   - `.agents/skills/<skill>/SKILL.md` y `.cursor/skills/<skill>/SKILL.md`: Detección inmediata al abrir el repositorio en Cursor AI o Antigravity/Gemini CLI.
