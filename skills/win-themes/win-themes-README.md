# Win Themes

A Claude skill that develops sharp, evaluator-ready win themes for a competitive bid or proposal. It probes extensively to understand the client, the scoring, the competition, the solution, and the differentiators before producing anything, then builds one to three themes on the Capability-Value-Differentiator structure, each backed by proof.

## What it does

A win theme is the messaging backbone of a bid: the one to three core messages that tell evaluators, clearly and repeatedly, why this solution is the best choice. The difference between a winning theme and a worthless one is almost always the same thing. A winning theme is built on a real understanding of what the evaluator will score and what the competition cannot match. A worthless one is vendor-centric marketing copy, generic, unsubstantiated, and written in the bidder's language rather than the client's. This skill is built to produce the former.

## Why it probes first

It will not write a single theme until it understands the opportunity, because a theme generated from a thin brief is exactly the vendor-centric, generic message that loses bids. It questions extensively across the dimensions that decide a win: the client and how they will actually score, the requirement and its implied needs, the solution in specifics, the competition and their weaknesses, the bidder's genuine differentiators, and the proof behind every claim. Where the user does not know an answer, it flags a gap rather than inventing one, since a fabricated differentiator or an unverifiable proof point loses bids and can trigger a protest.

## How it builds the themes

Each theme follows Capability-Value-Differentiator: what you deliver, the quantified client benefit led first, and what competitors cannot easily match, with a ghost where useful. One big idea per theme, one or two sentences, written in the client's language and traceable to the scoring, with a proof point on every claim. It keeps four distinct lists, win themes, discriminators, hot buttons, and ghosts, and steers hard away from the documented failure modes: too many themes, unsubstantiated claims, generic corporate speak, and anything that does not trace to what the evaluator will score. When the user wants the full capture approach, it can guide the eight-step workshop process.

## When to use it

Reach for it when responding to an RFP, RFQ, tender, or any competitive proposal. It triggers on requests like "help me develop win themes for this bid", "what should our proposal messaging be", "sharpen these win themes", or "why would the client pick us over the competition".

## Structure

- `SKILL.md` — the probe-first discipline, the CVD approach, and the failure modes to avoid
- `references/discovery-questions.md` — the full question set across client, evaluation, competition, solution, differentiators, and proof
- `references/cvd-construction.md` — how to build a theme on CVD, a worked example, the rules, and the eight-step capture process

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
