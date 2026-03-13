# Undetectability of M via Replay Logic (v1)

## Goal
Connect the claim “**m cannot detect M**” directly to the **global replay + commit frontier** model.

## Setup
- `M` is information‑silent (no stable records).
- `m` is record‑bearing (all observations are records in `T`).
- `t₀` is the global process; `k` is the commit frontier.
- Everyone can replay `t ≤ k` (global replay).

## Claim
**No experiment performed from within `m` can produce a recordable outcome that distinguishes the existence of `M`.**

## Argument (record-based)
1) A successful “detection” must yield a **recordable** outcome.
2) Recordable outcomes in this framework are exactly those that become part of `T` via commits, hence lie in some `t ≤ k`.
3) But any outcome that becomes a record is, by definition, realized within the record-bearing domain `m`.
4) `M`, being information-silent, cannot itself be the source of stable recordable outcomes.

Therefore:
- If a probe yields a record, that record testifies only to an `m`-internal event (possibly an extension of `m`), not to direct observation of `M`.
- If a probe yields no record, it cannot serve as detection.

## Receding frontier interpretation
Attempts to “probe beyond m” may at most coincide with further **instantiation / accretion / domain growth** of `m`.
This makes the boundary between `m` and `M` operationally non-observable: it does not appear as an object in `T`.

## What replay adds
Because replay is global and limited to `t ≤ k`, any purported evidence for `M` must be replayable as part of `T`.
But replay only replays `m`-internal records — hence `M` never appears as a replayable object of evidence.

