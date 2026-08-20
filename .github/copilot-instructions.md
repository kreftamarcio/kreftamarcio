# Copilot Instructions

These are the coding standards for this repository and all repositories owned by @kreftamarcio. Any AI coding assistant (Copilot, Cursor, Cody, etc.) MUST follow these rules.

## Language & Runtime

- **TypeScript only.** No `.js` files in `src/`. Build outputs go to `dist/`.
- **Node.js >= 20.** Use native `fetch`, `crypto`, `performance` APIs.
- **ESM modules.** All imports use `.js` extension in source (TypeScript resolves them).

## Type System

- **Zero `any`.** Use `unknown` + narrowing, generics, or branded types instead.
- **Explicit return types** on all exported functions. Internal helpers can rely on inference.
- **`type` imports** via `import type { ... }` or inline `import { type Foo }`.
- **Prefer interfaces** for object shapes that will be implemented. Use `type` for unions, intersections, and mapped types.
- **Naming conventions:**
  - Interfaces: `PascalCase` (no `I` prefix)
  - Type aliases: `PascalCase`
  - Enums: `PascalCase` (members: `PascalCase`)
  - Classes: `PascalCase`
  - Functions/variables: `camelCase`
  - Constants: `UPPER_SNAKE_CASE` only for true compile-time constants
  - Files: `kebab-case.ts`

## Error Handling

- **Never swallow errors.** Every `catch` must either rethrow, wrap in a domain error, or explicitly handle.
- **Domain errors extend `Error`** with a `readonly code` property and typed `cause`.
- **No `throw` of non-Error values.** Always `throw new SomeError(...)`.
- **Async functions:** Always handle promise rejections. Use `@typescript-eslint/no-floating-promises`.

## Architecture Patterns

- **Dependency Injection** via constructor parameters, never global singletons.
- **Composition over inheritance.** Prefer small, focused modules composed together.
- **Barrel exports** in `src/index.ts` only. No deep imports from outside the package.
- **Side-effect free modules.** A module import must not trigger I/O or mutation.
- **Configuration validated at construction** with Zod. Fail fast, fail loud.

## State Management (React)

- **Server state:** React Query / TanStack Query. Never `useEffect` + `useState` for fetching.
- **Client state:** Zustand for global, `useState` for local.
- **No prop drilling** beyond 2 levels. Use context or composition.
- **Render optimization:** `React.memo` only when measured. `useMemo`/`useCallback` only for referential stability passed to memoized children.

## Testing

- **Vitest** as test runner. Never Jest in new projects.
- **Test behavior, not implementation.** Test the public API surface.
- **No mocking of internal modules.** Mock only external boundaries (network, DB, clock).
- **Naming:** `describe('ClassName')` > `it('should verb when condition')`.

## Formatting & Linting

- **ESLint flat config** with `typescript-eslint/strict-type-checked`.
- **No Prettier.** ESLint handles formatting via stylistic rules.
- **2-space indentation.** Single quotes. No semicolons (ESLint enforced where configured).
- **Max line length:** 100 characters (soft guide, not hard rule).

## Git & CI

- **Conventional commits:** `feat:`, `fix:`, `refactor:`, `docs:`, `test:`, `chore:`.
- **CI gates:** typecheck + lint + test must pass before merge.
- **No force push** to `main`. PRs only.

## Documentation

- **TSDoc** on all exported symbols. At minimum: one sentence explaining *what* and *why*.
- **README** explains the problem solved, not just the API.
- **ARCHITECTURE.md** for repos with > 5 modules.

## Security

- **No secrets in code.** Use environment variables validated with Zod at startup.
- **Input validation** at every system boundary (API routes, message handlers, file parsers).
- **Dependency audit** in CI. No `npm audit` high/critical unresolved.

## What NOT to Generate

- No `console.log` in production code (use structured logging or event emitters).
- No `// TODO` without a linked issue.
- No default exports (except Next.js pages/routes where required).
- No `enum` with string values when a union type suffices.
- No `class` for pure data. Use interfaces + factory functions.
