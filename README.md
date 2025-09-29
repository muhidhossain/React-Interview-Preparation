# React Interview Preparation

## Overview

This repository contains comprehensive notes, examples, and interview-focused guidance for React and related front-end topics. Each topic includes clear explanations, practical code snippets, and interview-ready summaries to help you prepare for technical interviews that focus on React, its ecosystem, and front-end engineering fundamentals.

## Table of Contents

### 📚 Core React

1. **[React Hooks Guide](01.%20Core%20React/01.%20React%20Hooks%20Guide.md)**

   - Covers useState, useEffect, useRef, useMemo, useCallback
   - Custom hooks and hook composition

2. **[Custom Hooks](01.%20Core%20React/02.%20Custom%20Hooks.md)**

   - Creating reusable hooks
   - Rules of hooks and testing hooks

3. **[Controlled vs Uncontrolled Components](01.%20Core%20React/03.%20Controlled%20vs%20Uncontrolled%20Components.md)**

   - Form handling patterns and trade-offs

4. **[Lifting State Up](01.%20Core%20React/04.%20Lifting%20State%20Up.md)**

   - State ownership and prop drilling

5. **[React Lifecycle (Class Components)](01.%20Core%20React/05.%20React%20Lifecycle%20%28Class%20Components%29.md)**

   - Class lifecycle methods and functional equivalents

6. **[Error Boundaries](01.%20Core%20React/06.%20Error%20Boundaries.md)**

   - Error handling strategies in React

7. **[Portals](01.%20Core%20React/07.%20Portals.md)**

   - Rendering outside the DOM hierarchy

8. **[Fragments, StrictMode & Suspense](01.%20Core%20React/08.%20Fragments%2C%20StrictMode%2C%20Suspense.md)**

   - Useful built-in components and patterns

### 🔧 Performance & Optimization

1. **[Memoization (React.memo, useMemo, useCallback)](02.%20React%20Performance%20Optimization/01.%20Memoization%20%28React.memo%2C%20useMemo%2C%20useCallback%29.md)**

   - Preventing unnecessary re-renders and memoization patterns

2. **[Virtualization (react-window, react-virtualized)](02.%20React%20Performance%20Optimization/02.%20Virtualization%20%28react-window%2C%20react-virtualized%29.md)**

   - Efficient large list rendering and windowing strategies

3. **[Lazy Loading & Code-Splitting (React.lazy, Suspense)](02.%20React%20Performance%20Optimization/03.%20Lazy%20loading%20%26%20code-splitting%20%28React.lazy%2C%20Suspense%29.md)**

   - Reducing bundle size and improving load times

4. **[Avoiding Unnecessary Re-renders](02.%20React%20Performance%20Optimization/04.%20Avoiding%20unnecessary%20re-renders.md)**

   - Common causes of re-renders and how to mitigate them

5. **[Efficient List Rendering (keys, windowing)](02.%20React%20Performance%20Optimization/05.%20Efficient%20list%20rendering%20%28keys%2C%20windowing%29.md)**

   - Keys, virtualization, and rendering performance techniques

### 🧠 State Management

1. **[React Context API](03.%20State%20Management/01.%20React%20Context%20API.md)**

   - Patterns, pitfalls, and performance considerations

2. **[Redux (Thunk, Saga, Toolkit)](03.%20State%20Management/02.%20Redux%20%28Thunk%2C%20Saga%2C%20Toolkit%29.md)**

   - When to use Redux and common patterns

3. **[Zustand, Recoil, Jotai](03.%20State%20Management/03.%20Zustand%2C%20Recoil%2C%20Jotai%20%28Modern%20Lightweight%20Libraries%29.md)**

   - Modern lightweight state solutions

4. **[Comparison: Local State vs Global State](03.%20State%20Management/04.%20Comparison%3A%20Local%20State%20vs%20Global%20State.md)**

   - When to choose local, lifted, or global state

### 🌐 Routing

1. **[React Router v6+](04.%20Routing/01.%20React%20Router%20v6%2B.md)**

   - Overview of v6+ features, route nesting, and hooks

2. **[Nested Routes](04.%20Routing/02.%20Nested%20Routes.md)**

   - Building nested UI and layout routes

3. **[Route Protection (PrivateRoute)](04.%20Routing/03.%20Route%20Protection%20%28PrivateRoute%29.md)**

   - Protecting routes and authentication patterns

4. **[URL Parameters, Query Strings](04.%20Routing/04.%20URL%20Parameters%2C%20Query%20Strings.md)**

   - Reading and managing params and query strings

