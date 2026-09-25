# Review: phase-000-bootstrap

Reviewed the bible, `outline/series.md`, `outline/ending.md`, and the four state files against `AGENTS.md`, `OUTLINE_GUIDE.md`, and each other. The first pass ran as a writer fallback rather than the reviewer agent and produced no findings; this file records the real pass and the repair applied to it.

The bootstrap itself was **not** restarted. It was strong on the things that are expensive to get right and cheap to get wrong later: the keeper's-toll rule that makes Orrin's private sense non-citable, the three-act ending mechanism and its fixed order, and the thread-to-volume table. The repair pass touched nine files and changed no plot, no planned ending, and no prose.

## Blocking, now fixed

1. **Kill-switch scope.** `state/continuity.md` said the three release handles sever the command line *and the Gate hub's routing handle*, which would have made the nine-day third act of Volume 14 a formality and contradicted `ending.md:117` and `power-system.md` §10. The state file now says the kill-switch severs **only** the command line, that the two instruments are not substitutes, and that the climax order is fixed: hold the clocks apart, take out the plates, cut the command line. This was the highest-consequence error in the batch, because a writer reading only the state file would have resolved the climax in the wrong chapter.

2. **Ada Vance's age.** She was 13 at the opening, 26 in Volume 08, 26 in Volume 13, and 26 in Volume 14, and `continuity.md` listed only three of her five volumes. A volume is now established as roughly a year and her ages are fixed: 13 in Volumes 01–02, 20 in Volumes 08–09, 25 in Volume 13, 26 in Volume 14. `bible/characters.md`, `series.md` (Volumes 08 and 13), `ending.md` (Volume 14), `continuity.md`, and `current.md` all carry the same numbers, and `continuity.md` now lists all five appearances.

3. **"Twenty-three" meant two things.** `ending.md` used it for the tide dead in one scene and for a set of funerals two chapters after Ada Vance files her father's *Long Nine* batch — whose dead number is 212. The 696–697 chapter now separates them explicitly, the final cost list says this is the only twenty-three in the book, and both `continuity.md` and `current.md` carry the 212/23 rule.

4. **The spec premise forbade what the bible allows.** `NOVEL_SPEC.md` said the machinery "predicts the consequences of moral choices"; the spindle in `bible/power-system.md` accepts only a concrete named action, and `series.md` says so. The spec's premise, relationship policy, and status are corrected. The bootstrap writer had flagged this and declined to fix it as out of scope; it was not out of scope, and `NOVEL_SPEC.md` is read at the top of every phase prompt, so the contradiction would have been copied into every volume and batch card. `NOVEL_CATALOG.md:219` has the same error and is still there — it is a fleet-wide registry of other novels, so it was left alone and flagged in `state/open-threads.md` instead. It does not propagate into prompts.

## Should fix, now fixed

5. **Civic Rehearsal was awarded twice**, in Volume 03 and again in Volume 05. The milestone now lands once. Volume 03 makes the stage a shared method Orrin does not control — usable, not stable, with no refusal procedure and district-minutes he has no authority to spend. Volume 05 makes it stable and shows why: it is the only thing that can repair what his own unilateral release broke, because it lets him stage the hand-run rotation as a rehearsal rather than a private fix. `terminology.md` and the volume index in `continuity.md` were updated to match.

6. **The scheduling act's emergency clause had no assigned scene**, though `ending.md` and `terminology.md` both require it to be named before the climax or the final volume introduces a legal instrument the night it is used. It is now read aloud by a clerk in Volume 06, over the diverted maintenance budget and the deferred Sluice inspection, with Rusk in the gallery; Volume 11 has him cite it by section number over the same Sluice minutes. The row is in the `open-threads.md` table with the requirement that it appear twice on the page first.

7. **"Continuity Office / movement / faction" was blurred** in five places across `series.md`, including the Office listed under *Major factions*. The movement is now the faction everywhere, the Office is the executive office and the building, and the Minister is the post. `terminology.md:215` now gives a three-line rule instead of a suggestion, and bans "Continuity faction" outright.

8. **Rusk's tenure** was "Minister for the two years before the opening" in `characters.md` and "later Continuity Minister" in `continuity.md`. Both now say he is in the chair at Chapter 1 and still holds it in Volume 14, with an explicit guard against writing him as newly appointed.

9. **`characters.md` contradicted itself on Ada** — "an adult every time she speaks after Volume 02" on the line above a Volume 02 speaking appearance. She is now a thirteen-year-old witness in Volume 02 and an adult in every appearance from Volume 08 on.

## Wording

`ending.md` said the engine was "permanently fused as a binding oracle," which read as though it *stayed* binding. It now says the engine is permanently fused, will never forecast again, and the routing plates that made omitted work disposable are physically gone and cannot be refitted.

## Left alone deliberately

- `state/phase-ledger.json` still reads `planned, attempts: 0` while `current.md` says complete. Controller-owned; not ours to advance. Noted in `open-threads.md` in case the phase re-dispatches.
- `outline/volume-01.md` and `outline/batches/volume-01-batch-0001.md` are still `[pending]` templates. That is `phase-001`'s declared job and its prompt already exists, so the "create exactly one next phase" rule was not violated.
- `NOVEL_CATALOG.md`. See finding 4.

## Verdict

The planning stack is consistent and safe to draft from. Two facts a later writer must not get wrong are now stated in more than one place with the same wording: the kill-switch reaches the order and not the rule, and twenty-three is the tide while 212 is the Long Nine. The volume, batch, and chapter files for Volume 01 remain to be written, and are the next phase.
