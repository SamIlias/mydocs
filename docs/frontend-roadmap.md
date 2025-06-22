# ✅ Frontend Roadmap

### Must-read Books

- [x] **Стив Макконнелл** — _Совершенный код_
- [x] **В.Ф.Фило Феррейра** — _Теоретический минимум по Computer Science: Сети, криптография и Data Science_
- [x] **В.Ф.Фило Феррейра** — _Теоретический минимум по Computer Science: Всё, что нужно знать программисту_
- [x] **Адитья Бхаргава** — _Грокаем алгоритмы_
- [x] **Чарльз Петцольд** — _Код. Тайный язык компьютерного аппаратного и программного обеспечения_
- [ ] **Роберт Мартин** — _Чистый код. Создание, анализ и рефакторинг_
- [ ] **Роберт Мартин** — _Чистая архитектура. Искусство разработки программного обеспечения_
- [ ] **Эрик Эванс** — _Предметно-ориентированное проектирование. Структуризация сложных программных систем_
- [ ] **Chip Huyen** - _AI Engineering. Building Applications with Foundation Models_

## 1. Fundamentals of Programming and basic tools

### Data Types

- [x] Primitive types (numbers, strings, booleans)
- [x] Compound types (arrays, objects, structs)
- [x] Reference vs. value types
- [x] Static vs. dynamic typing

### Variables and Scope

- [x] Variable declaration and naming
- [x] Scope (global, local, block)
- [x] Variable lifecycle
- [x] Closures

### Operators and Expressions

- [x] Arithmetic operators
- [x] Logical operators
- [x] Comparison operators
- [x] Ternary operator and conditional expressions

### Control Flow

- [x] Conditional statements (if, else, switch)
- [x] Loops (for, while, do while, for...of)
- [x] Control keywords (break, continue, return)

### Functions

- [x] Function declaration and invocation
- [x] Parameters and return values
- [x] Default parameters
- [x] Pass by value vs. pass by reference
- [x] Recursion

### Basic Data Structures

- [x] Arrays and collections
- [x] Dictionaries / hash maps / objects
- [x] Stack and queue (basic understanding)

### Algorithmic Thinking

- [x] Sequence → Branching → Loop
- [x] Task decomposition
- [x] Pseudocode writing
- [x] Basic optimization techniques

### Error Handling

- [x] try/catch/finally
- [x] Exceptions

### Programming Paradigms

- [x] Imperative programming
- [x] Object-oriented basics (objects, classes, inheritance)
- [x] Functional programming basics (pure functions, higher-order functions, immutability)

### Code Quality Principles

- [x] Readability and clarity
- [x] Reusability (SOLID, DRY, KISS)
- [x] Commenting and documentation

### Development Environment

- [x] Running code (compilation, interpretation)
- [x] Using code editors (e.g., VS Code, terminal)
- [x] Basic debugging techniques (console.log, breakpoints)

### Basic tools

<!-- prettier-ignore -->
- [x] HTML:
    - [x] Structure
    - [x] Semantics
    - [x] Forms
- [x] CSS:
    - [x] Selectors
    - [x] Cascade
    - [x] Positioning
    - [x] Flexbox
    - [x] Grid
- [x] JavaScript Basics
    - [x] Variables and types
    - [x] Loops and conditionals
    - [x] Functions

---

## 2. Advanced JavaScript

### Core Concepts:

- [x] DOM manipulation
- [x] Events
- [x] `this`
- [x] Hoisting

### Async Programming:

- [x] Callbacks
- [x] Promises
- [x] Async/await

### Modules and Bundling:

- [x] ESModules
- [x] CommonJS

### Browser APIs:

- [x] Fetch
- [x] localStorage / sessionStorage
- [x] History API
- [ ] Clipboard / Geolocation

---

## 3. Developer Tools

### Git:

