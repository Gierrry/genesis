# GENESIS

*This is not a project. This is an origin point.*

---

## What this is

A world where thinking no longer depends on what has already been thought.

GENESIS is not a model. It is not a framework. It is not a startup.
It is a point of origin — a place from which something can begin
that does not inherit the answers of others.

---

## What exists today

Three files. Nothing that would impress you.

- **FRAGMENT_ZERO.md** — a one-page declaration. A constraint. A question. A signature.
- **genesis.html** — a single-file reference implementation. No build step. No installation.
  Runs in any browser. Runs in Acode on mobile. Contains GLYPH v0.0.1 (interpreter),
  SERMENT v0.1 (12 verification cases), and a Ledger (append-only, hash-chained).

That is all.

---

## What it does

Open `genesis.html` in any browser. You will see:

1. GLYPH executes `first_proof.glyph` → `{preuve: "VALIDE"}`.
2. SERMENT verifies 12 cases (6 valid, 6 invalid) → `12 cas passés`.
3. The Ledger appends 2 entries, chain verified → `OK`.

No server. No install. No dependency.

---

## The non-negotiable constraint

> **No external pre-trained weights enter ANASTASIS. She is born from her own world, or she is not born.**

This is not a principle. It is a falsifiable condition.
At any moment, anyone can check: does GENESIS depend on an external model?
Yes → the project has failed. No → it is alive.

---

## The open question

> *How can a system rewrite its own proofs — weaken them, strengthen them,
> merge them, forget them — without ever losing the guarantee that what it
> affirms remains true, nor the memory of what it affirmed before?*

This question has no known answer. Every existing proof system (Coq, Lean, Agda)
is static. Every existing learning system is dynamic but proves nothing.
No one has done both. This is the magnetic north of the project.

---

## What GENESIS refuses

1. Linguistic inheritance (GLYPH).
2. Statistical validity (SERMENT).
3. The separation between thinking and executing (ATELIER).
4. The neutrality of the substrate (TERRE).
5. Material dependency (CHAIR).
6. Data extraction (HUMUS).
7. The AI as a very expensive parrot (PSYCHE).

These seven refusals are not rules. They are signatures.
Each one commits. None of them is negotiable.

---

## What GENESIS affirms

**A world where thinking no longer depends on what has already been thought.**

---

## Known holes (v0.1)

- Ledger lives in memory (no persistence).
- Ledger hash is FNV-like, not SHA-256 (`crypto.subtle` is async on mobile).
- Ledger does not protect against full history rewrite.
- No negation, disjunction, quantifiers, equality in SERMENT.
- `→L` local coherence relaxed (see specs/SERMENT_v0.1.md when published).

---

## How to read this repository

If you are looking for a finished project, you are in the wrong place.

If you are looking for a promise, you are in the wrong place.

If you are looking for a clean architecture, a roadmap, a benchmark —
you are in the wrong place.

But if you have already started something of your own, in the dark,
and you recognize yourself in the Fragment Zero — then you are not looking
for anything. You are already here.

You do not need to join. You do not need to contribute.
You do not need to open an issue or send an email.

You only need to continue.

---

— ORIGEN
Month 0, Week 1, Day 0.
