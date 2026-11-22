# HANDOFF — M_Unity_FreeflowCombat

**Last updated: 2026-11-22 (America/New_York).**
**Repo:** `mhvnsnt/M_Unity_FreeflowCombat` (PUBLIC), default branch `Main-Branch` (NOT main — capital M, capital B).
**Purpose of this file:** any agent that picks up work here reads this FIRST, then the linked docs. It states what we've done, where we're at, and what we're working toward — so the owner can say "go to this repo, pick up the work" and you just know. Update this file in the same PR whenever the state changes (add, don't delete).

## 1. What this repo is

Free-flow combat in Unity — the owner's working copy of a free-flow combat project (the "Arkham-style" flow combat lineage: one stick, flowing from enemy to enemy). The repo description is "Free flow combat". At ~316 MB it is a Unity project copy with a `DungeonCrawlerTest` folder at root.

There is NO root README — pickup starts at `AGENTS.md` and `WORKING-METHOD.md`. What the project is beyond "free flow combat" — which game it serves, what the combat is for — is NOT written down in the repo state read 2026-11-22. Any agent picking this up should treat the purpose as unclear until the owner or the `docs/` folder says otherwise.

## 2. Where we're at

### DONE
- **Project in place:** Unity free-flow combat project, `DungeonCrawlerTest` folder, `docs/`, agent notes.
- **Anti-clobber laws merged (2026-10-17, PR #3):** the owner's anti-clobber laws are in `AGENTS.md`.
- **Working method stated (2026-10-27):** commits `d2328db` / `608be0b`, `WORKING-METHOD.md` at root.
- **Last push 2026-11-20** (repo metadata; no new content commits after Oct 27 — the push reflects repo-level activity).

### IN PROGRESS
- **Two open docs PRs (Nov 19–20, unmerged):** PR #6 — "Docs: pre-made parts first rule" (`docs/premade-parts-first`, 2026-11-20); PR #5 — "Docs: sourcing rule" (`docs/sourcing-rule`, 2026-11-19). Next step: a merge call on #5 and #6.
- **No build, slice, or target game is recorded in this repo.** What the free-flow combat is being built FOR is not stated. That is an open question (see §6), not hidden progress.

### BLOCKED
- **Nothing recorded as blocked in the repo state read 2026-11-22.** No blocked item is named in this repo. The open PRs are awaiting a merge decision, not unblocked work.
- **Branch note (not a block):** the default branch is `Main-Branch`, not `main`. Every branch/PR/merge command must use `Main-Branch` as the base — using `main` will fail.

## 3. What we're working toward

**The goal (as far as the repo states it):** free-flow combat that works in Unity — flowing, responsive, playable.

**The bar (owner, general):** REAL-SOURCE-ONLY — real parts, wired in, no hand-tooled lookalikes; the work proves itself in a live playable build, never a text-only "done". Until the target game is defined, there is no specific bar for this repo beyond that.

**In order:** (1) merge or close PRs #5 and #6; (2) get the owner to define what this combat is for and what the first playable slice is; (3) build that slice in player-progression order.

## 4. Standing rules that apply here

- **Branch → PR → merge, always — base is `Main-Branch`.** Never push to Main-Branch directly. Add-only, zero-conflict PRs, no force pushes.
- **Checkpoint-and-save law:** CHECKPOINT.md first, update after every step; the repo is the save; resume, never restart.
- **No-temp-storage law:** nothing in /tmp or any wipeable location, ever. Everything goes straight into the repo or a durable folder the second it exists.
- **Real-source-only:** every part comes from the actual source code and files, wired up fully. No hand-tooled lookalikes, no fake panels.
- **Anti-clobber law (owner 2026-10-17):** do not clobber other lanes' work. Add, don't overwrite. (Merged as PR #3.)
- **No-gaps / solve-it law:** a gap or block is never the end of the work — route-switch until it's done or every reasonable route is exhausted with exact errors recorded.
- **Licence-not-a-gate:** licence status never gates pulling in material that helps; licence/source is still logged honestly next to the item.

## 5. Key files and paths

| What | Where |
|---|---|
| Agent notes / working method (start here — no README) | `AGENTS.md`, `WORKING-METHOD.md` |
| Dungeon crawler test area | `DungeonCrawlerTest/` |
| Docs | `docs/` |
| Open PRs | #5 (sourcing rule), #6 (pre-made parts first rule) |
| Merged PR | #3 (anti-clobber laws, 2026-10-17) |

There is no root README and no releases in this repo. Default branch is `Main-Branch` — not `main`.

## 6. Open decisions needing the owner

- **Merge PRs #5 and #6?** Two small docs-rule PRs open since Nov 19–20. Merging locks the rules in; leaving them open leaves the repo without the written rules. His call — lanes do not decide merges.
- **What is this combat FOR?** Which game, what the first playable slice is — all his call. A lane cannot invent the target.
- **No other owner decision is recorded as open in this repo's state.**

## 7. How to pick up

1. Read this HANDOFF.md first, then `AGENTS.md`, `WORKING-METHOD.md`, and `docs/` (there is no README).
2. Remember: default branch is `Main-Branch`. Base every PR on `Main-Branch`.
3. Check the two open PRs (#5, #6) — leave them alone unless told to merge.
4. Do NOT invent a target game for this combat. If the purpose is still undefined, the next step is asking the owner (through the parent agent), not building a guessed game.
5. Resume from the stated next step — never restart, never re-derive finished work.
6. Land work branch → PR → merge, add-only. Update this HANDOFF.md in the same PR when the state changes. Verify with your own eyes (a running build) before claiming anything done.
