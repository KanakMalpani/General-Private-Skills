# General Private Skills

> **116 reusable development skills** for GitHub Copilot, organized as structured SKILL.md files.

## 🚀 Quick Start

### Option 1: Reference a skill directly in Copilot Chat

Open Copilot Chat in VS Code (`Ctrl+Shift+I`) and type:

```
Reference skills/python-patterns/SKILL.md and help me add type hints
```

```
Apply the patterns from skills/django-tdd/SKILL.md to write tests for my view
```

```
Using skills/api-design/SKILL.md, design a REST endpoint for user registration
```

### Option 2: Use the full GitHub path

```
Using KanakMalpani/General-Private-Skills/skills/python-patterns/SKILL.md patterns, improve my code
```

### Option 3: Add to your project's Copilot instructions

Copy `.github/copilot-instructions.md` into your own project to get skill guidance automatically.

---

## 📂 Repository Structure

```
.copilot/
  config.json      # All 116 skills registered (machine-readable)
  agents.yml       # Agent definitions for all skills
  skills.yml       # Skills organized by category
.github/
  copilot-instructions.md  # Copilot usage instructions
skills/
  <skill-name>/
    SKILL.md       # Skill content (frontmatter + patterns + examples)
```

---

## 🧠 How Skills Work

Each skill in `skills/<name>/SKILL.md` follows this format:

```yaml
---
name: skill-name
description: Short description of what this skill covers
origin: ECC
---
# Skill Title

## When to Activate
[triggers for using this skill]

## Core Principles
[patterns, conventions, and examples]
```

To use a skill with Copilot, **reference the skill file in your prompt**:

```
Check skills/golang-patterns/SKILL.md and refactor this code to be more idiomatic Go
```

---

## 📋 All Skills (116 total)


### 🐍 Python

| Skill | Description |
|-------|-------------|
| [`python-patterns`](skills/python-patterns/SKILL.md) | Pythonic idioms, PEP 8 standards, type hints, and best practices for building robust, effi... |
| [`python-testing`](skills/python-testing/SKILL.md) | Python testing strategies using pytest, TDD methodology, fixtures, mocking, parametrizatio... |
| [`pytorch-patterns`](skills/pytorch-patterns/SKILL.md) | PyTorch deep learning patterns and best practices for building robust, efficient, and repr... |

### 🎸 Django

| Skill | Description |
|-------|-------------|
| [`django-patterns`](skills/django-patterns/SKILL.md) | Django architecture patterns, REST API design with DRF, ORM best practices, caching, signa... |
| [`django-tdd`](skills/django-tdd/SKILL.md) | Django testing strategies with pytest-django, TDD methodology, factory_boy, mocking, cover... |
| [`django-security`](skills/django-security/SKILL.md) | Django security best practices, authentication, authorization, CSRF protection, SQL inject... |
| [`django-verification`](skills/django-verification/SKILL.md) | Verification loop for Django projects: migrations, linting, tests with coverage, security ... |

### ⚛️ Frontend / JS / TS

| Skill | Description |
|-------|-------------|
| [`frontend-patterns`](skills/frontend-patterns/SKILL.md) | Frontend development patterns for React, Next.js, state management, performance optimizati... |
| [`nextjs-turbopack`](skills/nextjs-turbopack/SKILL.md) | Next.js 16+ and Turbopack — incremental bundling, FS caching, dev speed, and when to use T... |
| [`nuxt4-patterns`](skills/nuxt4-patterns/SKILL.md) | Nuxt 4 app patterns for hydration safety, performance, route rules, lazy loading, and SSR-... |
| [`bun-runtime`](skills/bun-runtime/SKILL.md) | Bun as runtime, package manager, bundler, and test runner. When to choose Bun vs Node, mig... |
| [`coding-standards`](skills/coding-standards/SKILL.md) | Universal coding standards, best practices, and patterns for TypeScript, JavaScript, React... |
| [`frontend-slides`](skills/frontend-slides/SKILL.md) | Create stunning, animation-rich HTML presentations from scratch or by converting PowerPoin... |

### 🛠️ Backend

| Skill | Description |
|-------|-------------|
| [`backend-patterns`](skills/backend-patterns/SKILL.md) | Backend architecture patterns, API design, database optimization, and server-side best pra... |
| [`api-design`](skills/api-design/SKILL.md) | REST API design patterns including resource naming, status codes, pagination, filtering, e... |
| [`deployment-patterns`](skills/deployment-patterns/SKILL.md) | Deployment workflows, CI/CD pipeline patterns, Docker containerization, health checks, rol... |
| [`docker-patterns`](skills/docker-patterns/SKILL.md) | Docker and Docker Compose patterns for local development, container security, networking, ... |