5. **[Layouts with Nested Routing](04.%20Routing/05.%20Layouts%20with%20Nested%20Routing.md)**

   - Combining layouts with nested routing for page structure

### 🧾 Forms

1. **[Controlled vs Uncontrolled Inputs](05.%20Forms/01.%20Controlled%20vs%20Uncontrolled%20Inputs.md)**

   - Differences, pros/cons, and when to use each pattern

2. **[Form Libraries (Formik, React Hook Form)](05.%20Forms/02.%20Form%20Libraries%20%28Formik%2C%20React%20Hook%20Form%29.md)**

   - Library comparisons, validation strategies, and performance tips

3. **[Validation (Zod, Yup, custom validation)](05.%20Forms/03.%20Validation%20%28Zod%2C%20Yup%2C%20custom%20validation%29.md)**

   - Schema validation, runtime checks, and integration with form libraries

4. **[Dynamic Form Fields](05.%20Forms/04.%20Dynamic%20Form%20Fields.md)**

   - Adding/removing fields, arrays of inputs, and form state management

### 🔌 API Integrations

1. **[Fetching Data (fetch, axios, GraphQL, etc.)](06.%20API%20Integrations/01.%20Fetching%20Data%20Using%20fetch%2C%20axios%2C%20GraphQL%2C%20etc..md)**

   - fetch, axios, GraphQL, REST patterns and best practices

2. **[Data Fetching Libraries: React Query (TanStack Query), SWR](06.%20API%20Integrations/02.%20Data%20Fetching%20Libraries%3A%20React%20Query%20%28TanStack%20Query%29%2C%20SWR.md)**

   - Caching strategies, query invalidation, pagination, and infinite scroll

3. **[Caching, Pagination, Infinite Scroll](06.%20API%20Integrations/03.%20Caching%2C%20Pagination%2C%20Infinite%20Scroll.md)**

   - Patterns for caching, cursor vs page pagination, and UX considerations

4. **[Error & Loading States](06.%20API%20Integrations/04.%20Error%20%26%20Loading%20States.md)**

   - Handling loading, error, and empty states in UI

5. **[Debouncing, Throttling](06.%20API%20Integrations/05.%20Debouncing%2C%20Throttling.md)**

   - Rate-limiting interactions and improving perceived performance

### ✅ Testing

1. **[Unit Testing: Jest, React Testing Library](07.%20Testing/01.%20Unit%20Testing%3A%20Jest%2C%20React%20Testing%20Library.md)**

   - Writing unit tests for components and hooks

2. **[Component Testing](07.%20Testing/02.%20Component%20Testing.md)**

   - Testing component behavior and props

3. **[Integration Testing](07.%20Testing/03.%20Integration%20Testing.md)**

   - End-to-end flows and combined module testing

4. **[Mocking APIs with MSW](07.%20Testing/04.%20Mocking%20APIs%20with%20MSW.md)**

   - Use MSW to mock network requests in tests

5. **[Snapshot Testing](07.%20Testing/05.%20Snapshot%20Testing.md)**

   - When snapshots help and when they hurt

### 🔣 TypeScript with React

1. **[Typing Props, State, Refs, and Hooks](08.%20TypeScript%20with%20React/01.%20Typing%20Props%2C%20State%2C%20Refs%2C%20and%20Hooks.md)**

   - How to type components, refs, and hooks

2. **[Generics in Components and Hooks](08.%20TypeScript%20with%20React/02.%20Generics%20in%20Components%20and%20Hooks.md)**

   - Using generics to create reusable typed components and hooks

3. **[Discriminated Unions for Conditional Rendering](08.%20TypeScript%20with%20React/03.%20Discriminated%20Unions%20for%20Conditional%20Rendering.md)**

   - Pattern matching and safer conditional rendering with unions

4. **[Utility Types (Partial, Pick, Omit, etc.)](08.%20TypeScript%20with%20React/04.%20Utility%20Types%20%28Partial%2C%20Pick%2C%20Omit%2C%20etc.%29.md)**

   - Common utility types and when to use them

### 🎨 Styling

1. **[CSS Modules, SCSS, Styled Components, Emotion, TailwindCSS](09.%20CSS%20%26%20Styling/01.%20CSS%20Modules%2C%20SCSS%2C%20Styled%20Components%2C%20Emotion%2C%20TailwindCSS.md)**

   - Styling strategies: CSS Modules, utility-first, and CSS-in-JS trade-offs

2. **[Responsive Design & BEM](09.%20CSS%20%26%20Styling/02.%20Responsive%20Design%20%26%20BEM.md)**

   - Layout strategies, breakpoints, and naming conventions

