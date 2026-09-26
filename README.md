# larpra

> **100% vibe-coded.** This project was built through vibe coding and is released as an open-source project.
> Contributions, experiments, fixes, and improvements are welcome.

A modern, from-scratch Operations Research lab for the browser — a spiritual (not code or
branding) replacement for TORA-style university OR labs. Every algorithm is reimplemented from
first principles; nothing here is copied from TORA.

**Milestone 1** (Linear Programming: graphical method + two-phase simplex), **Milestone 2**
(Transportation: NW Corner/Least Cost/VAM + MODI), **Assignment** (Hungarian algorithm),
**Network & Routing** (Dijkstra shortest path, Kruskal/Prim minimum spanning tree, Edmonds-Karp
maximum flow), **Traveling Salesman** (Nearest Neighbor heuristic + exact Branch and Bound),
**CPM / PERT** (forward and backward passes, slack, every critical path, PERT expected durations
and project variance), **Integer Programming** (exact Branch and Bound reusing the simplex
engine), **Queuing Models** (M/M/1 and M/M/c, exact Erlang-C/B formulas), **Game Theory**
(two-player normal-form games: best responses, pure equilibria, iterated dominance, zero-sum
minimax LPs, and every mixed Nash equilibrium by exact support enumeration), and **Matrix / Linear
Equations** (Gaussian elimination and back-substitution, cofactor-expansion determinants,
Gauss-Jordan inverses, rank and nullspace, and eigenvalues/eigenvectors for small matrices, all in
exact fractions) are implemented and tested. All ten dashboard modules are complete as of
Milestone 10.

## Running it

```bash
npm install
npm run dev       # starts Vite on http://localhost:5173
```

```bash
npm run build      # type-checks (tsc -b) and produces a static build in dist/
npm run preview    # serve that build locally
```

## Running the tests

```bash
npm test           # runs the vitest suite once
npm run test:watch # watch mode
```

See the full test coverage and module documentation below.

## Open source

This repository is open source and released under the MIT License. See `LICENSE` for details.

## Vibe coding

This project is **100% vibe-coded** — built through iterative prompting, experimentation, and AI-assisted development.
