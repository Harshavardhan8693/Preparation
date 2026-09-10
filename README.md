# Product Company Preparation

## Repository Structure

```
Preparation/
├── DSA/
│   ├── Notes/              ← topic notes and cheat sheets
│   ├── Resources/          ← PDFs, reference material
│   └── Problems/           ← solutions organised by pattern
│       ├── Arrays/
│       ├── Strings/
│       ├── Hashing/
│       ├── TwoPointers/
│       ├── SlidingWindow/
│       ├── BinarySearch/
│       ├── Stack-Queue/
│       ├── LinkedList/
│       ├── Trees/
│       ├── Heaps/
│       ├── Graphs/
│       ├── Recursion-Backtracking/
│       ├── DynamicProgramming/
│       └── Greedy/
├── Java/
│   ├── Notes/
│   ├── Resources/          ← PDFs, Effective Java, JVM diagrams
│   ├── Code/
│   │   ├── OOP/
│   │   ├── Collections/
│   │   ├── Streams-Lambdas/
│   │   ├── Concurrency/
│   │   └── ModernJava/
│   └── InterviewPrep/
├── JavaScript/
│   ├── Notes/
│   ├── Resources/          ← MDN cheat sheets, JS guides
│   ├── Code/
│   │   ├── Fundamentals/
│   │   ├── CoreJS/
│   │   ├── AsyncJS/
│   │   └── NodeJS/
│   ├── Projects/           ← small practice projects
│   └── InterviewPrep/
├── SystemDesign/
│   ├── Notes/
│   ├── Resources/          ← architecture diagrams, PDFs
│   └── Cases/              ← individual system design write-ups
├── Selenium/
│   ├── Notes/
│   ├── Resources/
│   └── Code/
├── Playwright/
│   ├── Notes/
│   ├── Resources/
│   └── Code/
├── AI-Automation/
│   ├── Notes/
│   └── Resources/
├── CI-CD/
│   ├── Notes/
│   └── Resources/
├── DailyLogs/              ← one file per study day (YYYY-MM-DD.md)
└── MockInterviews/         ← notes from mock sessions
```

---

## Goal

Become interview-ready for a strong product-based company by building depth in:

- DSA
- Java
- JavaScript
- System Design
- Software Engineering
- AI / Automation / CI-CD

The objective is not to learn everything from scratch. The objective is to revive existing knowledge, close gaps, build problem-solving ability, and become interview-ready through consistent execution.

---

## Current Baseline

| Area | Current State | Strategy |
|---|---|---|
| DSA | Previously learned, currently rusty | Revive fundamentals → patterns → interview problems |
| Java | Previously strong foundation, currently rusty | Refresh → deepen → interview-level Java |
| JavaScript | Beginner / new | Start from fundamentals → core JS → practical development |
| System Design | Good conceptual exposure | Refresh and develop interview communication |
| AI / Automation / CI-CD | Practical POC experience | Strengthen as an engineering differentiator |

> **Important:** Do not restart Java or DSA from absolute zero. The goal is to reactivate existing knowledge quickly and identify actual gaps. JavaScript is different — it is a new skill and should be learned properly from fundamentals.

---

## Study Strategy

**Daily Target:** 2.5–3 hours/day

**Weekly Structure:**
- 6 focused study days
- 1 review/rest day
- 70% hands-on, 30% learning/theory

**Priority Split:**
1. DSA — 45%
2. Java — 30%
3. JavaScript — 25%

System Design and engineering topics will be layered in as the foundation becomes stronger.

---

## Resources

