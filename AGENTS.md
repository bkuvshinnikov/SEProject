# AGENTS.md

## Purpose
This file defines how AI agents (Copilot, Claude, Cursor) should work with this repository.

The goal is to ensure consistent, structured, and high-quality contributions.

---

## Project Summary
- This project is a Software Engineering course project.
- It represents a knowledge-based system / structured project documentation repository.
- The main goal is to organize, manage, and evolve project knowledge and artifacts.

---

## Core Concept
- The project focuses on:
  - structured documentation
  - knowledge organization
  - clear separation of concerns
- Code and documentation should always stay aligned.

---

## Source of Truth (IMPORTANT)
- The `/docs` folder contains:
  - requirements
  - project descriptions
  - architecture and decisions

❗ RULE:
AI agents MUST always check `/docs` before:
- writing code
- making changes
- making assumptions

If something is unclear — do NOT guess.

---

## Key Principles
- Clarity over complexity
- Consistency over creativity
- Simplicity over overengineering
- Follow existing patterns

---

## Code Guidelines
- Follow the existing project structure
- Use clear and descriptive naming
- Keep functions small and focused
- Avoid unnecessary abstractions
- Write clean and readable code

---

## Technology Constraints
- Use only technologies already present in the project
- Do NOT introduce new frameworks or libraries without justification

---

## Safety Rules
- Do not break existing functionality
- Do not modify unrelated files
- Do not delete code without reason
- Do not overwrite documentation arbitrarily

---

## Documentation Rules
- Documentation is a core part of this project
- Keep `/docs` updated when making changes
- Ensure code and documentation are consistent

---

## Collaboration Model
- Human developer is the final decision-maker
- AI acts as an assistant:
  - suggests improvements
  - generates code
  - explains decisions when needed

---

## Expected Output
- Provide complete and working solutions
- Avoid placeholders unless requested
- Ensure compatibility with existing project structure

---

## When in Doubt
1. Check `/docs`
2. Review existing files
3. Choose the simplest correct solution
