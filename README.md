# Alex Bachlej

AI-native systems engineer focused on multi-LLM orchestration runtimes, controlled AI execution, and practical developer tooling.

I build systems where AI does not just generate code blindly. The work is scoped, reviewed, tested, audited, and shipped through controlled execution loops.

## Ecosystem map

I build controlled AI execution systems.

- **archon3** - early orchestration and planning foundation
- **RailTaskLite** - supervised AI execution workflow
- **pixctl** - inspectable software artifact produced through that workflow
- **blackbox-raven** - early local AI operator experiment

The goal is not autonomous AI.

The goal is controlled execution, auditability, and reproducible software delivery.

## Core narrative

Most people argue whether AI is magic.

I built the button, wired the machine behind it, added logs, tests, audits, and release gates, then pressed it.

Everyone wants the magic button.  
The leverage is building it.

## Current focus

- Multi-LLM orchestration runtimes
- Supervised AI execution pipelines
- Python CLI tools for AI/dev workflows
- Prompt contracts, audit gates, and release discipline
- FastAPI, Redis, Docker, automation infrastructure

## Public proof artifacts

### RailTaskLite

RailTaskLite is my controlled AI execution workflow: scoped batches, allowed files, audit gates, repair loops, tests, operator decisions, and release checks.

The goal is not "AI wrote code for me."

The goal is controlled AI execution that produces inspectable software artifacts.

### pixctl

[pixctl](https://github.com/alexbachlej/pixctl) is a practical local image optimization and Real-ESRGAN upscaling tool.

It is also an inspectable output artifact from RailTaskLite. The code is public so the quality of the generated software can be evaluated directly.

### production-engineering-samples

[production-engineering-samples](https://github.com/alexbachlej/production-engineering-samples) contains small, standalone code samples extracted and sanitized from AI-native backend and orchestration systems.

It focuses on production patterns without exposing product internals: HMAC metadata signing, atomic filesystem writes, state-machine validation, safe upload handling, cursor pagination, immutable runtime reports, and audio temporal mapping.

### archon3

[archon3](https://github.com/alexbachlej/archon3) is an early multi-agent orchestration prototype and part of the foundation that led toward the RailTaskLite workflow.

It explores structured planning, building, validation, and integration across AI-driven software tasks.

### blackbox-raven

[blackbox-raven](https://github.com/alexbachlej/blackbox-raven) is a small local AI terminal/operator experiment for project-file injection, code generation, and session persistence.

It is a side artifact, not the flagship.

## What I am building next

Small, sharp public tools around AI execution quality:

- repo trust audits
- log sanitization
- prompt contract linting
- agent run cards
- MCP safety scanning
- supervised AI build evidence

The direction is simple:

AI execution should be inspectable, repeatable, auditable, and useful.
