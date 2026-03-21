# GitHub Copilot Instructions

This repository contains 116 reusable development skills. When helping with code, apply the relevant skill patterns from the `skills/` directory.

## How to Use Skills

Reference a skill in Copilot Chat by mentioning it by name:
```
Using the python-patterns skill, help me refactor this code
Apply django-tdd patterns to write tests for this view  
Follow api-design patterns for this endpoint
```

Or reference the skill file directly:
```
Check skills/python-patterns/SKILL.md and improve this code
```

## Available Skills (116 total)

- **agent-eval**: Head-to-head comparison of coding agents (Claude Code, Aider, Codex, etc.) on cu... → `skills/agent-eval/SKILL.md`
- **agent-harness-construction**: Design and optimize AI agent action spaces, tool definitions, and observation fo... → `skills/agent-harness-construction/SKILL.md`
- **agentic-engineering**: Operate as an agentic engineer using eval-first execution, decomposition, and co... → `skills/agentic-engineering/SKILL.md`
- **ai-first-engineering**: Engineering operating model for teams where AI agents generate a large share of ... → `skills/ai-first-engineering/SKILL.md`
- **ai-regression-testing**: Regression testing strategies for AI-assisted development. Sandbox-mode API test... → `skills/ai-regression-testing/SKILL.md`
- **android-clean-architecture**: Clean Architecture patterns for Android and Kotlin Multiplatform projects — modu... → `skills/android-clean-architecture/SKILL.md`
- **api-design**: REST API design patterns including resource naming, status codes, pagination, fi... → `skills/api-design/SKILL.md`
- **architecture-decision-records**: Capture architectural decisions made during Claude Code sessions as structured A... → `skills/architecture-decision-records/SKILL.md`
- **article-writing**: Write articles, guides, blog posts, tutorials, newsletter issues, and other long... → `skills/article-writing/SKILL.md`
- **autonomous-loops**: Patterns and architectures for autonomous Claude Code loops — from simple sequen... → `skills/autonomous-loops/SKILL.md`
- **backend-patterns**: Backend architecture patterns, API design, database optimization, and server-sid... → `skills/backend-patterns/SKILL.md`
- **blueprint**:  → `skills/blueprint/SKILL.md`
- **bun-runtime**: Bun as runtime, package manager, bundler, and test runner. When to choose Bun vs... → `skills/bun-runtime/SKILL.md`
- **carrier-relationship-management**:  → `skills/carrier-relationship-management/SKILL.md`
- **claude-api**: Anthropic Claude API patterns for Python and TypeScript. Covers Messages API, st... → `skills/claude-api/SKILL.md`
- **claude-devfleet**: Orchestrate multi-agent coding tasks via Claude DevFleet — plan projects, dispat... → `skills/claude-devfleet/SKILL.md`
- **clickhouse-io**: ClickHouse database patterns, query optimization, analytics, and data engineerin... → `skills/clickhouse-io/SKILL.md`
- **codebase-onboarding**: Analyze an unfamiliar codebase and generate a structured onboarding guide with a... → `skills/codebase-onboarding/SKILL.md`
- **coding-standards**: Universal coding standards, best practices, and patterns for TypeScript, JavaScr... → `skills/coding-standards/SKILL.md`
- **compose-multiplatform-patterns**: Compose Multiplatform and Jetpack Compose patterns for KMP projects — state mana... → `skills/compose-multiplatform-patterns/SKILL.md`
- **configure-ecc**: Interactive installer for Everything Claude Code — guides users through selectin... → `skills/configure-ecc/SKILL.md`
- **content-engine**: Create platform-native content systems for X, LinkedIn, TikTok, YouTube, newslet... → `skills/content-engine/SKILL.md`
- **content-hash-cache-pattern**: Cache expensive file processing results using SHA-256 content hashes — path-inde... → `skills/content-hash-cache-pattern/SKILL.md`
- **context-budget**: Audits Claude Code context window consumption across agents, skills, MCP servers... → `skills/context-budget/SKILL.md`
- **continuous-agent-loop**: Patterns for continuous autonomous agent loops with quality gates, evals, and re... → `skills/continuous-agent-loop/SKILL.md`
- **continuous-learning**: Automatically extract reusable patterns from Claude Code sessions and save them ... → `skills/continuous-learning/SKILL.md`
- **continuous-learning-v2**: Instinct-based learning system that observes sessions via hooks, creates atomic ... → `skills/continuous-learning-v2/SKILL.md`
- **cost-aware-llm-pipeline**: Cost optimization patterns for LLM API usage — model routing by task complexity,... → `skills/cost-aware-llm-pipeline/SKILL.md`
- **cpp-coding-standards**: C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). Use wh... → `skills/cpp-coding-standards/SKILL.md`
- **cpp-testing**: Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, d... → `skills/cpp-testing/SKILL.md`
- **crosspost**: Multi-platform content distribution across X, LinkedIn, Threads, and Bluesky. Ad... → `skills/crosspost/SKILL.md`
- **customs-trade-compliance**:  → `skills/customs-trade-compliance/SKILL.md`
- **data-scraper-agent**: Build a fully automated AI-powered data collection agent for any public source —... → `skills/data-scraper-agent/SKILL.md`
- **database-migrations**: Database migration best practices for schema changes, data migrations, rollbacks... → `skills/database-migrations/SKILL.md`
- **deep-research**: Multi-source deep research using firecrawl and exa MCPs. Searches the web, synth... → `skills/deep-research/SKILL.md`
- **deployment-patterns**: Deployment workflows, CI/CD pipeline patterns, Docker containerization, health c... → `skills/deployment-patterns/SKILL.md`
- **django-patterns**: Django architecture patterns, REST API design with DRF, ORM best practices, cach... → `skills/django-patterns/SKILL.md`
- **django-security**: Django security best practices, authentication, authorization, CSRF protection, ... → `skills/django-security/SKILL.md`
- **django-tdd**: Django testing strategies with pytest-django, TDD methodology, factory_boy, mock... → `skills/django-tdd/SKILL.md`
- **django-verification**: Verification loop for Django projects: migrations, linting, tests with coverage,... → `skills/django-verification/SKILL.md`
- **dmux-workflows**: Multi-agent orchestration using dmux (tmux pane manager for AI agents). Patterns... → `skills/dmux-workflows/SKILL.md`
- **docker-patterns**: Docker and Docker Compose patterns for local development, container security, ne... → `skills/docker-patterns/SKILL.md`
- **documentation-lookup**: Use up-to-date library and framework docs via Context7 MCP instead of training d... → `skills/documentation-lookup/SKILL.md`
- **e2e-testing**: Playwright E2E testing patterns, Page Object Model, configuration, CI/CD integra... → `skills/e2e-testing/SKILL.md`
- **energy-procurement**:  → `skills/energy-procurement/SKILL.md`
- **enterprise-agent-ops**: Operate long-lived agent workloads with observability, security boundaries, and ... → `skills/enterprise-agent-ops/SKILL.md`
- **eval-harness**: Formal evaluation framework for Claude Code sessions implementing eval-driven de... → `skills/eval-harness/SKILL.md`
- **exa-search**: Neural search via Exa MCP for web, code, and company research. Use when the user... → `skills/exa-search/SKILL.md`
- **fal-ai-media**: Unified media generation via fal.ai MCP — image, video, and audio. Covers text-t... → `skills/fal-ai-media/SKILL.md`
- **flutter-dart-code-review**: Library-agnostic Flutter/Dart code review checklist covering widget best practic... → `skills/flutter-dart-code-review/SKILL.md`
- **foundation-models-on-device**: Apple FoundationModels framework for on-device LLM — text generation, guided gen... → `skills/foundation-models-on-device/SKILL.md`
- **frontend-patterns**: Frontend development patterns for React, Next.js, state management, performance ... → `skills/frontend-patterns/SKILL.md`
- **frontend-slides**: Create stunning, animation-rich HTML presentations from scratch or by converting... → `skills/frontend-slides/SKILL.md`
- **golang-patterns**: Idiomatic Go patterns, best practices, and conventions for building robust, effi... → `skills/golang-patterns/SKILL.md`
- **golang-testing**: Go testing patterns including table-driven tests, subtests, benchmarks, fuzzing,... → `skills/golang-testing/SKILL.md`
- **inventory-demand-planning**:  → `skills/inventory-demand-planning/SKILL.md`
- **investor-materials**: Create and update pitch decks, one-pagers, investor memos, accelerator applicati... → `skills/investor-materials/SKILL.md`
- **investor-outreach**: Draft cold emails, warm intro blurbs, follow-ups, update emails, and investor co... → `skills/investor-outreach/SKILL.md`
- **iterative-retrieval**: Pattern for progressively refining context retrieval to solve the subagent conte... → `skills/iterative-retrieval/SKILL.md`
- **java-coding-standards**: Java coding standards for Spring Boot services: naming, immutability, Optional u... → `skills/java-coding-standards/SKILL.md`
- **jpa-patterns**: JPA/Hibernate patterns for entity design, relationships, query optimization, tra... → `skills/jpa-patterns/SKILL.md`
- **kotlin-coroutines-flows**: Kotlin Coroutines and Flow patterns for Android and KMP — structured concurrency... → `skills/kotlin-coroutines-flows/SKILL.md`
- **kotlin-exposed-patterns**: JetBrains Exposed ORM patterns including DSL queries, DAO pattern, transactions,... → `skills/kotlin-exposed-patterns/SKILL.md`
- **kotlin-ktor-patterns**: Ktor server patterns including routing DSL, plugins, authentication, Koin DI, ko... → `skills/kotlin-ktor-patterns/SKILL.md`
- **kotlin-patterns**: Idiomatic Kotlin patterns, best practices, and conventions for building robust, ... → `skills/kotlin-patterns/SKILL.md`
- **kotlin-testing**: Kotlin testing patterns with Kotest, MockK, coroutine testing, property-based te... → `skills/kotlin-testing/SKILL.md`
- **laravel-patterns**: Laravel architecture patterns, routing/controllers, Eloquent ORM, service layers... → `skills/laravel-patterns/SKILL.md`
- **laravel-security**: Laravel security best practices for authn/authz, validation, CSRF, mass assignme... → `skills/laravel-security/SKILL.md`
- **laravel-tdd**: Test-driven development for Laravel with PHPUnit and Pest, factories, database t... → `skills/laravel-tdd/SKILL.md`
- **laravel-verification**: Verification loop for Laravel projects: env checks, linting, static analysis, te... → `skills/laravel-verification/SKILL.md`
- **liquid-glass-design**: iOS 26 Liquid Glass design system — dynamic glass material with blur, reflection... → `skills/liquid-glass-design/SKILL.md`
- **logistics-exception-management**:  → `skills/logistics-exception-management/SKILL.md`
- **market-research**: Conduct market research, competitive analysis, investor due diligence, and indus... → `skills/market-research/SKILL.md`
- **mcp-server-patterns**: Build MCP servers with Node/TypeScript SDK — tools, resources, prompts, Zod vali... → `skills/mcp-server-patterns/SKILL.md`
- **nanoclaw-repl**: Operate and extend NanoClaw v2, ECC's zero-dependency session-aware REPL built o... → `skills/nanoclaw-repl/SKILL.md`
- **nextjs-turbopack**: Next.js 16+ and Turbopack — incremental bundling, FS caching, dev speed, and whe... → `skills/nextjs-turbopack/SKILL.md`
- **nutrient-document-processing**: Process, convert, OCR, extract, redact, sign, and fill documents using the Nutri... → `skills/nutrient-document-processing/SKILL.md`
- **nuxt4-patterns**: Nuxt 4 app patterns for hydration safety, performance, route rules, lazy loading... → `skills/nuxt4-patterns/SKILL.md`
- **perl-patterns**: Modern Perl 5.36+ idioms, best practices, and conventions for building robust, m... → `skills/perl-patterns/SKILL.md`
- **perl-security**: Comprehensive Perl security covering taint mode, input validation, safe process ... → `skills/perl-security/SKILL.md`
- **perl-testing**: Perl testing patterns using Test2::V0, Test::More, prove runner, mocking, covera... → `skills/perl-testing/SKILL.md`
- **plankton-code-quality**: Write-time code quality enforcement using Plankton — auto-formatting, linting, a... → `skills/plankton-code-quality/SKILL.md`
- **postgres-patterns**: PostgreSQL database patterns for query optimization, schema design, indexing, an... → `skills/postgres-patterns/SKILL.md`
- **production-scheduling**:  → `skills/production-scheduling/SKILL.md`
- **project-guidelines-example**: Example project-specific skill template based on a real production application. → `skills/project-guidelines-example/SKILL.md`
- **prompt-optimizer**:  → `skills/prompt-optimizer/SKILL.md`
- **python-patterns**: Pythonic idioms, PEP 8 standards, type hints, and best practices for building ro... → `skills/python-patterns/SKILL.md`
- **python-testing**: Python testing strategies using pytest, TDD methodology, fixtures, mocking, para... → `skills/python-testing/SKILL.md`
- **pytorch-patterns**: PyTorch deep learning patterns and best practices for building robust, efficient... → `skills/pytorch-patterns/SKILL.md`
- **quality-nonconformance**:  → `skills/quality-nonconformance/SKILL.md`
- **ralphinho-rfc-pipeline**: RFC-driven multi-agent DAG execution pattern with quality gates, merge queues, a... → `skills/ralphinho-rfc-pipeline/SKILL.md`
- **regex-vs-llm-structured-text**: Decision framework for choosing between regex and LLM when parsing structured te... → `skills/regex-vs-llm-structured-text/SKILL.md`
- **returns-reverse-logistics**:  → `skills/returns-reverse-logistics/SKILL.md`
- **rules-distill**: Scan skills to extract cross-cutting principles and distill them into rules — ap... → `skills/rules-distill/SKILL.md`
- **rust-patterns**: Idiomatic Rust patterns, ownership, error handling, traits, concurrency, and bes... → `skills/rust-patterns/SKILL.md`
- **rust-testing**: Rust testing patterns including unit tests, integration tests, async testing, pr... → `skills/rust-testing/SKILL.md`
- **search-first**: Research-before-coding workflow. Search for existing tools, libraries, and patte... → `skills/search-first/SKILL.md`
- **security-review**: Use this skill when adding authentication, handling user input, working with sec... → `skills/security-review/SKILL.md`
- **security-scan**: Scan your Claude Code configuration (.claude/ directory) for security vulnerabil... → `skills/security-scan/SKILL.md`
- **skill-stocktake**: Use when auditing Claude skills and commands for quality. Supports Quick Scan (c... → `skills/skill-stocktake/SKILL.md`
- **springboot-patterns**: Spring Boot architecture patterns, REST API design, layered services, data acces... → `skills/springboot-patterns/SKILL.md`
- **springboot-security**: Spring Security best practices for authn/authz, validation, CSRF, secrets, heade... → `skills/springboot-security/SKILL.md`
- **springboot-tdd**: Test-driven development for Spring Boot using JUnit 5, Mockito, MockMvc, Testcon... → `skills/springboot-tdd/SKILL.md`
- **springboot-verification**: Verification loop for Spring Boot projects: build, static analysis, tests with c... → `skills/springboot-verification/SKILL.md`
- **strategic-compact**: Suggests manual context compaction at logical intervals to preserve context thro... → `skills/strategic-compact/SKILL.md`
- **swift-actor-persistence**: Thread-safe data persistence in Swift using actors — in-memory cache with file-b... → `skills/swift-actor-persistence/SKILL.md`
- **swift-concurrency-6-2**: Swift 6.2 Approachable Concurrency — single-threaded by default, @concurrent for... → `skills/swift-concurrency-6-2/SKILL.md`
- **swift-protocol-di-testing**: Protocol-based dependency injection for testable Swift code — mock file system, ... → `skills/swift-protocol-di-testing/SKILL.md`
- **swiftui-patterns**: SwiftUI architecture patterns, state management with @Observable, view compositi... → `skills/swiftui-patterns/SKILL.md`
- **tdd-workflow**: Use this skill when writing new features, fixing bugs, or refactoring code. Enfo... → `skills/tdd-workflow/SKILL.md`
- **team-builder**: Interactive agent picker for composing and dispatching parallel teams → `skills/team-builder/SKILL.md`
- **verification-loop**: A comprehensive verification system for Claude Code sessions. → `skills/verification-loop/SKILL.md`
- **video-editing**: AI-assisted video editing workflows for cutting, structuring, and augmenting rea... → `skills/video-editing/SKILL.md`
- **videodb**: See, Understand, Act on video and audio. See- ingest from local files, URLs, RTS... → `skills/videodb/SKILL.md`
- **visa-doc-translate**: Translate visa application documents (images) to English and create a bilingual ... → `skills/visa-doc-translate/SKILL.md`
- **x-api**: X/Twitter API integration for posting tweets, threads, reading timelines, search... → `skills/x-api/SKILL.md`

## Skill File Format

Each skill follows this format in `skills/<name>/SKILL.md`:
```yaml
---
name: skill-name
description: What this skill covers
origin: ECC
---
# Skill Title
## When to Activate
## Core Principles
[patterns and examples]
```

## Usage Patterns

### In VS Code Copilot Chat
```
Reference skills/python-patterns/SKILL.md and help me with type hints
```

### In GitHub Copilot Chat (Web)
```
Using patterns from KanakMalpani/General-Private-Skills/skills/django-tdd/SKILL.md, write tests for my model
```

### Direct skill reference
```
Apply the patterns in skills/api-design/SKILL.md to design this REST endpoint
```

## Repository Structure
```
.copilot/
  config.json      # Skill registry (all 116 skills)
  agents.yml       # Agent definitions  
  skills.yml       # Skills organized by category
.github/
  copilot-instructions.md  # This file
skills/
  <skill-name>/
    SKILL.md       # Skill content with frontmatter
```
