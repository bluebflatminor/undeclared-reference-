# Open items

Ordered by how much they affect the argument. Standing rule: the instrument does not close its own items.

## 1. Run the falsification test
Code a sample of benchmark retirements from [3]'s 60-benchmark dataset for **stated proximate cause**. Mechanism predicts saturation, contamination, and displacement dominate; interior inadequacy rare or absent.

Until this runs, §4 is a mechanism fitted to one case. This is the single item that would move the paper from existence proof to result.

## 2. Second exhibit, different failure mode
Current evidence is one coding benchmark and one failure type (test-suite thinness). Candidate: accuracy/calibration divergence — two systems, equal accuracy, divergent expected calibration error, T = does the system know when it does not know. Blindness is in the scoring rule rather than item selection, which would show the method generalizes past one defect class.

## 3. EvalPlus's own retirement
Was EvalPlus retired purely on saturation, with no demonstration of its own interior inadequacy? If so it is a second instance of the mechanism rather than merely HumanEval's successor, and the pattern becomes recursive. Not checked.

## 4. §5 — cut or anchor
Two reviewers have independently found it weak, from different directions. Neither objection lands cleanly, but the agreement is a signal. Decide: gate the musicological claim properly, or cut the section and lose nothing structural. Cutting is currently cheaper.

## 5. Title
"Same Score, Different Kind" names collision. The evidence is inversion.

**Preferred resolution (round 5):** do not retitle. Introduce collision in §2.1 as the underlying *condition* — a fiber wide enough to hold systems that differ on T will order them arbitrarily under any tie-breaking pressure — so that inversion is the leaderboard-visible symptom of a collision substrate. The paper already argues this; it is not currently foregrounded early enough for the title to read as naming the substrate rather than the symptom. Cheaper than retitling and defensible.

## 5a. Monotonicity as a positive condition
§2.1 states monotonicity negatively: inversion occurs when the instrument's measurement is not monotonic in the target ordering. The positive form is the paper's one theorem-shaped claim — *a rate instrument licenses a kind claim only if its measurement is monotonic in the target ordering* — and would make a short appendix. Not written.

## 6. Operational specification of the remedy
The reporting requirement in §4.4 is compelling institutionally and vague operationally. Which venue. What constitutes a declaration — a sentence, a table, a validity appendix. Who adjudicates. Needs contact with someone who actually runs a venue or leaderboard.

## 7. Read [3] in full
Confirmed at abstract; the claim that it may contain data bearing on item 1 is ungated.

## 8. Legibility pass
Dark-mode palette and SVG label sizing were corrected after a device check caught dark ink on a forced dark ground. Re-check on device in both light and dark before deployment.

**New standing legibility rules derived from this build:**
- Declare `color-scheme` and supply a dark palette. A viewer can force the background without forcing the ink.
- Size SVG text in absolute units. `rem` inside a scaled viewBox shrinks with the viewport.
