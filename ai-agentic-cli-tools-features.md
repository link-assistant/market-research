# AI Agentic CLI Tools: Comprehensive Features Comparison

This document provides a detailed feature-by-feature comparison of AI agentic CLI tools for coding, updated as of December 2025. Use this guide to compare specific capabilities across tools and find the best fit for your development workflow.

## Table of Contents
1. [Agent Capabilities](#agent-capabilities)
2. [AI Model Support](#ai-model-support)
3. [Context & Memory](#context--memory)
4. [File & Code Operations](#file--code-operations)
5. [Version Control Integration](#version-control-integration)
6. [IDE & Editor Integration](#ide--editor-integration)
7. [Terminal & Shell Features](#terminal--shell-features)
8. [Extensibility & Customization](#extensibility--customization)
9. [Enterprise & Team Features](#enterprise--team-features)
10. [Pricing & Free Tiers](#pricing--free-tiers)
11. [Open Source & Licensing](#open-source--licensing)

---

## Agent Capabilities

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **Autonomous Task Execution** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Multi-step Planning** | Yes | Yes (ReAct) | Yes | Yes (Plan/Act) | Yes (Architect) | Yes | Yes | Yes | Yes (Spec-driven) | Yes | Yes (Plan Mode) | Yes | Yes | Yes |
| **Code Generation** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Code Refactoring** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Bug Fixing** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Test Generation** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes (PBT) | Yes | Yes | Yes | Yes | Yes |
| **Test Execution** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Command Execution** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Web Browsing** | Yes (WebFetch) | Yes | No | Yes | No | Yes | No | No | No | No | No | No | Yes | Yes |
| **Image/Screenshot Input** | Yes | Yes | Yes | No | Yes | No | No | No | No | No | Yes | No | No | No |
| **Voice Input** | No | No | No | No | Yes | No | No | No | No | No | No | No | No | No |
| **Human-in-the-loop Approval** | Yes | Yes | Yes | Yes | Yes | Yes (configurable) | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Full Autonomous Mode** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes (Dispatch) | Yes | Yes | Yes | Yes | Yes | Yes |
| **Specialized Agent Types** | No | No | No | No | No | No | No | No | Yes (Custom agents) | No | Yes (SubAgents) | Yes (Knowledge, Reliability, Product) | Yes (Modes) | No |

---

## AI Model Support

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **Claude Models** | Sonnet 4/4.5, Opus 4/4.5 | Via API | No | Yes | Yes | Yes | Yes | Claude 3.5 | Haiku 4.5 | Sonnet 4 (Bedrock) | Via API | Opus 4, Sonnet 4 | Yes | Yes |
| **OpenAI GPT Models** | Via API | No | GPT-5.2-Codex, GPT-5, o3, o4-mini | Yes | Yes | Yes | Yes | GPT-4o | No | No | Via API | GPT-5 | Yes | Yes |
| **Google Gemini Models** | Via API | Gemini 2.5 Pro, 3 Flash/Pro | No | Yes | Yes | Yes | Yes | No | No | No | No | No | Yes | No |
| **Grok Models** | Via API | No | No | Yes | Yes | Yes | No | No | No | No | No | No | Yes | No |
| **Open-Source Models** | Via API | No | No | Yes | Yes (DeepSeek, Llama, etc.) | Yes | Yes (Ollama) | No | No | No | Qwen3-Coder | No | Yes (Ollama) | Yes |
| **Local Model Support** | Via API | No | No | Yes | Yes | Yes | Yes | No | No | No | No | No | Yes | Yes |
| **BYOK (Bring Your Own Key)** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes (Build plan) | No | No | Yes | No | Yes | Yes |
| **Auto Model Selection** | No | No | No | No | No | Yes | No | Yes | Yes (Auto mode) | No | No | Yes | Yes (per mode) | No |

---

## Context & Memory

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **Max Context Window** | 200K | 1M | Varies by model | Varies | Varies | Varies | Varies | Varies | Varies | Varies | 256K-1M | Varies | Varies | Varies |
| **Automatic Context Gathering** | Yes | Yes | Yes | Yes | Yes (repo map) | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Codebase Indexing** | Yes | Yes | Yes | Yes | Yes | Yes | Yes (LSP) | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Session Memory** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Multi-session Support** | No | No | No | No | No | No | Yes | No | No | No | No | No | No | Yes |
| **Shareable Sessions** | No | No | No | No | No | No | Yes | No | No | No | No | No | No | No |
| **Project Instructions File** | CLAUDE.md | GEMINI.md | AGENTS.md | .clinerules | .aider | Various | Various | WARP.md | .kiro | .amazonq | Various | Various | Various | Various |
| **Conversation History** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **History Compaction** | Yes | Yes | Yes | Yes | Yes | Yes (/compact) | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |

---

## File & Code Operations

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **Multi-file Editing** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Diff Preview** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | No | Yes | Yes | Yes | Yes | Yes | Yes |
| **File Creation** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **File Deletion** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Directory Operations** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Pattern-based Search** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **LSP Integration** | Yes (v2.0.74+) | No | No | No | No | No | Yes | No | No | No | No | No | No | No |
| **Multi-language Support** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Linting Integration** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | No | Yes | Yes | Yes | Yes | Yes | Yes |

---

## Version Control Integration

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **Git Integration** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Auto-commit** | No | No | No | No | Yes | No | No | No | No | No | No | No | No | No |
| **Sensible Commit Messages** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **PR Creation** | Yes | Yes | Yes | Yes | No | Yes | Yes | No | Yes | Yes | Yes | Yes | Yes | Yes |
| **PR Review** | Yes | Yes | Yes | Yes | No | Yes | Yes | Yes | Yes | Yes | Yes | Yes (auto) | Yes | Yes |
| **GitHub Integration** | Yes (Actions) | Yes (Actions) | Yes (@codex) | No | No | Yes | Yes (/oc) | No | Yes | Yes | No | Yes | No | Yes |
| **Linear Integration** | No | No | Yes | No | No | Yes | No | No | No | No | No | Yes | No | Yes |
| **Jira Integration** | No | No | No | No | No | Yes | No | No | No | No | No | Yes | No | Yes |

---

## IDE & Editor Integration

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **VS Code Extension** | Yes | No | Yes | Yes | Yes | No | No | No | Yes (via Kiro IDE) | Yes | Yes | Yes | Yes | No |
| **JetBrains Extension** | Yes | No | No | Yes | No | No | No | No | Yes (via Kiro IDE) | Yes | No | Yes | No | No |
| **Neovim/Vim Support** | No | No | No | No | No | Yes | No | No | No | No | No | Yes | No | No |
| **Zed Integration** | No | No | No | No | No | Yes (ACP) | No | No | No | No | Yes | No | No | No |
| **Cursor Integration** | No | No | No | Yes | No | No | No | No | No | No | No | No | Yes | No |
| **Desktop App** | No | No | No | No | No | Yes | Yes | Yes (native) | Yes | No | No | No | No | Yes |
| **Web Interface** | Yes | No | Yes | No | Yes | No | No | No | Yes | Yes | No | Yes | No | Yes |
| **Slack Integration** | Yes | No | No | No | No | No | No | No | No | Yes | No | Yes | No | No |

---

## Terminal & Shell Features

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **Native Terminal** | CLI | CLI | CLI | No | CLI | CLI + Desktop | CLI + Desktop | Native Terminal | CLI | CLI | CLI | CLI | No | CLI + GUI |
| **Shell Completions** | Yes | Yes | Yes | N/A | Yes (bash, zsh) | Yes | Yes | Native | Yes | Yes | Yes | Yes | N/A | Yes |
| **Natural Language to Bash** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Command Execution** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Sandboxed Execution** | Yes | Yes | Yes | Yes | No | No | No | No | No | No | No | No | Yes | Yes |
| **Slash Commands** | Yes | Yes | Yes (/review, /plan) | No | Yes | Yes | No | Yes | Yes | Yes | Yes | Yes | No | Yes |
| **Bash/Zsh Support** | Yes | Yes | Yes | N/A | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | N/A | Yes |
| **Fish Shell Support** | Yes | Yes | Yes | N/A | Yes | Yes | Yes | Yes | No | Yes | Yes | Yes | N/A | Yes |
| **PowerShell Support** | Yes | Yes | Yes | N/A | Yes | Yes | Yes | Yes | No | Yes | Yes | Yes | N/A | Yes |
| **SSH Support** | Yes | Yes | Yes | N/A | Yes | Yes | Yes | Yes | No | Yes | Yes | Yes | N/A | Yes |

---

## Extensibility & Customization

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **MCP Support** | Yes | Yes | Yes | Yes | No | Yes | No | Yes | Yes | No | No | No | Yes | No |
| **Custom Tools/Skills** | Yes | Yes | Yes (agent skills) | Yes | No | Yes | No | Yes | Yes (custom agents) | No | Yes (Skills) | Yes | Yes | Yes |
| **Custom Prompts** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Plugin System** | No | No | Yes (skills) | Yes | No | Yes (extensions) | No | No | Yes | No | Yes (SubAgents) | Yes | Yes | No |
| **API Access** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | No | Yes | Yes | Yes | Yes | Yes | Yes |
| **SDK Available** | No | No | No | No | No | No | No | No | No | Yes | No | No | No | Yes (Python) |
| **Custom Modes** | No | No | No | No | Yes (Architect/Editor) | Yes | No | No | No | No | Yes (Plan Mode) | No | Yes (Custom) | No |

---

## Enterprise & Team Features

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **SSO/SAML** | No | No | No | Yes | No | No | No | Yes (Business) | Yes | Yes | No | Yes | No | Yes |
| **Audit Trails** | No | No | No | Yes | No | No | No | No | Yes | Yes | No | Yes | No | Yes |
| **Admin Controls** | No | No | No | Yes | No | No | No | Yes | Yes | Yes | No | Yes | No | Yes |
| **Private Networking** | No | No | No | Yes (VPC) | No | Yes (local) | No | No | Yes | Yes | No | Yes | No | Yes |
| **Self-hosted** | No | No | No | Yes | Yes | Yes | Yes | No | No | No | Yes | Yes | Yes | Yes |
| **SOC 2 Compliance** | No | No | No | No | No | No | No | Yes | Yes | Yes | No | Yes | No | No |
| **Zero Data Retention** | No | Yes | No | No | No | Yes | No | Yes | No | No | No | No | No | No |
| **Team Management** | No | No | No | Yes | No | No | No | Yes | Yes | Yes | No | Yes | No | Yes |

---

## Pricing & Free Tiers

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **Free Tier** | No | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Trial | Yes | Yes ($10 credit) |
| **Free Requests/Day** | 0 | 1,000 | API-based | API-based | API-based | API-based | API-based | 75-150/mo | 500 bonus | 1,000/mo | 2,000 | Trial | API-based | API-based |
| **Entry Paid Plan** | $20/mo (Pro) | $19.99/mo (AI Pro) | API pricing | API pricing | API pricing | API pricing | API pricing | $20/mo (Build) | $20/mo (Pro) | $19/mo (Pro) | API pricing | Enterprise | API pricing | API pricing |
| **Premium Plan** | $200/mo (Max) | AI Ultra | API pricing | API pricing | API pricing | API pricing | API pricing | $50/mo (Business) | $200/mo (Power) | $19/mo | API pricing | Enterprise | API pricing | API pricing |
| **API Pricing Model** | Per token | Per token | Per token | Per token | Per token | Per token | Per token | Credit-based | Credit-based | Interaction-based | Per token | Custom | Per token | Per token |
| **Startup Credits** | No | No | No | No | No | No | No | No | Yes (1 year Pro+) | No | No | No | No | No |

---

## Open Source & Licensing

| Feature | Claude Code | Gemini CLI | Codex CLI | Cline | Aider | Goose | OpenCode | Warp | Kiro CLI | Amazon Q | Qwen Code | Droid | Roo Code | OpenHands |
|---------|-------------|------------|-----------|-------|-------|-------|----------|------|----------|----------|-----------|-------|----------|-----------|
| **Open Source** | No | Yes | Yes | Yes | Yes | Yes | Yes | No | No | No | Yes | No | Yes | Yes |
| **License** | Proprietary | Apache 2.0 | Apache 2.0 | Apache 2.0 | Apache 2.0 | Apache 2.0 | MIT | Proprietary | Proprietary | Proprietary | Apache 2.0 | Proprietary | Apache 2.0 | MIT |
| **GitHub Stars** | 49K | 88.5K | 54.7K | 50K+ | ~35K | 24.8K | 41K | N/A | N/A | N/A | New | N/A | 21.4K | N/A |
| **Active Development** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Community Contributors** | N/A | Yes | Yes | Yes | Yes | Yes (450+) | Yes | N/A | N/A | N/A | Yes | N/A | Yes | Yes |
| **Foundation Membership** | No | No | AAIF | No | No | AAIF | No | No | No | AAIF | No | No | No | No |

---

## Quick Feature Summary by Use Case

### Best for Open Source Development
1. **Gemini CLI** - Largest open-source community (88.5K stars), Apache 2.0
2. **Cline** - Fastest-growing (50K+ stars), enterprise features
3. **OpenAI Codex CLI** - 54.7K stars, agent skills ecosystem

### Best for Enterprise
1. **Droid by Factory** - #1 benchmark performance, specialized agents
2. **Kiro CLI** - AWS integration, spec-driven development
3. **Warp** - SOC 2 compliance, SSO, team management

### Best for Free Usage
1. **Gemini CLI** - 1,000 free requests/day
2. **Qwen Code** - 2,000 free requests/day via OAuth
3. **Amazon Q Developer CLI** - 1,000 free interactions/month

### Best for Local/Private Execution
1. **Goose** - Fully local, part of Linux Foundation AAIF
2. **Aider** - Self-hosted, any local model
3. **OpenCode** - Multi-session, local LLM support

### Best for IDE Integration
1. **Cline** - VS Code, JetBrains, Cursor
2. **Roo Code** - Multiple modes in VS Code
3. **Claude Code** - VS Code, JetBrains, Slack

### Best for Git/GitHub Workflows
1. **Aider** - Auto-commit, sensible messages
2. **OpenAI Codex CLI** - @codex mentions in PRs/Issues
3. **OpenCode** - /oc mentions in comments

---

## Benchmark Performance (December 2025)

| Tool | Terminal-Bench Score | SWE-bench Score | Notes |
|------|---------------------|-----------------|-------|
| **Droid (Opus)** | 58.75% (#1) | N/A | Best benchmark performance |
| **Droid (Sonnet)** | 50.5% | N/A | Beats Claude Code |
| **Droid (GPT-5)** | 52.5% | N/A | Beats Codex CLI |
| **Claude Code (Opus)** | 43.2% | N/A | |
| **Codex CLI** | 42.8% | N/A | |
| **Gemini 3 Flash** | N/A | 78% | Best SWE-bench for Gemini CLI |
| **OpenHands** | N/A | 50%+ | Solves 50%+ of real GitHub issues |

---

## Model Context Protocol (MCP) Ecosystem

Tools with MCP support can integrate with a growing ecosystem of MCP servers:

| Tool | MCP Support | Custom MCP Servers | Built-in Tools |
|------|-------------|-------------------|----------------|
| **Claude Code** | Yes | Yes | WebSearch, WebFetch, MultiEdit |
| **Gemini CLI** | Yes | Yes | Google Search, file ops, shell |
| **Codex CLI** | Yes | Yes | Agent skills, slash commands |
| **Cline** | Yes | Yes | Browser, file ops |
| **Goose** | Yes | Yes | Extensible via MCP |
| **Warp** | Yes | Yes | Codebase embeddings |
| **Kiro CLI** | Yes | Yes | AWS service queries |

---

## References

- [Claude Code Docs](https://docs.claude.com/en/release-notes/claude-code)
- [Gemini CLI GitHub](https://github.com/google-gemini/gemini-cli)
- [OpenAI Codex CLI Docs](https://developers.openai.com/codex/cli/features/)
- [Cline Documentation](https://cline.bot/)
- [Aider Documentation](https://aider.chat/)
- [Goose Documentation](https://block.github.io/goose/)
- [OpenCode Documentation](https://opencode.ai/)
- [Warp AI Features](https://www.warp.dev/warp-ai)
- [Kiro CLI Documentation](https://kiro.dev/cli/)
- [Amazon Q Developer](https://aws.amazon.com/q/developer/)
- [Qwen Code Documentation](https://qwenlm.github.io/qwen-code-docs/en/)
- [Factory Droid](https://factory.ai/)
- [Roo Code Documentation](https://roocode.com/)
- [OpenHands Documentation](https://openhands.dev/)
- [Agentic AI Foundation (AAIF)](https://www.linuxfoundation.org/press/linux-foundation-announces-the-formation-of-the-agentic-ai-foundation)
- [Terminal-Bench Results](https://factory.ai/news/terminal-bench)
