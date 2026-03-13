# Commit Frontier — Formal Note (v1)

## Purpose
This note isolates the **Commit Frontier** concept so it can be referenced by other documents (replay rules, termination, undetectability of M).

## Definitions

### CF1 — Global Process
- `t₀` is the single global time process.
- Each segment `t` is finite, directed, and either **live** (unfinished) or **committed** (finished).

### CF2 — Record
- `T` is the immutable archive of committed segments.

### CF3 — Commit Frontier
- `k = CF(T)` is the greatest index such that `t ≤ k` are committed and included in `T`.

### CF4 — Commit operation
A commit:
1) ends the current live segment
2) appends it immutably to `T`
3) advances `k` to `k+1`

## Invariants

### I1 — Immutability
- Once committed, a segment is never rewritten.

### I2 — No forward access
- No operation can traverse into `t > k`.

### I3 — Replay window
- Replay is defined only over committed segments `t ≤ k`.

## Termination
Termination occurs when the system produces **no new changes of t**:
- there is no further commit after some final `k_final`
- `T` remains as a complete immutable archive

