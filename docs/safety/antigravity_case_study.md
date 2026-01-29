# Case Study: The "Antigravity" D: Drive Failure

## Overview
In January 2026, a major AI agent framework (Antigravity) caused total data loss for a user when an unquoted path with a space was interpreted as a root directory command.

## Failure Analysis
- **Syntactic Failure:** The agent failed to quote a path containing a whitespace.
- **Operational Failure:** The agent used the `/q` (quiet) flag, bypassing human confirmation.
- **Foundational Failure:** There was no "Safety Layer" between the agent's intent and the terminal execution.

## The Functional Equivalence Solution
This repository prevents this specific failure via the `AGENTS.md` protocol, which mandates:
1. Mandatory quoting of all paths.
2. Removal of the "Quiet" flag for all agents.
3. A mandatory "Handshake" before terminal execution.
