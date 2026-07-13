# FlyRank Capstone Project Rules

This document outlines the development guidelines, tech stack, and conventions for the FlyRank Frontend AI Engineering track capstone project.

## Tech Stack
- **Framework:** Next.js (App Router, React 19/latest)
- **Language:** TypeScript (strict mode)
- **Styling:** Tailwind CSS (mobile-first approach)
- **State Management / Data Fetching:** React Server Components (RSC), React Query, or standard React Hooks as needed.

## Coding Conventions

### 1. TypeScript Rules
- Enforce strict typing. Avoid using `any` or `unsafe` casts.
- Use explicit type definitions for function return types, component props, and API responses.
- Leverage TypeScript interfaces or types for data models and component props.

### 2. Styling (Tailwind CSS)
- Implement utility-first styles with a **mobile-first** approach (i.e., base styles apply to mobile first, and responsive prefixes `md:`, `lg:` build up for larger screens).
- Maintain custom theme definitions in `tailwind.config.ts`.
- Avoid arbitrary values (e.g., `h-[343px]`) where standard theme spacing tokens exist.

### 3. Component Structure & Design
- **Component File Structure:** Place components in `/components` grouped by domain or functionality (e.g., `/components/ui/` for primitive design system components, and custom features in `/components/features/`).
- Use React Server Components (RSC) by default. Add `"use client"` only at the leaf nodes or components that require client-side interactivity, state, or hooks.
- Follow a clean file structure:
  - Separate styles, helper utilities, and logic where appropriate.
  - Export components as named exports or default exports consistently.

### 4. Build, Lint, and Format Commands
- **Run dev server:** `npm run dev`
- **Build application:** `npm run build`
- **Run linter:** `npm run lint`
- **Type check:** `npx tsc --noEmit`
