# Context Map

This file explains where context lives and when to use it.

## Root Files

- `profile.md`: durable identity.
- `voice.md`: writing style.
- `strategy.md`: decision filters and Xpand Studio strategy.
- `active-projects.md`: current work, date-sensitive.
- `project-index.md`: map of project-specific context.

## Context Portfolio

Use `context-portfolio/` as the deeper knowledge base:

- `01-identity.md`: expanded identity.
- `02-role-and-responsibilities.md`: actual work responsibilities.
- `03-current-projects.md`: expanded active project list.
- `04-team-and-relationships.md`: people and collaborators.
- `05-tools-and-systems.md`: tools, subscriptions, workflows.
- `06-communication-style.md`: communication preferences.
- `07-goals-and-priorities.md`: priorities and optimization filters.
- `08-preferences-and-constraints.md`: hard rules and constraints.
- `09-domain-knowledge.md`: expertise the agent should not over-explain.
- `10-decision-log.md`: decision patterns and open decisions.

## Conflict Rule

If root files conflict with `context-portfolio/`, prefer root files for current operating instructions. Treat `context-portfolio/` as richer background unless the user says otherwise.

## Verification Rule

Dates, current project status, deadlines, and tool behavior must be verified before being treated as current.
