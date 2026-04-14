# allternit-api-client — Agent Guide

> Official TypeScript API client for the Allternit platform.

## Quick Start

```bash
npm install
npm run build
```

## Key Commands

| Command | What it does |
|---------|--------------|
| `npm install` | Install dev dependencies |
| `npm run build` | Compile `src/` to `dist/` (tsc) |
| `npm run prepare` | Runs `build` automatically on install |

## Directory Map

| Path | Purpose |
|------|---------|
| `src/` | TypeScript source (`index.ts`) |
| `dist/` | Compiled JS + type declarations |
| `allternit-api-client/` | Duplicate source tree (legacy) |

## Conventions

- **Package manager:** npm
- **Build tool:** TypeScript compiler (`tsc`)
- **Module:** ESM (`"type": "module"`)
- **No tests** are currently configured

## Warnings

- Do not edit `dist/` directly — always modify `src/` and rebuild.
- If adding new endpoints, keep the client API surface minimal and typed.

## Related Repos

- [`allternit-platform`](https://github.com/Gizziio/allternit-platform) — API definitions
- [`allternit-sdk`](https://github.com/Gizziio/allternit-sdk) — Higher-level SDK