### ☕ Java / Spring

| Skill | Description |
|-------|-------------|
| [`java-coding-standards`](skills/java-coding-standards/SKILL.md) | Java coding standards for Spring Boot services: naming, immutability, Optional usage, stre... |
| [`springboot-patterns`](skills/springboot-patterns/SKILL.md) | Spring Boot architecture patterns, REST API design, layered services, data access, caching... |
| [`springboot-tdd`](skills/springboot-tdd/SKILL.md) | Test-driven development for Spring Boot using JUnit 5, Mockito, MockMvc, Testcontainers, a... |
| [`springboot-security`](skills/springboot-security/SKILL.md) | Spring Security best practices for authn/authz, validation, CSRF, secrets, headers, rate l... |
| [`springboot-verification`](skills/springboot-verification/SKILL.md) | Verification loop for Spring Boot projects: build, static analysis, tests with coverage, s... |
| [`jpa-patterns`](skills/jpa-patterns/SKILL.md) | JPA/Hibernate patterns for entity design, relationships, query optimization, transactions,... |

### 🏗️ Kotlin / Android

| Skill | Description |
|-------|-------------|
| [`kotlin-patterns`](skills/kotlin-patterns/SKILL.md) | Idiomatic Kotlin patterns, best practices, and conventions for building robust, efficient,... |
| [`kotlin-testing`](skills/kotlin-testing/SKILL.md) | Kotlin testing patterns with Kotest, MockK, coroutine testing, property-based testing, and... |
| [`kotlin-coroutines-flows`](skills/kotlin-coroutines-flows/SKILL.md) | Kotlin Coroutines and Flow patterns for Android and KMP — structured concurrency, Flow ope... |
| [`kotlin-ktor-patterns`](skills/kotlin-ktor-patterns/SKILL.md) | Ktor server patterns including routing DSL, plugins, authentication, Koin DI, kotlinx.seri... |
| [`kotlin-exposed-patterns`](skills/kotlin-exposed-patterns/SKILL.md) | JetBrains Exposed ORM patterns including DSL queries, DAO pattern, transactions, HikariCP ... |
| [`android-clean-architecture`](skills/android-clean-architecture/SKILL.md) | Clean Architecture patterns for Android and Kotlin Multiplatform projects — module structu... |
| [`compose-multiplatform-patterns`](skills/compose-multiplatform-patterns/SKILL.md) | Compose Multiplatform and Jetpack Compose patterns for KMP projects — state management, na... |

### 🐹 Go

| Skill | Description |
|-------|-------------|
| [`golang-patterns`](skills/golang-patterns/SKILL.md) | Idiomatic Go patterns, best practices, and conventions for building robust, efficient, and... |
| [`golang-testing`](skills/golang-testing/SKILL.md) | Go testing patterns including table-driven tests, subtests, benchmarks, fuzzing, and test ... |

### 🦀 Rust

| Skill | Description |
|-------|-------------|
| [`rust-patterns`](skills/rust-patterns/SKILL.md) | Idiomatic Rust patterns, ownership, error handling, traits, concurrency, and best practice... |
| [`rust-testing`](skills/rust-testing/SKILL.md) | Rust testing patterns including unit tests, integration tests, async testing, property-bas... |

### 🍎 Swift / iOS

| Skill | Description |
|-------|-------------|
| [`swiftui-patterns`](skills/swiftui-patterns/SKILL.md) | SwiftUI architecture patterns, state management with @Observable, view composition, naviga... |
| [`swift-protocol-di-testing`](skills/swift-protocol-di-testing/SKILL.md) | Protocol-based dependency injection for testable Swift code — mock file system, network, a... |
| [`swift-actor-persistence`](skills/swift-actor-persistence/SKILL.md) | Thread-safe data persistence in Swift using actors — in-memory cache with file-backed stor... |
| [`swift-concurrency-6-2`](skills/swift-concurrency-6-2/SKILL.md) | Swift 6.2 Approachable Concurrency — single-threaded by default, @concurrent for explicit ... |
| [`foundation-models-on-device`](skills/foundation-models-on-device/SKILL.md) | Apple FoundationModels framework for on-device LLM — text generation, guided generation wi... |
| [`liquid-glass-design`](skills/liquid-glass-design/SKILL.md) | iOS 26 Liquid Glass design system — dynamic glass material with blur, reflection, and inte... |

