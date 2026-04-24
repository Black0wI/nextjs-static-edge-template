# Contributing to Next.js SST Boilerplate

Thank you for your interest in contributing! This document provides guidelines for a smooth contribution workflow.

## Development Setup

```bash
git clone https://github.com/Black0wI/fullstack-serverless-ssr.git
cd fullstack-serverless-ssr
make setup
make dev
```

## Branch Strategy

| Branch | Purpose                                      |
| ------ | -------------------------------------------- |
| `main` | Stable default branch                        |
| `feat/*`, `fix/*` | Short-lived branches for contributions |

## Commit Conventions

Use [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add new feature card component
fix: resolve header blur on mobile Safari
docs: update deployment instructions
refactor: extract design tokens to CSS variables
chore: update dependencies
```

## Pull Request Process

1. Create a branch from `main`
2. Make your changes with descriptive commits
3. Ensure all checks pass: `make check`
4. Open a PR to `main`
5. Wait for review and address feedback
6. Merge once the branch is approved and green

## Code Standards

- **TypeScript**: Strict mode, no `any`, named exports
- **CSS**: Use design tokens (`var(--token)`), BEM naming
- **Components**: One per file, Server Components by default
- **Tests**: Cover critical logic

## Questions?

Open an issue or reach out to the maintainers.
