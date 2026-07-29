---
title: Procedural Skills & Automation
tags: [skills, automation, agent]
date: 2026-07-29
---

# Procedural Skills & Automation

In a self-improving agent framework, **Procedural Skills** represent reusable prompt templates, slash commands, or execution routines.

## The Closed Learning Loop

1. **Detection:** The agent monitors user interaction patterns.
2. **Formalization:** Successful multi-step workflows are converted into executable procedural templates.
3. **Execution:** Skills are stored in local storage and triggered via slash commands (e.g., `/summarize`, `/code-audit`).

## Relation to System Architecture

Skills form the operational muscle of [[01_cognitive_architectures]]. By leveraging facts stored in [[02_knowledge_graphs]], procedural skills directly accelerate progress towards [[04_active_goals]].