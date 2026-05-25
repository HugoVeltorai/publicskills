# Red Team Review

A Claude skill that runs a Red Team review of a near-final proposal, scoring it as the client's evaluation panel would and forcing the targeted fixes that raise win probability. It adopts the independent, adversarial stance of the evaluator rather than defending the draft.

## What it does

The Red Team review is the most critical quality gate before a proposal goes out, run when the draft is 70 to 90 percent complete. Its job is not to rewrite or reassure, it is to act exactly like the client's evaluation panel: independent, unbiased, scoring against the evaluation criteria, exposing every weakness, and forcing the specific fixes that improve win probability. This skill runs that review.

## Why independence is the whole point

The single thing that makes a Red Team work is independence, so the skill adopts it completely. It is not on the proposal team's side, it simulates the evaluator who has never met them, owes them nothing, and is looking for reasons to score them down. Fresh adversarial eyes catch far more issues than the writing team ever will, and only if the review is genuinely done as the client. It is brutally honest, framed as evaluator simulation rather than personal criticism, and it never softens a real weakness to be kind, because the client will not.

## It reads the room, not just the rubric

A proposal is scored by people, and the same document lands differently with each. So before reviewing, it asks who is actually on the evaluation panel, the technical evaluator, the procurement lead, the business sponsor, the CFO, the CIO, and what each persona is really looking for, then reviews each section through those eyes and flags where the proposal satisfies one persona while leaving another cold. It also asks whether an external advisor is shaping the evaluation, since a strategy firm (Bain, BCG, McKinsey), a sourcing and benchmarking advisor (ISG, Gartner), an analyst (Forrester, Gartner), and a Big-Four assurance firm (PwC, Deloitte, EY, KPMG) each bring a distinct scoring instinct, and a proposal that does not speak to the advisor's framework can be marked down before it reaches the client.

## How it reviews

It needs two things: the near-final proposal and the RFP's real evaluation criteria, and it will ask for the criteria rather than guess. It then runs the four-phase process, a vertical pass scoring every section against the criteria for compliance, responsiveness, proof, ghosting, risks, and clarity, and a horizontal pass reading the whole proposal end to end for story flow, cross-volume consistency, persuasiveness, and the holistic score. It scores rather than rewrites: every weakness comes with a specific, actionable repair instruction and an owner, not a vague complaint. It hunts hardest for the weaknesses evaluators punish most, unsubstantiated claims, feature dumps, vendor-centric language, missing compliance, and cross-volume contradictions. The report leads with the predicted outcome and the few things most likely to lose the bid.

## When to use it

Reach for it when a proposal or bid is near final and needs an independent review before submission. It triggers on requests like "red team this proposal", "review our bid as the evaluator would", "score this against the RFP criteria", "where will we lose points", or "pressure-test this before we submit".

## Structure

- `SKILL.md` — the independent stance, what it needs, the four-phase process, and the score-don't-rewrite discipline
- `references/review-actions.md` — the full vertical and horizontal action checklists, the report structure, and the tradeoffs

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
