# SpacetimeDB Agent Skills

A collection of skills for AI coding agents. Skills are packaged instructions and scripts that extend agent capabilities for building real-time, multiplayer applications with SpacetimeDB.

Skills follow the [Agent Skills](https://agentskills.io/) format.

## Available Skills

### spacetimedb-best-practices

SpacetimeDB development best practices for TypeScript server modules and client SDK. Contains rules across multiple categories, prioritized by impact.

**Use when:**
- Writing SpacetimeDB server modules in TypeScript
- Implementing client-side subscriptions and state management
- Setting up React hooks for SpacetimeDB integration
- Reviewing code for performance and real-time sync issues
- Optimizing query patterns and reducer design

**Categories covered:**
- Module Design (Critical)
- Table Schema & Indexing (Critical)
- Reducer Patterns (High)
- Subscription Optimization (High)
- Client State Management (Medium-High)
- React Integration (Medium)
- TypeScript Patterns (Medium)
- Real-time Sync (Low-Medium)

### web-design-guidelines

Review UI code for compliance with web interface best practices. Audits your code for 100+ rules covering accessibility, performance, and UX.

**Use when:**
- "Review my UI"
- "Check accessibility"
- "Audit design"
- "Review UX"
- "Check my site against best practices"

**Categories covered:**
- Accessibility (aria-labels, semantic HTML, keyboard handlers)
- Focus States (visible focus, focus-visible patterns)
- Forms (autocomplete, validation, error handling)
- Animation (prefers-reduced-motion, compositor-friendly transforms)
- Typography (curly quotes, ellipsis, tabular-nums)
- Images (dimensions, lazy loading, alt text)
- Performance (virtualization, layout thrashing, preconnect)
- Navigation & State (URL reflects state, deep-linking)
- Dark Mode & Theming (color-scheme, theme-color meta)
- Touch & Interaction (touch-action, tap-highlight)
- Locale & i18n (Intl.DateTimeFormat, Intl.NumberFormat)

## Installation

```bash
npx add-skill spacetimedb/agent-skills
```

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

**Examples:**
```
Create a SpacetimeDB module for a chat app
```
```
Review this reducer for performance issues
```
```
Help me optimize my subscription queries
```
```
Set up React hooks for my SpacetimeDB client
```

## Skill Structure

Each skill contains:
- `SKILL.md` - Instructions for the agent
- `scripts/` - Helper scripts for automation (optional)
- `references/` - Supporting documentation (optional)

## License

MIT