### ⚡ C++

| Skill | Description |
|-------|-------------|
| [`cpp-coding-standards`](skills/cpp-coding-standards/SKILL.md) | C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). Use when writing... |
| [`cpp-testing`](skills/cpp-testing/SKILL.md) | Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, diagnosing ... |

### 🐪 Perl

| Skill | Description |
|-------|-------------|
| [`perl-patterns`](skills/perl-patterns/SKILL.md) | Modern Perl 5.36+ idioms, best practices, and conventions for building robust, maintainabl... |
| [`perl-security`](skills/perl-security/SKILL.md) | Comprehensive Perl security covering taint mode, input validation, safe process execution,... |
| [`perl-testing`](skills/perl-testing/SKILL.md) | Perl testing patterns using Test2::V0, Test::More, prove runner, mocking, coverage with De... |

### 🐦 Flutter / Dart

| Skill | Description |
|-------|-------------|
| [`flutter-dart-code-review`](skills/flutter-dart-code-review/SKILL.md) | Library-agnostic Flutter/Dart code review checklist covering widget best practices, state ... |

### 🐘 Laravel / PHP

| Skill | Description |
|-------|-------------|
| [`laravel-patterns`](skills/laravel-patterns/SKILL.md) | Laravel architecture patterns, routing/controllers, Eloquent ORM, service layers, queues, ... |
| [`laravel-tdd`](skills/laravel-tdd/SKILL.md) | Test-driven development for Laravel with PHPUnit and Pest, factories, database testing, fa... |
| [`laravel-security`](skills/laravel-security/SKILL.md) | Laravel security best practices for authn/authz, validation, CSRF, mass assignment, file u... |
| [`laravel-verification`](skills/laravel-verification/SKILL.md) | Verification loop for Laravel projects: env checks, linting, static analysis, tests with c... |

### 🗄️ Database

| Skill | Description |
|-------|-------------|
| [`postgres-patterns`](skills/postgres-patterns/SKILL.md) | PostgreSQL database patterns for query optimization, schema design, indexing, and security... |
| [`clickhouse-io`](skills/clickhouse-io/SKILL.md) | ClickHouse database patterns, query optimization, analytics, and data engineering best pra... |
| [`database-migrations`](skills/database-migrations/SKILL.md) | Database migration best practices for schema changes, data migrations, rollbacks, and zero... |

### 🧪 Testing

| Skill | Description |
|-------|-------------|
| [`e2e-testing`](skills/e2e-testing/SKILL.md) | Playwright E2E testing patterns, Page Object Model, configuration, CI/CD integration, arti... |
| [`tdd-workflow`](skills/tdd-workflow/SKILL.md) | Use this skill when writing new features, fixing bugs, or refactoring code. Enforces test-... |
| [`ai-regression-testing`](skills/ai-regression-testing/SKILL.md) | Regression testing strategies for AI-assisted development. Sandbox-mode API testing withou... |
| [`verification-loop`](skills/verification-loop/SKILL.md) | A comprehensive verification system for Claude Code sessions. |
| [`eval-harness`](skills/eval-harness/SKILL.md) | Formal evaluation framework for Claude Code sessions implementing eval-driven development ... |

### 🔐 Security

| Skill | Description |
|-------|-------------|
| [`security-review`](skills/security-review/SKILL.md) | Use this skill when adding authentication, handling user input, working with secrets, crea... |
| [`security-scan`](skills/security-scan/SKILL.md) | Scan your Claude Code configuration (.claude/ directory) for security vulnerabilities, mis... |

### 🤖 AI / ML / Agents

