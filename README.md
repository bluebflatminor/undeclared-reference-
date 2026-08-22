# undeclared-reference

**Same Score, Different Kind — benchmark fiber structure and the undeclared choice of reference**

Working paper. Draft v0.7. Not for citation.

Read it: **https://bluebflatminor.github.io/undeclared-reference/**

---

## The claim in one paragraph

A benchmark's *fiber structure* — the family of systems it cannot distinguish — is fixed when the task set, scoring rule, and aggregation are specified. It is almost never declared. Kind-claims made on the basis of a benchmark score depend silently on that partition. The exhibit that would expose the dependence is finite and cheap, and it has already been produced: in 2023 the EvalPlus authors showed, with a named model pair, that HumanEval's *ordering* was an artifact of test-suite thinness. HumanEval then appeared on essentially every frontier model card for three more years and was retired for saturation instead.

## The mechanism

An evaluation loop corrects exactly those defects **detectable without a declared reference**, and is structurally blind to the rest.

- Saturation is reference-free: compute the score spread.
- Contamination is reference-free: compute n-gram overlap.
- Mis-ranking is not: someone had to build an eightyfold test suite to see it.

HumanEval had three demonstrated defects. The two that counted are the two nobody needed a task definition to detect.

This is not indifference to validity. It is an inability to see the part of validity that requires a reference to see — which returns the mechanism to the paper's subject rather than sitting beside it.

## What would falsify this

Stated in advance, per standing practice.

**Primary.** A survey of benchmark retirements in which a substantial fraction cite demonstrated interior inadequacy — mis-ranking, shortcut exploitation, construct failure — as the proximate cause, rather than saturation, contamination, or displacement. The mechanism predicts these are rare or absent. The dataset in Akhtar et al. (60 benchmarks, arXiv:2602.16763) is the natural place to run it. **This has not been run.**

**Secondary.** A documented case where a fiber-collision or inversion exhibit alone removed an instrument from circulation, with no accompanying saturation or contamination finding. One clean instance would refute the strong form.

## Repository contents

```
index.html              the paper, v0.7
drafts/                 v0.1–v0.5 markdown lineage, with cut logs
reviews/panel-log.md    adversarial review, items taken and declined
verification/           citation gate results and open items
```

Drafts are retained rather than squashed. Each carries a change log naming what was cut and why, including the two claims that were wrong and had to be replaced (see below).

## Corrections on the record

Two load-bearing claims in earlier drafts were false and are recorded rather than quietly fixed.

| Draft | Claim | Status |
|---|---|---|
| v0.4 | Validity information has no channel into benchmark turnover | **False.** Refuted by the paper's own case — EvalPlus was adopted, and adopted for fixing a demonstrated defect. Replaced in v0.5 by the adoption/retirement asymmetry. |
| v0.6 | The loop monitors the ceiling fiber and is blind to interior ones | **Mislocated.** Ceiling compression is itself a validity failure; an instrument reporting that frontier models are alike is making a kind-claim. Replaced in v0.7 by reference-free detectability. |

Both corrections came from adversarial review and both improved the argument. The tombstones stay.

## Known defects

- **§5 is blocked.** Its historical claim about recording and score authority has no anchor. Candidate sources were identified during drafting and are deliberately **not named anywhere in this repository**, because listing plausible-looking titles is the failure mode the citation gate exists to prevent. Two reviewers have independently found the section weak; cutting it may be cheaper than gating it.
- **The mechanism rests on one case** and is subject to survivorship: a benchmark retired for demonstrated invalidity would be underrepresented in retrospectives by construction.
- **The title names the weaker failure.** "Same Score, Different Kind" describes collision; the evidence is inversion. Unresolved.
- **The proposed remedy is operationally unspecified.** Which venue, what constitutes a declaration, who adjudicates. No proposal offered.

## Citation gate

Run 2026-08 against publisher records. References [1]–[3] resolved. Field corrections logged in `verification/citation-gate.md`, including an author-string error propagated by a major index and a live discrepancy in the reported tests-per-problem figure for HumanEval.

No reference appears in the paper that has not been resolved at source. Where an anchor is needed and absent, the gap is stated and the section is marked blocked.

## Disclosure

**D3: machine-drafted, human-directed, human-verification pending.**

Drafted in collaboration with a language model, directed and reviewed by the author, with citations verified against publisher records. Adversarial review obtained from language models used as instruments; panel agreement is treated as approximately one signal rather than several, since the instruments are correlated. Review items are logged whether taken or declined.

## License

CC0 1.0 Universal. No rights reserved.

## Contact

Solbakken Research Initiative · Omaha, Nebraska · no institutional affiliation.

Corrections are welcome and will be logged rather than silently applied. If you can produce a counterexample to the falsification condition above, that is the most useful thing anyone could send.
