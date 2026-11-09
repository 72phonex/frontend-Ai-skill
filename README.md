# Frontend AI

**Frontend AI** is a framework-agnostic agent skill for designing and building polished websites and product interfaces from the user's requirements. It adapts established design and agent-workflow ideas to this project's frontend goals.

Use it for AI product sites, SaaS pages, web apps, dashboards, responsive components, and standalone HTML. It helps an AI understand the brief, choose a fitting visual direction, build real interactions, and verify the result. Optional playbooks cover visual direction, scroll storytelling, and design exploration.

The repository does not bundle upstream code or assets.

## Install from a terminal

The skill has no runtime dependencies. Choose the folder for your agent and operating system. These commands install it for your current user.

### Windows PowerShell

```powershell
# GitHub Copilot in VS Code
git clone https://github.com/72phonex/frontend-Ai-skill.git "$HOME\.copilot\skills\frontend-ai"

# Claude Code
git clone https://github.com/72phonex/frontend-Ai-skill.git "$HOME\.claude\skills\frontend-ai"

# OpenAI Codex CLI and ChatGPT desktop
git clone https://github.com/72phonex/frontend-Ai-skill.git "$HOME\.agents\skills\frontend-ai"

# Cursor
git clone https://github.com/72phonex/frontend-Ai-skill.git "$HOME\.cursor\skills\frontend-ai"
```

Run **one** command for the agent you use. Restart or reload that agent if it does not discover the skill.

### macOS or Linux

Choose the command for your agent:

```sh
# GitHub Copilot in VS Code
git clone https://github.com/72phonex/frontend-Ai-skill.git ~/.copilot/skills/frontend-ai

# Claude Code
git clone https://github.com/72phonex/frontend-Ai-skill.git ~/.claude/skills/frontend-ai

# OpenAI Codex CLI and ChatGPT desktop
git clone https://github.com/72phonex/frontend-Ai-skill.git ~/.agents/skills/frontend-ai

# Cursor
git clone https://github.com/72phonex/frontend-Ai-skill.git ~/.cursor/skills/frontend-ai
```

## Install in an IDE or a project

### VS Code with GitHub Copilot

- **Personal install:** use the Windows, macOS, or Linux terminal command above for `~/.copilot/skills/frontend-ai`.
- **Current project only:** download this repository as a ZIP and copy its contents into `<project>/.github/skills/frontend-ai/`. Keep `SKILL.md` directly inside `frontend-ai`.
- **From the UI:** open the Command Palette, run **Chat: Open Customizations**, choose **Skills**, then use **Browse** to find and install the skill if its GitHub source is available in your configured marketplace.
- Start a new Copilot chat and look for `/frontend-ai` in the skill menu.

### Cursor

Use the terminal command for `~/.cursor/skills/frontend-ai` to install for your user. For one project, copy the skill folder to `<project>/.cursor/skills/frontend-ai/` or `<project>/.agents/skills/frontend-ai/`. Cursor discovers Agent Skills from these locations.

### Claude Code

Use the terminal command for `~/.claude/skills/frontend-ai` to install for your user. For one project, copy the skill folder to `<project>/.claude/skills/frontend-ai/`. Start a new Claude Code session and invoke `/frontend-ai` or ask for a matching frontend task.

### Codex CLI or IDE extension

Use the terminal command for `~/.agents/skills/frontend-ai` to install for your user. For one project, copy the skill folder to `<project>/.agents/skills/frontend-ai/`. Restart Codex if needed, then invoke `$frontend-ai` or select it from the available skills.

## Use in AI websites and apps

### Claude.ai website

1. Download this repository as a ZIP from GitHub and extract it.
2. Rename the extracted `frontend-Ai-skill-main` folder to `frontend-ai`, then ZIP that folder so `frontend-ai/SKILL.md` is at the archive root level.
3. Keep the accompanying `frontend-ai/skills/` playbooks in the ZIP.
4. In Claude, open **Customize → Skills** and upload the ZIP. Enable the skill after upload.

Availability of custom skills depends on your Claude account and workspace plan/settings.

### ChatGPT desktop app

Install the skill into `~/.agents/skills/frontend-ai` using the terminal command above. Open **Skills** in the ChatGPT desktop app and check that the skill is available. If it is not shown, verify the app's Codex/IDE skill support and restart it.

### ChatGPT website

A standalone skill folder cannot currently be installed directly into ChatGPT on the web. OpenAI supports skills in web Chat and Work when they are distributed through a plugin. This repository does not yet include a ChatGPT plugin package. To use the instructions manually, open [SKILL.md](SKILL.md) and paste its relevant guidance into your conversation.

Other AI websites may accept instructions or knowledge uploads, but each service has its own format; check that service's current documentation. Do not assume that uploading a repository ZIP automatically installs a skill.

## Verify the install

Start a new session and ask the agent to build or improve a frontend from a short brief. In VS Code, confirm `/frontend-ai` appears in the skill menu; in Claude Code use `/frontend-ai`; in Codex use `$frontend-ai`. If it is missing, check the install path, make sure `SKILL.md` is directly inside the `frontend-ai` folder, and restart the agent.

## References

- [Agent Skills open standard](https://agentskills.io/)
- [VS Code Agent Skills](https://code.visualstudio.com/docs/agent-customization/agent-skills)
- [Claude Code skills](https://code.claude.com/docs/en/skills)
- [Claude custom skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)
- [OpenAI skills for ChatGPT and Codex](https://learn.chatgpt.com/docs/build-skills)
- [Cursor Agent Skills](https://cursor.com/docs/skills)

## Acknowledgments

The following public MIT-licensed repositories informed the general workflows in this project:

- [nateherkai/scroll-craft](https://github.com/nateherkai/scroll-craft) — scroll-story planning, layered composition, and responsive motion.
- [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) — visual direction, hierarchy-first design, and screenshot-based review.
- [superdesigndev/superdesign-skill](https://github.com/superdesigndev/superdesign-skill) — optional design-canvas exploration and design-system workflows.

Their license declarations were checked in the upstream repositories. This project does not include upstream code or assets. If code or assets are added later, verify their current license and preserve any required notices and individual asset terms. The upstream Superdesign instructions use an unpinned `npx` package command; this project does not copy or automatically run it. Any future tool installation or hosted-service use requires user approval and a reviewed, pinned package version.
