# Axioms & Rules — Minor/Major Cosmology + Global Replay (v1)

> **Status:** Speculative framework note (non‑standard cosmology).  > **Goal:** Consolidate Axioms + Rules, integrate **R3 + P1**, define **Commit Frontier**, and connect replay semantics to **Undetectability of M**.

## 0) Notation & Objects

### 0.1 Two notions of time
- **t** — a *finite* directed segment (a “frame interval”) with a **beginning** and an **end**.
- **T** — the **immutable record** / archive defined as a **collection of** realized *t* segments.

### 0.2 The active global process
- **t₀** — the *global* time process currently running (the “live simulation”).
- **k** — the latest **committed segment index** of t₀ that has been written into T.

### 0.3 Spaces
- **M (Space Major)** — centerless, information‑silent meta‑domain.
- **m (Space Minor)** — record‑bearing domain (structure/observers/records live here).
- **m₄** — the specific minor region instantiated at Bootstrap (process start).

### 0.4 Core idea (one sentence)
Reality is a finite sequence of globally shared time‑segments **t**, stored immutably in **T**, running inside a record‑bearing domain **m** that is instantiated within a centerless information‑silent domain **M**.

---

## 1) Axioms

### A1 — Finite Time + Termination
- Each segment **t** is finite and directed.
- The global process **t₀** can **terminate**.
- **Ending is not erasure; it is _no new changes of t_.**
  - i.e., the process ends when it no longer generates additional state updates / frames.

### A2 — Record Immutability
- **T is immutable.**
- Once a segment is committed into T, it is not erased, corrupted, or rewritten.

### A3 — Two‑Space Ontology
- **M** has **no real center** and does **not** host stable records.
- **m** is record‑bearing and supports dynamics/observers.
- **M contains m** and may contain **multiple m regions**.

### A4 — Bootstrap / Process Start
- Replace “Big Bang” language with **Bootstrap / Process Start**.
- Bootstrap instantiates a specific minor region **m₄**.
- Bootstrap is **localized** (not “everywhere at once”).

---

## 2) Terminology: No “Pushing” (avoid force metaphors)

We avoid “pushing” because it implies resistance. Use any of these equivalent phrases:

1) **Instantiation** — m increases by instantiating additional record‑bearing domain.
2) **Accretion** — m accretes extent into the uninstantiated remainder (no resistance implied).
3) **Domain growth** — m undergoes domain growth as a generative process.

All three mean: the realized (record‑bearing) domain **m** increases; **M** remains information‑silent and non‑resistant.

---

## 3) Commit Frontier (formal definition)

### Definition CF1 — Commit Frontier
Let **T** be the immutable record of committed segments of the global process **t₀**.

- The **Commit Frontier** is the index **k = CF(T)** such that:
  - segments **t ≤ k** are committed and present in **T**
  - segments **t > k** are uncommitted and not present in **T**

### Definition CF2 — Commit Operation
A **commit** is the transition that:
- closes the current live segment of t₀
- appends it immutably to T
- advances the frontier from k to k+1

### Constraint CF3 — No access beyond frontier
No operation may reference or traverse into **t > k** as if it were committed.

---

## 4) R3 + P1 — Global Replay Rule (Trigger / Traversal)

### P1 — Global Replay Model (shared, not per‑observer)
- At any moment, t₀ has advanced to **k**.
- **Everyone** can replay **up to k**.
- Replay semantics are **global**, not per‑person.

### R3 — Trigger / Replay Rule (T‑authorized)

**R3.1 Authority**
- Replay is a **manual** operation authorized from **T**.
- Replay does **not** originate from **M**.

**R3.2 Replay Window**
- Replay is allowed for any committed segment: **t ≤ k**.

**R3.3 Commit Barrier (forward‑rewind forbidden)**
- While the current segment is unfinished (i.e., before the next commit), **forward traversal** into uncommitted time is forbidden.
- There is no “rewind forward” into **t > k**.

**R3.4 Read‑only replay**
- Replay does not alter committed segments.
- There is no mechanism to change any **t ≤ k**.

**R3.5 Paradox avoidance (consequence)**
- Because committed history is immutable and future segments are inaccessible until committed, classic causal loops and grandfather‑style paradoxes are structurally blocked.
- Causal influence proceeds only via normal forward evolution of t₀.

---

## 5) Principle: Undetectability of M (connected to replay + records)

### P_M — Undetectability of M from within m
**Claim:** No observer confined to m can detect M.

**Reason:** Any detection attempt must produce an observable outcome, and any observable outcome must be recorded within m and therefore within some segment **t ≤ k** that becomes part of **T**.

But by definition:
- **M is information‑silent**: it does not yield stable recordable outcomes.
- The only way an attempted “probe beyond m” can become recordable is by being realized inside m.

Therefore:
- If a probe produces a record, it is already an m‑internal event (it extends/uses m), not evidence of M.
- If it produces no record, it cannot function as detection.

This yields a **receding frontier** intuition:
- attempts to “reach M” can at most trigger further **instantiation / accretion / domain growth** of m,
- but never a stable recorded observation “of M itself.”

---

## 6) Scope boundary (important)

This chapter does **not** claim:
- equivalence to standard cosmology
- observational agreement with isotropy/homogeneity constraints
- calculus/limit semantics for time or geometry
- a physical mechanism for dark energy

It **does** claim internal consistency under the axioms above: finite time, immutable record, global replay up to the commit frontier, M as undetectable information‑silent container, and m as the record‑bearing instantiating domain.
