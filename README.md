# Codex Frontend Craft

## Resumo (pt-BR)
Super skill de design system para front-end no GPT-5 Codex. Criei este projeto para orientar a criação de interfaces com direção visual clara, tipografia expressiva, layout intencional e execução de alto nível.

## Descrição
Projeto que define regras, critérios e fluxo de trabalho para gerar UI/UX de qualidade, evitando resultados genéricos.

## O que inclui
- `skill.yaml` com metadados da skill
- `system.md` com o guia principal de design

## Instalação passo a passo (pt-BR)
1. Baixe o projeto (zip) ou clone o repositório.
2. Localize a pasta de skills do Codex (`$CODEX_HOME/skills`). Padrão:
   - Windows: `%USERPROFILE%\\.codex\\skills`
   - macOS/Linux: `~/.codex/skills`
3. Copie a pasta do projeto para `.../skills/codex-frontend-craft`.
4. Verifique se `skill.yaml` e `system.md` estão dentro dessa pasta.

Exemplos:
```bash
mkdir -p "$HOME/.codex/skills"
git clone https://github.com/bugeeapps/codex-frontend-craft.git "$HOME/.codex/skills/codex-frontend-craft"
```

```powershell
$skills = Join-Path $env:USERPROFILE ".codex\\skills"
New-Item -ItemType Directory -Force -Path $skills | Out-Null
git clone https://github.com/bugeeapps/codex-frontend-craft.git (Join-Path $skills "codex-frontend-craft")
```

## Step-by-step installation (EN)
1. Download the project (zip) or clone the repo.
2. Find your Codex skills folder (`$CODEX_HOME/skills`). Defaults:
   - Windows: `%USERPROFILE%\\.codex\\skills`
   - macOS/Linux: `~/.codex/skills`
3. Copy the project folder to `.../skills/codex-frontend-craft`.
4. Make sure `skill.yaml` and `system.md` are inside that folder.

Examples:
```bash
mkdir -p "$HOME/.codex/skills"
git clone https://github.com/bugeeapps/codex-frontend-craft.git "$HOME/.codex/skills/codex-frontend-craft"
```

```powershell
$skills = Join-Path $env:USERPROFILE ".codex\\skills"
New-Item -ItemType Directory -Force -Path $skills | Out-Null
git clone https://github.com/bugeeapps/codex-frontend-craft.git (Join-Path $skills "codex-frontend-craft")
```

## Uso no Codex CLI (pt-BR)
1. Abra o Codex CLI.
2. Ative a skill pelo nome `codex-frontend-craft` (ex.: no prompt "Use a skill codex-frontend-craft para ...").
3. Descreva o que você precisa (tipo de tela, público, stack, restrições).

## Using in Codex CLI (EN)
1. Open Codex CLI.
2. Activate the skill by name `codex-frontend-craft` (e.g. in the prompt "Use the codex-frontend-craft skill to ...").
3. Describe your UI requirements (page type, audience, stack, constraints).

## Exemplos de prompts (pt-BR)
- "Use a skill codex-frontend-craft para criar uma landing page de café com estilo editorial e tipografia expressiva."
- "Crie um dashboard de vendas com layout assimétrico e micro-interações, mantendo o HTML simples."
- "Melhore o visual de um formulário SaaS sem alterar a lógica, priorizando Tailwind."

Exemplo completo de invocação:
```text
Use codex-frontend-craft.

Modo: craft:explore -> craft:proposal -> craft:build

Contexto do produto:
Página de dashboard financeiro para founders,
usada à noite, ambiente escuro, foco em decisões rápidas.

Stack:
React + Tailwind
Não mudar lógica nem dados.

Objetivo:
Refinar visual, tipografia, espaçamento e hierarquia.
Eliminar aparência genérica.
```

## Example prompts (EN)
- "Use the codex-frontend-craft skill to design a retro-futuristic product page with bold typography."
- "Create a pricing page UI with a strong visual concept and unique layout."
- "Improve the UI hierarchy of a React admin screen without changing business logic."

## Links
- Repositório: https://github.com/bugeeapps/codex-frontend-craft
- Versão v2 (com comandos e anti-padrões): https://github.com/bugeeapps/codex-frontend-craft-v2

## Parâmetros da skill (pt-BR)
- name: `codex-frontend-craft` (nome da skill no Codex CLI)
- description: "Production-grade frontend with extreme design intentionality." (resumo do foco)
- scope: `frontend`, `react`, `tailwind` (contextos onde aplica)
- poder de fogo: pipeline técnico de direção visual + heurísticas de design system (escala tipográfica, hierarquia, grid, espaçamento, tokens semânticos, paleta, estados, acessibilidade, motion e responsividade) com foco em UI de produção

## Skill parameters (EN)
- name: `codex-frontend-craft` (skill name in Codex CLI)
- description: "Production-grade frontend with extreme design intentionality." (focus summary)
- scope: `frontend`, `react`, `tailwind` (where it applies)
- power level: technical pipeline for visual direction + design-system heuristics (type scale, hierarchy, grid, spacing, semantic tokens, palette, states, accessibility, motion, responsiveness) aimed at production UI