<!-- prettier-ignore -->
- [x] Standard Git features (init, clone, commit, push, pull)
- [x] Branching, merging, rebasing
- [x] Revert, reset, stash
- [x] Amend
- [ ] Worktree
- [ ] Dangerous but useful:
    - [x] HEAD manipulations
    - [ ] Cherry-picking
    - [ ] Force push (when and why)

### GitHub:

- [x] Pull requests and code reviews
- [x] GitHub Projects / Issues

### Frontend Dev Workflow Tools:

- [x] Webpack / Vite dev mode
- [x] React Developer Tools
- [ ] Lighthouse / Web Vitals in Chrome DevTools
- [x] Prettier, ESLint

### Terminal & NPM:

- [x] CLI basics (cd, mkdir, touch, ls, etc.)
- [x] npm / yarn commands
- [x] Understanding `package.json` structure

### Common Tools:

- [ ] Postman (API testing)
- [ ] OpenAPI / Swagger (API specification)

---

## 4. Modern CSS

### Preprocessors:

- [x] Sass / SCSS

### Methodologies:

- [ ] BEM
- [ ] Atomic CSS
- [ ] OOCSS

### Utility-first CSS:

- [x] Tailwind CSS

### Responsive Design:

- [x] Media queries
- [x] Mobile-first approach

---

## 5. React Basics

- [x] JSX
- [x] Functional components
- [x] Props and state
- [x] useState / useEffect
- [x] Conditional rendering
- [x] Forms and event handling
- [x] Lifting state up
- [x] Prop drilling
- [x] Component folder structures (e.g. FSD)

---

## 6. Advanced React

### Hooks:

- [x] useContext
- [x] useRef
- [x] useMemo / useCallback

### Routing:

- [x] React Router

### Custom Hooks:

- [x] Encapsulate side effects and logic

### State Management:

- [x] Redux (Toolkit)
- [x] Zustand
- [ ] RTK Query / React Query

---

## 7. Testing

### Unit Testing:

- [x] Jest basics
- [x] Mocking and spies

### Component Testing:

- [x] React Testing Library

### E2E Testing:

- [ ] Cypress / Playwright

---

## 8. Build Tools

- [x] Webpack
  - [x] Loaders (babel-loader, css-loader)
  - [x] DevServer
  - [ ] Optimization (tree shaking, code splitting)
- [x] Vite
  - [x] HMR (Hot Module Replacement)
  - [x] Plugin system
- [x] Babel
- [x] PostCSS
- [ ] Bundle analysis tools (e.g., webpack-bundle-analyzer)

---

## 9. Deployment

### Containerization:

- [ ] Docker
  - [ ] Multi-stage Dockerfile
  - [x] Containers

### CI/CD pipelining:

- [ ] GitHub Actions
  - [x] Build/lint/test workflows
  - [ ] Automatic deployments

### Lightweight platforms:

- [ ] Vercel
  - [ ] GitHub integration
  - [ ] Env vars and preview builds
- [ ] Netlify
  - [ ] Deployment configuration
  - [ ] Redirects and headers

### Static deployment:

- [x] GitHub Pages
  - [x] gh-pages branch
  - [x] mkdocs gh-deploy

### Configuration:

- [x] `.env` files
- [ ] Secret management in CI/CD

### Performance:

- [ ] Lighthouse audits
- [ ] Core Web Vitals

---

## 10. Patterns & Architecture

- [ ] Separation of concerns
- [ ] Reusable and modular components
- [x] Feature-Sliced Design (FSD)
- [x] Module aliasing (`@shared`, `@entities`, etc.)

---

## 11. Advanced Topics

- [ ] SSR / SSG: Next.js or Remix
- [x] i18n (i18next)
- [x] Accessibility (a11y)
- [ ] Web security basics (XSS, CSRF, CORS)
- [ ] PWA (Progressive Web Apps)

---

## 12. Portfolio & Career Growth

### Projects:

- [x] Clean README files
- [x] Project using external API
- [x] Project using state manager
- [x] Project using AI

### Growth:

- [ ] Contribute to open source
- [x] Documented personal roadmap (e.g., MkDocs)