3. **[Theming and Dark Mode](09.%20CSS%20%26%20Styling/03.%20Theming%20and%20Dark%20Mode.md)**

   - Theme variables, prefers-color-scheme, and CSS variables

4. **[CSS-in-JS Patterns](09.%20CSS%20%26%20Styling/04.%20CSS-in-JS%20Patterns.md)**

   - Patterns and trade-offs for CSS-in-JS libraries

### ⚙️ Build Tools & Environment

1. **[Vite, Webpack, CRA, Next.js](10.%20Build%20Tools%20%26%20Environment/01.%20Vite%2C%20Webpack%2C%20CRA%2C%20Next.js.md)**

   - Comparison of bundlers and framework-specific tooling

2. **[ESLint, Prettier, Husky, Lint-staged](10.%20Build%20Tools%20%26%20Environment/02.%20ESLint%2C%20Prettier%2C%20Husky%2C%20Lint-staged.md)**

   - Linting, formatting, and pre-commit automation

3. **[Environment Variables](10.%20Build%20Tools%20%26%20Environment/03.%20Environment%20Variables.md)**

   - Managing env vars across environments and secrets handling

4. **[Performance Profiling & Dev Tools](10.%20Build%20Tools%20%26%20Environment/04.%20Performance%20Profiling%20%26%20Dev%20Tools.md)**

   - Profiling tools and devtool tips for performance debugging

### 🧩 Advanced Patterns & Architecture

1. **[Render Props](11.%20Advanced%20Patterns/01.%20Render%20Props.md)**

   - Passing render logic to components for flexible UI

2. **[Higher Order Components (HOCs)](11.%20Advanced%20Patterns/02.%20Higher%20Order%20Components%20%28HOCs%29.md)**

   - HOC patterns and trade-offs compared to hooks

3. **[Compound Components](11.%20Advanced%20Patterns/03.%20Compound%20Components.md)**

   - Building flexible component APIs with composition

4. **[Controlled vs Uncontrolled Components (Advanced)](11.%20Advanced%20Patterns/04.%20Controlled%20vs%20Uncontrolled%20Components.md)**

   - Advanced forms of control and state synchronization

5. **[State Reducers](11.%20Advanced%20Patterns/05.%20State%20Reducers.md)**

   - Using reducer patterns to manage complex component state

### 🏗️ Architecture & Design

1. **[Component Design Principles](12.%20Architecture%20%26%20Design/01.%20Component%20Design%20Principles.md)**

   - Reusability, composition, and separation of concerns

2. **[State Management Patterns](12.%20Architecture%20%26%20Design/02.%20State%20Management%20Patterns.md)**

   - Context API, Redux, and Zustand

3. **[API Design & Integration](12.%20Architecture%20%26%20Design/03.%20API%20Design%20%26%20Integration.md)**

   - REST vs GraphQL, and data fetching strategies

4. **[Performance Optimization](12.%20Architecture%20%26%20Design/04.%20Performance%20Optimization.md)**

   - Code splitting, lazy loading, and memoization

5. **[Testing Strategies](12.%20Architecture%20%26%20Design/05.%20Testing%20Strategies.md)**

   - Unit testing, integration testing, and end-to-end testing

### ⚡ Next.js

1. **[SSR, SSG, ISR in Next.js](13.%20Next.js/01.%20SSR%2C%20SSG%2C%20ISR%20in%20Next.js.md)**

   - Server-side rendering, static generation, and incremental static regeneration patterns in Next.js

2. **[File-based Routing in Next.js](13.%20Next.js/02.%20File-based%20Routing%20in%20Next.js.md)**

   - Pages, dynamic routes, and nested folders using the file-system router

3. **[App Router (Next.js 13+)](13.%20Next.js/03.%20App%20Router%20%28Next.js%2013%2B%29.md)**

   - New App Router concepts: layouts, server components, and streaming

4. **[API Routes in Next.js](13.%20Next.js/04.%20API%20Routes%20in%20Next.js.md)**

   - Building backend endpoints inside a Next.js app and deploying serverless functions

5. **[Middleware in Next.js](13.%20Next.js/05.%20Middleware%20in%20Next.js.md)**

   - Edge middleware, request handling, and redirects

6. **[Authentication (next-auth)](13.%20Next.js/06.%20Authentication%20%28next-auth%29.md)**
   - Implementing authentication with next-auth and session strategies

### 🧭 Soft Skills & System Design