### DSA
- [NeetCode Roadmap](https://neetcode.io/roadmap) — structured problem set, highly recommended
- [LeetCode](https://leetcode.com) — primary practice platform
- Blind 75 problem list — must-solve for product company interviews

### Java
- [Java 17+ docs](https://docs.oracle.com/en/java/javase/17/docs/api/) — reference for APIs
- Effective Java (Joshua Bloch) — for depth, not memorization

### JavaScript
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript) — definitive reference
- [javascript.info](https://javascript.info) — best free resource for learning JS from scratch
- [Node.js docs](https://nodejs.org/en/docs) — for backend JS

---

## Week 1 — Reset & Momentum

### Day 1

**DSA**
- Big-O analysis
- Arrays and Strings
- Find min/max
- Frequency counting
- Prefix sums

**Java**
- Classes, Objects, Methods
- Core collections refresh (List, Set, Map at a high level)

**JavaScript**
- `var`, `let`, `const` — differences and when to use each
- Primitive types: string, number, boolean, null, undefined, symbol
- `typeof`, type coercion basics
- Basic functions and arrow functions

---

### Day 2

**DSA**
- Hashing
- HashMap / frequency counting
- Basic hashing problems

**Java**
- `ArrayList`, `LinkedList`, `HashSet`, `HashMap` — when to use each
- Iterating collections

**JavaScript**
- Arrays — creation, indexing, `push`, `pop`, `shift`, `unshift`, `splice`, `slice`
- Objects — creation, property access (dot vs bracket), `Object.keys()`, `Object.values()`
- Template literals and string interpolation

---

### Day 3

**DSA**
- Two pointers
- Sorted-array problems
- String problems

**Java**
- OOP: Encapsulation, Inheritance, Polymorphism, Abstraction
- `abstract` class vs `interface`

**JavaScript**
- Functions: declarations vs expressions vs arrow functions
- Callbacks
- Scope: `var` function scope vs `let`/`const` block scope
- Hoisting basics

---

### Day 4

**DSA**
- Sliding window
- Fixed-size window
- Variable-size window

**Java**
- Generics
- `Comparable` vs `Comparator`
- Exception handling: checked vs unchecked, `try-catch-finally`

**JavaScript**
- `map()`, `filter()`, `reduce()`
- `find()`, `some()`, `every()`, `flat()`, `flatMap()`
- Destructuring: arrays and objects
- Spread (`...`) and Rest parameters

---

### Day 5

**DSA**
- Stack
- Queue
- Monotonic stack introduction

**Java**
- Lambdas and functional interfaces (`Predicate`, `Function`, `Consumer`, `Supplier`)
- Streams: `filter`, `map`, `collect`, `sorted`, `distinct`
- `Optional`

**JavaScript**
- Closures — what they are and why they matter
- `this` keyword — how it behaves in different contexts
- Promises basics
- `async/await`

---

### Day 6

**DSA**
- Mixed interview problems
- Review mistakes
- Timed problem solving (20–25 min per problem)

**Java**
- Interview-oriented coding exercises
- Write at least 2 problems from scratch without reference

**JavaScript**
- Build a small console-based program (e.g., a todo list or word frequency counter)

---

### Day 7 — Review / Rest

- Review mistakes from the week
- Identify weak topics
- Update revision queue
- No heavy new learning

---

## Week 2 — Depth & Patterns

### Day 1

**DSA**
- Binary Search: standard, on answer, rotated arrays

**Java**
- String manipulation: `StringBuilder`, `charAt`, `substring`, `indexOf`, `split`, `trim`
- String immutability and the String pool

**JavaScript**
- Prototypes and prototype chain
- `class` syntax, constructors, `extends`, `super`
- Modules: `import` / `export`

---

### Day 2

**DSA**
- Linked List: singly linked list operations (insert, delete, reverse)
- Slow and fast pointer pattern

**Java**
- `equals()` and `hashCode()` contract
- `Comparable` and custom sorting
- `Collections.sort()`, `Arrays.sort()`

**JavaScript**
- Event loop, call stack, microtask queue, macrotask queue
- Execution context and scope chain
- `setTimeout`, `setInterval` behavior

---

### Day 3

**DSA**
- Linked List problems: cycle detection, merge two sorted lists, find middle
- Stack problems: valid parentheses, min stack

**Java**
- Streams: groupingBy, partitioningBy, toMap, joining
- Method references: `Class::method`, `instance::method`

**JavaScript**
- Promise chaining
- `Promise.all`, `Promise.allSettled`, `Promise.race`, `Promise.any`
- Error handling with `async/await` using `try/catch`

---

### Day 4

**DSA**
- Binary Trees: traversals (inorder, preorder, postorder) — iterative and recursive
- BFS and DFS on trees

**Java**
- Multithreading basics: `Thread`, `Runnable`, `Callable`
- `synchronized`, `volatile`

**JavaScript**
- Browser fundamentals: DOM, `document.querySelector`, event listeners
- `fetch` API and working with JSON responses
- `null` vs `undefined`, nullish coalescing (`??`), optional chaining (`?.`)

---

### Day 5

**DSA**
- Binary Search Trees: insert, search, delete, validate BST
- Heaps and Priority Queue: min-heap, max-heap, `k` largest/smallest

**Java**
- `ExecutorService`, thread pools
- `Future`, `CompletableFuture` basics

**JavaScript**
- Node.js: what it is and how it differs from browser JS
- `require` vs `import/export` (CommonJS vs ESM)
- Basic file I/O with `fs` module

---

### Day 6

**DSA**
- Mixed problems: binary search, linked list, tree
- Timed practice: 2 problems in 45 minutes

**Java**
- Full mock problem: implement a data structure or algorithm from scratch

**JavaScript**
- Build a small Node.js script: read a file, process data, write output

---

### Day 7 — Review / Rest

- Review all week mistakes
- Update revision queue
- Identify the 2–3 weakest areas to focus on next week

---

## Progress Tracker

| Week | DSA | Java | JavaScript | Status |
|---|---|---|---|---|
| Week 1 | Fundamentals + basic patterns | Core refresh | Fundamentals | ⬜ |
| Week 2 | Linked List + Binary Search + Trees | Collections + Strings + Modern Java | Core JS + Async | ⬜ |
| Week 3 | Heaps + Recursion + Backtracking | Streams + JVM basics + Concurrency | Browser + Node.js | ⬜ |
| Week 4 | Graphs: BFS, DFS, Dijkstra | Advanced Java + interview questions | REST APIs + Express | ⬜ |
| Week 5+ | Greedy + Dynamic Programming | Full interview prep | Practical development | ⬜ |

---

## DSA Roadmap

### Phase 1 — Foundations
- Big-O analysis
- Arrays and Strings
- Hashing
- Prefix Sum
- Sorting: Bubble, Selection, Insertion, Merge Sort, Quick Sort (understand, don't memorize)

### Phase 2 — Core Patterns
- Two Pointers
- Sliding Window
- Binary Search
- Stack and Queue
- Monotonic Stack

### Phase 3 — Data Structures
- Linked Lists
- Trees and Binary Search Trees
- Heaps and Priority Queue
- Tries (optional but useful)

### Phase 4 — Advanced Problem Solving
- Recursion
- Backtracking
- Graphs: BFS, DFS, topological sort, union-find
- Greedy
- Dynamic Programming: 1D, 2D, knapsack, subsequences

### Phase 5 — Stretch Topics
- Bit manipulation
- Intervals
- Math-based problems

---

## DSA Problem Log

Every important problem should be recorded using this structure:

```
Problem:
Pattern:
Platform + link:

Brute Force:
Optimal Approach:

Time Complexity:
Space Complexity:

What I initially thought:
What I missed:
Similar problems:

Key takeaway:
```

The objective is not just to count solved problems. Mistakes and patterns matter more than the raw number.

---

## Java Roadmap

### Phase 1 — Core Java
- OOP: classes, objects, interfaces, abstract classes
- Collections: List, Set, Map, Queue, Deque
- Generics
- Exceptions: checked vs unchecked, custom exceptions
- Strings: immutability, String pool, `StringBuilder`, common methods
- `equals()`, `hashCode()`, `Comparable`, `Comparator`

### Phase 2 — Modern Java (Java 8–17+)
- Lambdas and functional interfaces
- Streams API
- `Optional`
- Method references
- Records (Java 16+)
- Sealed classes (Java 17+)

### Phase 3 — Interview Depth
- JVM architecture: heap, stack, metaspace
- Garbage Collection: types, tuning basics
- Java Memory Model
- Multithreading: `Thread`, `Runnable`, `Callable`, `Future`
- Concurrency: `synchronized`, `volatile`, `ReentrantLock`
- `ExecutorService`, thread pools, `CompletableFuture`
- Common Java interview questions

---

## JavaScript Roadmap

### Phase 1 — Fundamentals
- Variables (`var`, `let`, `const`), scope, hoisting
- Data types: primitives and objects
- Type coercion, `typeof`, `==` vs `===`
- Operators: arithmetic, logical, ternary, nullish coalescing (`??`)
- Optional chaining (`?.`)
- Control flow: conditionals, loops
- Functions: declarations, expressions, arrow functions
- Arrays and Objects
- Destructuring, Spread, Rest
- Template literals

### Phase 2 — Core JavaScript
- Scope chain and closures
- `this` keyword and binding (`call`, `apply`, `bind`)
- Prototypes and prototype chain
- Classes: `class`, `extends`, `super`, `static`
- Modules: `import` / `export`
- Event loop, call stack, microtask queue
- Execution context

### Phase 3 — Asynchronous JavaScript
- Callbacks and callback hell
- Promises: creation, chaining, `.then()`, `.catch()`, `.finally()`
- `Promise.all`, `Promise.allSettled`, `Promise.race`, `Promise.any`
- `async/await`
- Error handling in async code
- `fetch` API

### Phase 4 — Practical JavaScript
- Browser fundamentals: DOM, events, event delegation
- HTTP basics
- Node.js: event loop, modules, `fs`, `path`
- `npm` and package management
- Express.js basics
- Building REST APIs

---

## System Design

System design is not starting from zero. Focus on converting existing conceptual understanding into strong interview performance.

### Topics
- Requirements gathering: functional vs non-functional requirements
- Scalability, Availability, Reliability
- CAP theorem
- Load balancing
- Caching strategies
- Databases: SQL vs NoSQL, indexing, sharding
- Message queues and event-driven architecture
- Microservices
- API design: REST, rate limiting, versioning
- Authentication and authorization
- Observability: logging, metrics, tracing
- Distributed systems fundamentals

### Interview Framework

For every system design problem, go through:

1. Requirements (functional + non-functional)
2. Scale estimation
3. API design
4. High-level architecture
5. Data storage and schema
6. Caching layer
7. Messaging / async flows
8. Scaling strategy
9. Failure handling
10. Bottlenecks and trade-offs

---

## Engineering Advantage

Maintain and strengthen practical engineering knowledge around:

- AI automation
- CI/CD
- Test automation
- API automation
- DevOps concepts
- Cloud fundamentals
- Observability
- Deployment strategies

The existing AI automation CI/CD POC should eventually become part of the interview/project discussion.

---

## Interview Preparation Roadmap

### Stage 1 — Foundation Revival
- [ ] Refresh DSA fundamentals
- [ ] Refresh Java fundamentals
- [ ] Learn JavaScript fundamentals
- [ ] Establish daily coding habit

### Stage 2 — Problem Solving
- [ ] 25 DSA problems
- [ ] 50 DSA problems
- [ ] 75 DSA problems
- [ ] 100 DSA problems

Focus on understanding patterns rather than blindly increasing the count.

### Stage 3 — Technical Depth
- [ ] Advanced DSA
- [ ] Java interview preparation
- [ ] JavaScript interview preparation
- [ ] System design revision
- [ ] Engineering fundamentals

### Stage 4 — Interview Mode
- [ ] Timed DSA practice
- [ ] Java coding rounds
- [ ] JavaScript coding rounds
- [ ] System design mock interviews
- [ ] Full mock interviews (platform or with a peer)
- [ ] Resume and project preparation
- [ ] Begin product-company applications

---

## Daily Progress Log

Use this format every study day:

```
## YYYY-MM-DD

### DSA
Topics:
Problems solved:
Problems struggled with:
Mistakes:

### Java
Topics:
Coding completed:
Weak areas:

### JavaScript
Topics:
Coding completed:
Questions:

### Key Learning

### Revision Required

### Tomorrow
```

---

## Revision Queue

### DSA
- [ ]

### Java
- [ ]

### JavaScript
- [ ]

### System Design
- [ ]

### Interview Mistakes
- [ ]

---

## Milestones

- [ ] Complete Week 1
- [ ] Complete Week 2
- [ ] Complete Week 3
- [ ] Complete Week 4
- [ ] Solve first 25 DSA problems
- [ ] Solve first 50 DSA problems
- [ ] Solve first 100 DSA problems
- [ ] Refresh Java core
- [ ] Complete JavaScript fundamentals
- [ ] Build first JavaScript project
- [ ] Complete advanced DSA
- [ ] Complete Java interview revision
- [ ] Complete JavaScript interview revision
- [ ] Refresh system design
- [ ] Practice mock interviews
- [ ] Start product-company applications

---

## Rules

1. Don't restart from zero.
2. Code more than you watch.
3. Attempt every DSA problem before looking at the solution.
4. Track mistakes, not just solved problems.
5. Don't endlessly redesign the study plan.
6. JavaScript starts from fundamentals because it is new.
7. Repeated mistakes go into the revision queue.
8. Review weak topics at least once a week.
9. Prefer understanding over memorization.
10. Consistency beats occasional marathon sessions.
11. Build practical projects alongside interview preparation.
12. Don't wait until you feel "fully ready" before starting applications.

---

## Core Philosophy

> Think deeply, but don't overthink execution. When the next useful action is clear, do it.

The goal is not to become perfect before interviewing.

The goal is to become consistently better, technically strong, and interview-ready.

---

## AI Assistant + GitHub Workflow

This repository is the source of truth for preparation progress.

When working with an AI assistant (Claude, ChatGPT, etc.):

- Share this README to establish context
- Update progress after meaningful study sessions
- Record important DSA mistakes in the problem log
- Add weak topics to the revision queue
- Update milestones as they are completed
- Adjust the roadmap based on actual progress rather than constantly redesigning it

**Daily prompt to use:**

> "Give me today's preparation plan based on my GitHub README. Consider my current progress, weak areas, previous mistakes, and where I am in the DSA / Java / JavaScript roadmap."

---

## Final Objective

Become strong enough to confidently target product-based software engineering roles, with:

**Strong DSA + Strong Java + Practical JavaScript + System Design + Real Engineering Experience**

Transition from preparation mode into actual interview mode and applications when technically ready — not when you feel perfectly ready.