| Skill | Description |
|-------|-------------|
| [`claude-api`](skills/claude-api/SKILL.md) | Anthropic Claude API patterns for Python and TypeScript. Covers Messages API, streaming, t... |
| [`mcp-server-patterns`](skills/mcp-server-patterns/SKILL.md) | Build MCP servers with Node/TypeScript SDK — tools, resources, prompts, Zod validation, st... |
| [`cost-aware-llm-pipeline`](skills/cost-aware-llm-pipeline/SKILL.md) | Cost optimization patterns for LLM API usage — model routing by task complexity, budget tr... |
| [`agent-eval`](skills/agent-eval/SKILL.md) | Head-to-head comparison of coding agents (Claude Code, Aider, Codex, etc.) on custom tasks... |
| [`agent-harness-construction`](skills/agent-harness-construction/SKILL.md) | Design and optimize AI agent action spaces, tool definitions, and observation formatting f... |
| [`agentic-engineering`](skills/agentic-engineering/SKILL.md) | Operate as an agentic engineer using eval-first execution, decomposition, and cost-aware m... |
| [`autonomous-loops`](skills/autonomous-loops/SKILL.md) | Patterns and architectures for autonomous Claude Code loops — from simple sequential pipel... |
| [`continuous-agent-loop`](skills/continuous-agent-loop/SKILL.md) | Patterns for continuous autonomous agent loops with quality gates, evals, and recovery con... |
| [`claude-devfleet`](skills/claude-devfleet/SKILL.md) | Orchestrate multi-agent coding tasks via Claude DevFleet — plan projects, dispatch paralle... |
| [`dmux-workflows`](skills/dmux-workflows/SKILL.md) | Multi-agent orchestration using dmux (tmux pane manager for AI agents). Patterns for paral... |
| [`team-builder`](skills/team-builder/SKILL.md) | Interactive agent picker for composing and dispatching parallel teams |
| [`ai-first-engineering`](skills/ai-first-engineering/SKILL.md) | Engineering operating model for teams where AI agents generate a large share of implementa... |

### 📚 Documentation

| Skill | Description |
|-------|-------------|
| [`documentation-lookup`](skills/documentation-lookup/SKILL.md) | Use up-to-date library and framework docs via Context7 MCP instead of training data. Activ... |
| [`architecture-decision-records`](skills/architecture-decision-records/SKILL.md) | Capture architectural decisions made during Claude Code sessions as structured ADRs. Auto-... |
| [`codebase-onboarding`](skills/codebase-onboarding/SKILL.md) | Analyze an unfamiliar codebase and generate a structured onboarding guide with architectur... |
| [`article-writing`](skills/article-writing/SKILL.md) | Write articles, guides, blog posts, tutorials, newsletter issues, and other long-form cont... |

### 🔧 Other

