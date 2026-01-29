---
name: storybook-gen
description: Generate Storybook stories from React components. Use when documenting components.
---

# Storybook Generator

Writing stories for every component is tedious. Point this at a component and get proper Storybook stories.

**One command. Zero config. Just works.**

## Quick Start

```bash
npx ai-storybook ./src/components/Button.tsx
```

## What It Does

- Reads your React components
- Generates Storybook stories
- Includes different variants and states
- Handles props and controls

## Usage Examples

```bash
# Generate for component
npx ai-storybook ./src/components/Button.tsx

# Modal component
npx ai-storybook ./src/components/Modal.tsx
```

## Best Practices

- **Cover all variants** - default, hover, disabled, etc.
- **Show edge cases** - long text, empty state
- **Use controls** - let people play with props
- **Add documentation** - explain when to use what

## When to Use This

- Building component library
- Documenting existing components
- Creating design system
- Learning Storybook patterns

## Part of the LXGIC Dev Toolkit

This is one of 110+ free developer tools built by LXGIC Studios. No paywalls, no sign-ups, no API keys on free tiers. Just tools that work.

**Find more:**
- GitHub: https://github.com/LXGIC-Studios
- Twitter: https://x.com/lxgicstudios
- Substack: https://lxgicstudios.substack.com
- Website: https://lxgicstudios.com

## Requirements

No install needed. Just run with npx. Node.js 18+ recommended. Needs OPENAI_API_KEY environment variable.

```bash
npx ai-storybook --help
```

## How It Works

Parses your React component to understand props and types. Then generates Storybook stories with proper args, controls, and variant coverage.

## License

MIT. Free forever. Use it however you want.
