# undeclared-reference

**Same Score, Different Kind — benchmark fiber structure and the undeclared choice of reference**

Working paper. Draft v0.9. Not for citation. **Revision held pending human review** — see `reviews/panel-log.md`.

Read it: **https://bluebflatminor.github.io/undeclared-reference-/**

> Note the trailing hyphen. The repository is named `undeclared-reference-`, and every earlier version of this README linked to the un-hyphenated path, which 404s. If the repository is renamed to drop the hyphen, this link and any external references must be updated with it.

---

## The claim in one paragraph

A benchmark's *fiber structure* — the family of systems it cannot distinguish — is fixed when the task set, scoring rule, and aggregation are specified. It is almost never declared. Kind-claims made on the basis of a benchmark score depend silently on that partition. The exhibit that would expose the dependence is finite and cheap, and it has already been produced: in 2023 the EvalPlus authors showed, with a named model pair, that HumanEval's *ordering* was an artifact of test-suite thinness. HumanEval then continued to circulate alongside its replacement and was eventually retired on other grounds. **That last sentence is unanchored** — see Known defects.

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
index.html              the paper, v0.9
drafts/                 v0.1–v0.8 markdown lineage, with cut logs
reviews/panel-log.md    adversarial review, items taken and declined
verification/           citation gate results and open items
```

Drafts are retained rather than squashed. Each carries a change log naming what was cut and why, including the two claims that were wrong and had to be replaced, and the one section that was cut rather than anchored.

## Corrections on the record

Load-bearing claims in earlier drafts that were false, mislocated, or unsupportable. Recorded rather than quietly fixed.

| Draft | Claim | Status |
|---|---|---|
| v0.4 | Validity information has no channel into benchmark turnover | **False.** Refuted by the paper's own case — EvalPlus was adopted, and adopted for fixing a demonstrated defect. Replaced in v0.5 by the adoption/retirement asymmetry. |
| v0.6 | The loop monitors the ceiling fiber and is blind to interior ones | **Mislocated.** Ceiling compression is itself a validity failure; an instrument reporting that frontier models are alike is making a kind-claim. Replaced in v0.7 by reference-free detectability. |
| v0.8 | HumanEval appeared on essentially every frontier model card across vendors for three years | **Withdrawn.** No citation, and never listed as a defect while being asserted in the abstract, §1.1, and this README's lead. The weaker continued-circulation claim survives and is marked at the point of use in v0.9. |
| v0.8 | §5, the musical-notation case | **Cut, not blocked.** See below. |

The tombstones stay.

## The gate failure in v0.8

Recorded separately because it is a failure of the protocol rather than of a claim.

§5 carried an unanchored historical claim and an explicit instruction that the section must not be deployed in that state. It was deployed anyway, live on the public site, for the duration of v0.8. "Blocked" was functioning as a label, not as a state that prevented anything.

In v0.9 the section is cut. Its argumentative work — answering the objection that some reference is nonetheless the correct one — is now carried by the first item in the objections section, which needs no case to make the point. Candidate anchors remain deliberately unnamed anywhere in this repository.

The lesson generalizes: this repository has no mechanism that can stop a marked section from shipping. Until it does, **marking is disclosure, not enforcement**, and this README should not be read as claiming otherwise.

## Known defects

- **The continued-circulation claim is unanchored.** It is asserted in §1.1 and inherited by §4.2, and both are marked in place. Test: code a sample of post-2023 frontier model cards for whether HumanEval is reported and on what stated grounds. Not run.
- **Possible prior art on the fiber framing.** A 2026 preprint appears to apply fiber vocabulary to benchmarks directly, with quantitative mixed-fiber audits across scientific domains. Surfaced in search, not resolved at publisher record, deliberately unnamed until it clears the gate. If it holds, the §2 framing is restatement and the contribution narrows to the case and the mechanism. **Top gate item.**
- **The mechanism rests on one case** and is subject to survivorship: a benchmark retired for demonstrated invalidity would be underrepresented in retrospectives by construction.
- **The title names the weaker failure.** "Same Score, Different Kind" describes collision; the evidence is inversion. Unresolved.
- **The remedy's institutional feasibility is untested.** §4.4 and §4.5 specify what a reporting requirement would have to consist of, constrained by the mechanism itself. Whether any venue or leaderboard would adopt it is unknown, and no one who runs one has been asked.
- **The 7.7 vs 9.6 test-count discrepancy is open**, and one offered explanation for it has been refused as unverified rather than adopted. See the tombstone in `verification/citation-gate.md`.
- **Legibility check not run** against the v0.9 build on a real device.
- **No human has reviewed this.** Every correction to date came from language models used as adversarial instruments, which are correlated with each other and with the model that drafted it. Successive rounds have produced distinct review *framings* — agreement, disagreement, rigor, completion — and one underlying behaviour. This is the weakest form of review the paper could rest on and is currently the only form it has.

## Citation gate

Run 2026-08 against publisher records. References [1]–[3] resolved. Field corrections logged in `verification/citation-gate.md`, including an author-string error propagated by a major index and a live discrepancy in the reported tests-per-problem figure for HumanEval.

No reference appears in the paper that has not been resolved at source. Two entries are held unnamed pending resolution and are marked as such.

## Disclosure

**D3: machine-drafted, human-directed, human-verification pending.**

Drafted in collaboration with a language model, directed and reviewed by the author, with citations verified against publisher records. Adversarial review obtained from language models used as instruments; panel agreement is treated as approximately one signal rather than several, since the instruments are correlated. Review items are logged whether taken or declined.

## License

CC0 1.0 Universal. No rights reserved.

## Contact

Solbakken Research Initiative · Omaha, Nebraska · no institutional affiliation.

Corrections are welcome and will be logged rather than silently applied. If you can produce a counterexample to the falsification condition above, that is the most useful thing anyone could send.