1. **[Making Architectural Decisions](14.%20Soft%20Skills%20%26%20System%20Design/01.%20Making%20Architectural%20Decisions.md)**

   - How to reason about architecture choices and justify trade-offs in interviews

2. **[Mentoring Juniors](14.%20Soft%20Skills%20%26%20System%20Design/02.%20Mentoring%20Juniors.md)**

   - Best practices for onboarding, feedback, and growth conversations

3. **[Code Reviews](14.%20Soft%20Skills%20%26%20System%20Design/03.%20Code%20Reviews.md)**

   - How to give actionable feedback and keep reviews efficient and respectful

4. **[Discussing Trade-offs (e.g., Redux vs Context, SSR vs CSR)](14.%20Soft%20Skills%20%26%20System%20Design/04.%20Discussing%20Trade-offs%20%28e.g.%2C%20Redux%20vs%20Context%2C%20SSR%20vs%20CSR%29.md)**

   - Framing trade-offs and explaining technical decisions concisely

5. **[System Design Basics: Structuring a Scalable React App](14.%20Soft%20Skills%20%26%20System%20Design/05.%20System%20Design%20Basics%3A%20Structuring%20a%20Scalable%20React%20App.md)**
   - High-level patterns for scalable front-end architectures and data flows

## 🎯 Interview Tips

### Key areas (what interviewers expect)

- Core React: hooks (useState, useEffect, useRef, useMemo/useCallback) and lifecycle equivalents
- Component design: composition, single-responsibility, controlled vs uncontrolled patterns
- Performance: memoization, virtualization, avoiding unnecessary re-renders, code-splitting
- State management: Context API, Redux/Toolkit, and modern lightweight stores (Zustand, Recoil)
- Routing & Next.js: client vs server rendering, file-based routing, App Router basics, API routes
- Data fetching: REST vs GraphQL, React Query/SWR, caching, pagination, and error/loading states
- Testing: unit/component/integration testing with Jest, React Testing Library, and MSW
- TypeScript: typing props, generics, discriminated unions, and utility types
- Soft skills & design: communicating trade-offs, writing clear PRs, and system-design basics for frontends

### Study strategy (how to practice)

1. Read the core topics in this repo in order: Core React → State Management → Routing → API Integrations → Testing.
2. Build 2–3 small focused apps that exercise multiple areas (e.g., a CRUD app with forms, client-side caching, and tests).
3. Add performance improvements iteratively: measure with React DevTools Profiler, then apply memoization or virtualization where needed.
4. Write tests for critical flows: unit tests for utils/hooks, component tests for UI, and integration tests for page-level flows using MSW.
5. Practice explaining trade-offs out loud: five-minute explanations of choices (e.g., Redux vs Context, SSR vs CSR).

### Practical checklist (ready-to-show answers/code)

- [ ] Explain useEffect with dependency arrays and common pitfalls (stale closures, missing deps)
- [ ] Demonstrate controlled vs uncontrolled inputs and when to use each
- [ ] Describe memoization patterns (React.memo, useMemo, useCallback) and when they're beneficial
- [ ] Compare state management options and pick one for a given scenario (justify choice)
- [ ] Show a small data-fetching example using React Query or SWR with caching and error handling
- [ ] Write a component test with React Testing Library and a mocked API using MSW
- [ ] Type a small component with generics or utility types and explain the trade-offs
- [ ] Walk through a simple frontend system-design diagram for a scalable React app (data flow, caching layer, state boundaries)

## 🛠️ How to Use This Repository

1. Pick a learning path: follow the Table of Contents in order (Core React → State Management → Routing → API Integrations → Testing).
2. For each topic, open the linked markdown file, read the explanation, run any example code locally, then try the short exercises.
3. Build small projects that combine topics (e.g., a Next.js CRUD app that uses React Query, Redux or Zustand, and has unit + integration tests).
4. Use the Practical checklist above to create small, demonstrable artifacts you can show in interviews (code snippets, tests, design diagrams).
5. Add your notes or corrections directly into the topic files — filenames contain spaces, so use your editor's file open dialog or click links from this README.

## 📝 Notes

- This repository uses modern React (functional components + hooks).
- Files are organized by topic folders; links in this README are percent-encoded to work with filenames that contain spaces and special characters.
- If you prefer, rename files to simpler names (no spaces) and update links here — I can do that automatically if you want.
- Contributions, issues, and PRs are welcome — follow standard GitHub flow (fork → branch → PR) and include short descriptions of any added examples or corrections.

---

Happy Learning! 🚀

_This repository is designed to help you prepare for React interviews by combining conceptual notes, practical examples, and hands-on exercises._
