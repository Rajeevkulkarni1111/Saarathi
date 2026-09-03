# Saarathi

> A Personal Execution OS that understands what you are trying to accomplish, determines what matters, and helps you decide what to do next.

---

## Table of Contents

- [Overview](#overview)
- [What is a Personal Execution OS?](#what-is-a-personal-execution-os)
- [The Problem](#the-problem)
- [Why Saarathi](#why-saarathi)
- [Core Product Philosophy](#core-product-philosophy)
- [Product Vision](#product-vision)
- [Core Principles](#core-principles)
- [How Saarathi Thinks](#how-saarathi-thinks)
- [High-Level Product Flow](#high-level-product-flow)
- [System Architecture](#system-architecture)
- [Architecture Layers](#architecture-layers)
- [Core Domain Model](#core-domain-model)
- [Intelligence Layer](#intelligence-layer)
- [Execution Model](#execution-model)
- [Technology Stack](#technology-stack)
- [Repository Structure](#repository-structure)
- [Backend Architecture](#backend-architecture)
- [Frontend Architecture](#frontend-architecture)
- [Database](#database)
- [API Design](#api-design)
- [AI and Agent Architecture](#ai-and-agent-architecture)
- [Context and Memory](#context-and-memory)
- [Prioritisation](#prioritisation)
- [Decision and Next-Action Engine](#decision-and-next-action-engine)
- [Feedback Loop](#feedback-loop)
- [Security and Privacy](#security-and-privacy)
- [Local Development](#local-development)
- [Development Workflow](#development-workflow)
- [Git and Branching Strategy](#git-and-branching-strategy)
- [Testing Strategy](#testing-strategy)
- [Continuous Integration](#continuous-integration)
- [Engineering Principles](#engineering-principles)
- [Sprint Roadmap](#sprint-roadmap)
- [Definition of Done](#definition-of-done)
- [Project Evolution](#project-evolution)
- [Project Status](#project-status)
- [Final Vision](#final-vision)

---

# Overview

Saarathi is a **Personal Execution OS**.

It is designed around a simple idea:

> People do not primarily struggle because they cannot store tasks. They struggle because they do not always know what matters, what to focus on, and what to do next.

Traditional productivity software generally focuses on:

- Tasks
- Notes
- Calendars
- Reminders
- Lists
- Deadlines

Saarathi aims to operate at a higher level.

Instead of simply asking:

> "What tasks do you have?"

Saarathi aims to understand:

> "What are you trying to accomplish?"

and then help answer:

> "What matters right now?"

and:

> "What should you do next?"

---

# What is a Personal Execution OS?

A Personal Execution OS is an intelligent system that sits between a person's **intent** and their **execution**.

It helps translate:

```text
Intent
   ↓
Goals
   ↓
Context
   ↓
Priorities
   ↓
Decisions
   ↓
Actions
   ↓
Execution
   ↓
Feedback
   ↓
Updated Context