| Skill | Description |
|-------|-------------|
| [`blueprint`](skills/blueprint/SKILL.md) |  |
| [`carrier-relationship-management`](skills/carrier-relationship-management/SKILL.md) |  |
| [`configure-ecc`](skills/configure-ecc/SKILL.md) | Interactive installer for Everything Claude Code — guides users through selecting and inst... |
| [`content-engine`](skills/content-engine/SKILL.md) | Create platform-native content systems for X, LinkedIn, TikTok, YouTube, newsletters, and ... |
| [`content-hash-cache-pattern`](skills/content-hash-cache-pattern/SKILL.md) | Cache expensive file processing results using SHA-256 content hashes — path-independent, a... |
| [`context-budget`](skills/context-budget/SKILL.md) | Audits Claude Code context window consumption across agents, skills, MCP servers, and rule... |
| [`continuous-learning`](skills/continuous-learning/SKILL.md) | Automatically extract reusable patterns from Claude Code sessions and save them as learned... |
| [`continuous-learning-v2`](skills/continuous-learning-v2/SKILL.md) | Instinct-based learning system that observes sessions via hooks, creates atomic instincts ... |
| [`crosspost`](skills/crosspost/SKILL.md) | Multi-platform content distribution across X, LinkedIn, Threads, and Bluesky. Adapts conte... |
| [`customs-trade-compliance`](skills/customs-trade-compliance/SKILL.md) |  |
| [`data-scraper-agent`](skills/data-scraper-agent/SKILL.md) | Build a fully automated AI-powered data collection agent for any public source — job board... |
| [`deep-research`](skills/deep-research/SKILL.md) | Multi-source deep research using firecrawl and exa MCPs. Searches the web, synthesizes fin... |
| [`energy-procurement`](skills/energy-procurement/SKILL.md) |  |
| [`enterprise-agent-ops`](skills/enterprise-agent-ops/SKILL.md) | Operate long-lived agent workloads with observability, security boundaries, and lifecycle ... |
| [`exa-search`](skills/exa-search/SKILL.md) | Neural search via Exa MCP for web, code, and company research. Use when the user needs web... |
| [`fal-ai-media`](skills/fal-ai-media/SKILL.md) | Unified media generation via fal.ai MCP — image, video, and audio. Covers text-to-image (N... |
| [`inventory-demand-planning`](skills/inventory-demand-planning/SKILL.md) |  |
| [`investor-materials`](skills/investor-materials/SKILL.md) | Create and update pitch decks, one-pagers, investor memos, accelerator applications, finan... |
| [`investor-outreach`](skills/investor-outreach/SKILL.md) | Draft cold emails, warm intro blurbs, follow-ups, update emails, and investor communicatio... |
| [`iterative-retrieval`](skills/iterative-retrieval/SKILL.md) | Pattern for progressively refining context retrieval to solve the subagent context problem |
| [`logistics-exception-management`](skills/logistics-exception-management/SKILL.md) |  |
| [`market-research`](skills/market-research/SKILL.md) | Conduct market research, competitive analysis, investor due diligence, and industry intell... |
| [`nanoclaw-repl`](skills/nanoclaw-repl/SKILL.md) | Operate and extend NanoClaw v2, ECC's zero-dependency session-aware REPL built on claude -... |
| [`nutrient-document-processing`](skills/nutrient-document-processing/SKILL.md) | Process, convert, OCR, extract, redact, sign, and fill documents using the Nutrient DWS AP... |
| [`plankton-code-quality`](skills/plankton-code-quality/SKILL.md) | Write-time code quality enforcement using Plankton — auto-formatting, linting, and Claude-... |
| [`production-scheduling`](skills/production-scheduling/SKILL.md) |  |
| [`project-guidelines-example`](skills/project-guidelines-example/SKILL.md) | Example project-specific skill template based on a real production application. |
| [`prompt-optimizer`](skills/prompt-optimizer/SKILL.md) |  |
| [`quality-nonconformance`](skills/quality-nonconformance/SKILL.md) |  |
| [`ralphinho-rfc-pipeline`](skills/ralphinho-rfc-pipeline/SKILL.md) | RFC-driven multi-agent DAG execution pattern with quality gates, merge queues, and work un... |
| [`regex-vs-llm-structured-text`](skills/regex-vs-llm-structured-text/SKILL.md) | Decision framework for choosing between regex and LLM when parsing structured text — start... |
| [`returns-reverse-logistics`](skills/returns-reverse-logistics/SKILL.md) |  |
| [`rules-distill`](skills/rules-distill/SKILL.md) | Scan skills to extract cross-cutting principles and distill them into rules — append, revi... |
| [`search-first`](skills/search-first/SKILL.md) | Research-before-coding workflow. Search for existing tools, libraries, and patterns before... |
| [`skill-stocktake`](skills/skill-stocktake/SKILL.md) | Use when auditing Claude skills and commands for quality. Supports Quick Scan (changed ski... |
| [`strategic-compact`](skills/strategic-compact/SKILL.md) | Suggests manual context compaction at logical intervals to preserve context through task p... |
| [`video-editing`](skills/video-editing/SKILL.md) | AI-assisted video editing workflows for cutting, structuring, and augmenting real footage.... |
| [`videodb`](skills/videodb/SKILL.md) | See, Understand, Act on video and audio. See- ingest from local files, URLs, RTSP/live fee... |
| [`visa-doc-translate`](skills/visa-doc-translate/SKILL.md) | Translate visa application documents (images) to English and create a bilingual PDF with o... |
| [`x-api`](skills/x-api/SKILL.md) | X/Twitter API integration for posting tweets, threads, reading timelines, search, and anal... |

---

## 🌐 Global Access

This repository is **public**, so all skills are accessible from anywhere:

| How | Example |
|-----|---------|
| **Direct file reference** | `Reference skills/python-patterns/SKILL.md` |
| **Full GitHub URL** | `https://github.com/KanakMalpani/General-Private-Skills/blob/main/skills/python-patterns/SKILL.md` |
| **Raw content URL** | `https://raw.githubusercontent.com/KanakMalpani/General-Private-Skills/main/skills/python-patterns/SKILL.md` |
| **Repo reference** | `KanakMalpani/General-Private-Skills skills/python-patterns/SKILL.md` |

---

## 🔧 Adding Skills to Your Project

To make all skills available in any project, add this to your `.github/copilot-instructions.md`:

```markdown
This project uses skills from https://github.com/KanakMalpani/General-Private-Skills
Available skills: python-patterns, django-tdd, api-design, [etc.]
Reference skills using: skills/<name>/SKILL.md
```

---

## 📖 Configuration Files

- **`.copilot/config.json`** — Machine-readable skill registry listing all 116 skills with paths
- **`.copilot/agents.yml`** — Agent definitions for skill-based assistance  
- **`.copilot/skills.yml`** — Skills organized by language/category
- **`.github/copilot-instructions.md`** — Human-readable instructions for Copilot

---

*Skills sourced from the Everything Claude Code (ECC) collection.*
