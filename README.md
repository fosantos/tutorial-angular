# Angular 17+ Senior Engineer Fast-Track

This repository contains a zero-fluff, architecture-first guide designed for senior engineers transitioning to modern Angular (17+) from other component-based ecosystems like React or Vue.

The main content is available in the interactive [index.html](file:///C:/projetos/tutorial-angular/index.html) file.

## 🚀 Objectives
* **Fast Transition:** Reach 80% daily productivity by learning the 20% of Angular that matters most in modern enterprise environments.
* **Modern API Focus:** Avoid legacy `NgModule` paradigms and learn strictly standalone components, functional guards, signals, and the `inject()` framework.
* **Architectural Depth:** Master Angular's hierarchical dependency injection (DI) tree, reactivity models (Zone.js vs. Signals), and custom caching/data access resource designs.

---

## 📖 Key Topics Covered

### 1. Core Architecture Breakdown
* **The Component & Injector Trees:** Visualizing how Angular runs two parallel trees.
* **Mental Model Shift:** A direct comparison table mapping React/Vue concepts (hooks, state, side effects) to Angular equivalents (signals, DI, effects).
* **Modern Building Blocks:** Standalone components, custom attribute directives, and the modern `inject()` functional paradigm.
* **Dependency Injection (DI):** Explaining the resolution algorithm and parent/child injector overrides.
* **Reactivity:** Comparing Zone.js change detection vs. fine-grained Signals reactivity.

### 2. Project Bootstrapping & Monorepos
* Scaffolding modern workspaces using `@angular/cli`.
* Exploring critical configurations (`angular.json` and strict type checks in `tsconfig.json`).
* Monorepo alias routing with tsconfig path mapping.
* Production bundle budgets configuration and build optimization patterns.

### 3. The 80/20 Toolkit
* **Reactive Forms:** Strictly-typed form models, custom cross-field validation, and building dynamic schema-driven form engines.
* **Routing & Navigation:** Flat routing, functional guards, route parameter signal bindings, and custom hover-based preloading strategies.
* **HTTP Client:** Functional interceptor mesh, caching interceptors, request deduplication, and signal-based API resources (`ApiResource<T>`).

---

## 🛠️ Hands-on Challenges / Exercises Included
The guide contains practical exercises designed to test your knowledge of advanced topics:
1. **Architectural Refactor & DI Hierarchy:** Migrating a legacy module-based app to lazy-loaded standalones.
2. **Production Workspace Configuration:** Enforcing strict budgets, custom brotli-compressed builds, and design system path mappings.
3. **Dynamic Schema-Driven Form Engine:** Building a conditional visibility form engine with async state validation.
4. **Permission-Based Route Fabric:** Designing functional guards and runtime route filters based on user roles.
5. **Signal-Based API Resource with Interceptor Mesh:** Designing a visible-only auto-refresh CRUD layer with cache TTL and optimistic updates.

---

## 💻 How to View the Guide
Simply open the [index.html](file:///C:/projetos/tutorial-angular/index.html) file in any web browser to read the guide and start coding:
```bash
# Double click index.html or open it via terminal (on Windows):
start index.html
```

---
*Created as a training reference for senior engineers scaling Angular application architectures.*
