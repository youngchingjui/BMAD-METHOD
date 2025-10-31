# BMad CORE + BMad Method

[![Version](https://img.shields.io/npm/v/bmad-method?color=blue&label=version)](https://www.npmjs.com/package/bmad-method)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D20.0.0-brightgreen)](https://nodejs.org)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da?logo=discord&logoColor=white)](https://discord.gg/gk8jAdXWmj)

> **🚨 ALPHA VERSION DOCUMENTATION**
>
> - **Install v6 Alpha:** `npx bmad-method@alpha install`
> - **Install stable v4:** `npx bmad-method install`
> - **[View v4 documentation](https://github.com/bmad-code-org/BMAD-METHOD/tree/V4)**

## Universal Human-AI Collaboration Platform

BMad-CORE (**C**ollaboration **O**ptimized **R**eflection **E**ngine) amplifies human potential through specialized AI agents. Unlike tools that replace thinking, BMad-CORE guides reflective workflows that bring out your best ideas and AI's full capabilities.

**🎯 Human Amplification** • **🎨 Domain Agnostic** • **⚡ Agent-Powered**

## Table of Contents

- [Quick Start](#quick-start)
- [What is BMad-CORE?](#what-is-bmad-core)
- [What is the BMAD Method?](#what-is-the-bmad-method)
- [Use BMAD in ChatGPT (copy/paste prompts)](#use-bmad-in-chatgpt-copypaste-prompts)
- [Modules](#modules)
  - [BMad Method (BMM)](#bmad-method-bmm---agile-ai-development)
  - [BMad Builder (BMB)](#bmad-builder-bmb---create-custom-solutions)
  - [Creative Intelligence Suite (CIS)](#creative-intelligence-suite-cis---innovation--creativity)
- [Installation](#installation)
- [Key Features](#key-features)
- [Documentation](#documentation)
- [Community & Support](#community--support)

## Quick Start

- **New to v6?** [→ BMad Method V6 Quick Start Guide](./docs/BMad-Method-V6-Quick-Start.md)
- **Upgrading?** [→ v4 to v6 Upgrade Guide](./docs/v4-to-v6-upgrade.md)

## What is BMad-CORE?

Foundation framework powering all BMad modules:

- **Agent Orchestration** - Specialized AI personas with unique capabilities
- **Workflow Engine** - Guided multi-step processes
- **Modular Architecture** - Domain-specific extensions
- **IDE Integration** - Works across development environments
- **Update-Safe Customization** - Persistent configuration through updates

### v6 Core Enhancements

- **🎨 Agent Customization** - Modify names, roles, personalities via `bmad/_cfg/agents/`
- **🌐 Multi-Language** - Independent language settings for communication and output
- **👤 Personalization** - Agents adapt to your name, technical level, preferences
- **🔄 Persistent Config** - Customizations survive all updates
- **⚙️ Flexible Settings** - Module or global configuration options

### C.O.R.E. Philosophy

- **C**ollaboration: Human-AI partnership leveraging unique strengths
- **O**ptimized: Refined processes for maximum effectiveness
- **R**eflection: Guided thinking unlocking better solutions
- **E**ngine: Framework orchestrating specialized agents and workflows

BMad-CORE helps you **discover better solutions** through strategic questioning and structured thinking.

## What is the BMAD Method?

BMAD stands for the "Breakthrough Method of Agile AI‑driven Development." It is a pragmatic, scale‑adaptive way to build software and games with AI as a thinking partner rather than an auto‑pilot.

- **Origins**: BMAD grew out of hands-on work with agile delivery, design thinking, and lean product practices, combined with thousands of real-world AI sessions. Earlier versions (v4) used tasks/templates; v6 refactors the method around BMad‑CORE with agents and workflows.
- **Structure**: The BMAD Method is implemented as the BMM module on top of the CORE engine. You work with specialized agents (PM, Analyst, Architect, SM, DEV, UX) through guided workflows across four phases: Analysis → Planning → Solutioning → Implementation.
- **Scale-Adaptive**: The method adapts to project size (Levels 0–4), from single-file fixes to enterprise systems.

If you want the "how it feels" overview, start with the [BMad Method V6 Quick Start](./docs/BMad-Method-V6-Quick-Start.md).

## Use BMAD in ChatGPT (copy/paste prompts)

You can use the BMAD Method directly in ChatGPT (or any LLM chat) without installing anything by loading one of the agent definitions below as your System prompt.

How to use:

1. Open one of the agent files below on GitHub.
2. Copy the contents of the `persona` section and (when present) `critical_actions` into your chat model's System prompt.
3. Start a new chat and speak naturally (e.g., "Run PRD" or "Create a story for Epic X"). The menu items listed in each file show that agent’s supported workflows.

Core BMM agents (system prompt links):

- [Analyst](./src/modules/bmm/agents/analyst.agent.yaml)
- [Product Manager (PM)](./src/modules/bmm/agents/pm.agent.yaml)
- [Architect](./src/modules/bmm/agents/architect.agent.yaml)
- [Scrum Master (SM)](./src/modules/bmm/agents/sm.agent.yaml)
- [Developer (DEV)](./src/modules/bmm/agents/dev.agent.yaml)
- [UX Designer](./src/modules/bmm/agents/ux-designer.agent.yaml)

Tips:

- Use a fresh chat for each workflow (prevents context drift and hallucinations).
- You can say commands naturally ("create architecture", "draft PRD")—the agent will map them to its workflows.
- For deeper guidance on which workflow to run when, see the [Quick Start](./docs/BMad-Method-V6-Quick-Start.md).

## Modules

### BMad Method (BMM) - Agile AI Development

AI-driven agile framework revolutionizing software and game development. Adapts from bug fixes to enterprise systems.

#### v6 Highlights

**🎯 Scale-Adaptive Workflows (Levels 0-4)**

- Automatically adjusts complexity from quick fixes to enterprise projects
- Greenfield & brownfield support with smart context engine

**🏗️ Project-Adaptive Architecture**

- Documents adapt to project type (web, mobile, embedded, game)
- Engine-specific game development (Unity, Phaser, Godot, Unreal)

**📋 Four-Phase Methodology**

1. **Analysis** - Brainstorming, research, briefs
2. **Planning** - Scale-adaptive PRD/GDD
3. **Solutioning** - Architecture and tech specs
4. **Implementation** - Stories, development, review

**Specialized Agents**: PM, Analyst, Architect, Scrum Master, Developer, Game Designer/Developer/Architect, UX, Test Architect

**Documentation**: [📚 BMM Module](./src/modules/bmm/README.md) | [📖 Workflows Guide](./src/modules/bmm/workflows/README.md)

### BMad Builder (BMB) - Create Custom Solutions

Build custom agents, workflows, and modules using BMad-CORE framework.

- **Agent Creation** - Custom roles and behaviors
- **Workflow Design** - Structured multi-step processes
- **Module Development** - Complete domain solutions
- **Three Agent Types** - Full module, hybrid, standalone

**Documentation**:

- [📚 BMB Module](./src/modules/bmb/README.md) - Complete module reference
- [🎯 Create Agent](./src/modules/bmb/workflows/create-agent/README.md) - Agent builder workflow
- [📋 Create Workflow](./src/modules/bmb/workflows/create-workflow/README.md) - Workflow designer
- [📦 Create Module](./src/modules/bmb/workflows/create-module/README.md) - Module scaffolding

### Creative Intelligence Suite (CIS) - Innovation & Creativity

AI-powered creative facilitation across five domains.

- **5 Interactive Workflows** - Brainstorming, Design Thinking, Problem Solving, Innovation Strategy, Storytelling
- **150+ Creative Techniques** - Proven frameworks and methodologies
- **5 Specialized Agents** - Unique personas and facilitation styles
- **Shared Resource** - Powers creative workflows in other modules

**Documentation**: [📚 CIS Module](./src/modules/cis/README.md) | [📖 CIS Workflows](./src/modules/cis/workflows/README.md)

## Installation

**Prerequisites**: Node.js v20+ ([Download](https://nodejs.org))

```bash
# Install v6 Alpha
npx bmad-method@alpha install

# Install stable v4
npx bmad-method install
```

Interactive installer guides you through:

1. **Project location** - Installation directory
2. **Module selection** - BMM, BMB, CIS
3. **Configuration** - Name, language, game dev options
4. **IDE integration** - Environment setup

### Project Structure

```
your-project/
└── bmad/
    ├── core/         # Core framework
    ├── bmm/          # BMad Method
    ├── bmb/          # BMad Builder
    ├── cis/          # Creative Intelligence
    └── _cfg/         # Your customizations
        └── agents/   # Agent configs
```

### Getting Started

After installation, activate Analyst agent and run:

```
/workflow-init
```

This initializes the workflow system and helps choose your starting point.

## Key Features

### 🎨 Update-Safe Customization

- Agent modification via `bmad/_cfg/agents/`
- Persistent settings through updates
- Multi-language support
- Flexible configuration

### 🚀 Intelligent Installation

- Auto-detects v4 installations
- Configures IDE integrations
- Resolves dependencies
- Creates unified manifests

### 📁 Unified Architecture

Single `bmad/` folder - clean, organized, maintainable.

## Documentation

- **[📚 Documentation Index](./docs/index.md)** - Complete documentation map
- **[v4 to v6 Upgrade Guide](./docs/v4-to-v6-upgrade.md)** - Migration instructions
- **[CLI Tool Guide](./tools/cli/README.md)** - Installer reference
- **[Contributing Guide](./CONTRIBUTING.md)** - Contribution guidelines

## Community & Support

- 💬 **[Discord](https://discord.gg/gk8jAdXWmj)** - Community help
- 🐛 **[Issues](https://github.com/bmad-code-org/BMAD-METHOD/issues)** - Bug reports
- 🎥 **[YouTube](https://www.youtube.com/@BMadCode)** - Tutorials
- ⭐ **[Star this repo](https://github.com/bmad-code-org/BMAD-METHOD)** - Updates

## Contributing

See **[CONTRIBUTING.md](CONTRIBUTING.md)** for guidelines.

## License

MIT License - See [LICENSE](LICENSE)

**Trademark**: BMAD™ and BMAD-METHOD™ are trademarks of BMad Code, LLC.

---

[![Contributors](https://contrib.rocks/image?repo=bmad-code-org/BMAD-METHOD)](https://github.com/bmad-code-org/BMAD-METHOD/graphs/contributors)

<sub>Built with ❤️ for the human-AI collaboration community</sub>
