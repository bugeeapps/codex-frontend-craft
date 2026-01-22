# Codex Frontend Craft

## Resumo (pt-BR)
Super skill de design system para front-end no GPT-5 Codex. Criei este projeto para orientar a criacao de interfaces com direcao visual clara, tipografia expressiva, layout intencional e execucao de alto nivel.

## Descricao
Projeto que define regras, criterios e fluxo de trabalho para gerar UI/UX de qualidade, evitando resultados genericos.

## O que inclui
- `skill.yaml` com metadados da skill
- `system.md` com o guia principal de design

## Instalacao passo a passo (pt-BR)
1. Baixe o projeto (zip) ou clone o repositorio.
2. Localize a pasta de skills do Codex (`$CODEX_HOME/skills`). Padrao:
   - Windows: `%USERPROFILE%\\.codex\\skills`
   - macOS/Linux: `~/.codex/skills`
3. Copie a pasta do projeto para `.../skills/codex-frontend-craft`.
4. Verifique se `skill.yaml` e `system.md` estao dentro dessa pasta.

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
3. Descreva o que voce precisa (tipo de tela, publico, stack, restricoes).

## Using in Codex CLI (EN)
1. Open Codex CLI.
2. Activate the skill by name `codex-frontend-craft` (e.g. in the prompt "Use the codex-frontend-craft skill to ...").
3. Describe your UI requirements (page type, audience, stack, constraints).

## Links
- Repositorio: https://github.com/bugeeapps/codex-frontend-craft
- Versao v2 (com comandos e anti-padroes): https://github.com/bugeeapps/codex-frontend-craft-v2
