# RFP Response Plan

A Claude skill that turns a received RFP into a complete, backward-planned response plan and a living tracker, so a team gets to an on-time, compliant, high-quality submission. It questions the team's approval process, structure, workstreams, and timeline extensively first, then produces a Word response plan and an Excel tracker.

## What it does

When an RFP lands, the difference between a winning submission and a scramble is a response plan: the project plan for creating the proposal, built backwards from a fixed submission deadline so nothing is left to the last night. This is not the proposal itself and not the win themes, it is the operational backbone that aligns every stakeholder on what, when, who, and how. This skill builds that plan and the tracker that runs it, tailored to how the team actually works.

## Why it questions first

A response plan only works if it matches how the team actually operates, and the most common failure is a generic plan with vague dates and gates nobody owns. So it interrogates the setup before building: the exact submission deadline and rules, the team's real approval and color-review gates, who must sign off and how long that takes, the team structure and whether the response runs in workstreams, SME availability and capacity risks, the bid's strategic weight, and the tools and governance the team works within. Where something is not yet known, it records an explicit planning assumption rather than leaving a date as "TBD".

## How it builds the plan

Everything is planned backwards from the submission deadline as Day Zero, with buffers, placing executive sign-off, the Gold, Red, and Pink reviews, the draft cycles, and the kickoff in the right order with real time between them and the critical path made visible. It then produces two deliverables, deferring to the document and spreadsheet skills to build them: a professional Word response plan covering the eight standard components, and a living multi-sheet Excel tracker with a dashboard, master schedule, RACI, compliance matrix, action tracker, resource plan, and risk register. It treats both as living artifacts updated at every gate, and scales the process to the bid's weight rather than imposing the full machine on every response.

## When to use it

Reach for it when a team has received or is about to receive an RFP, RFQ, tender, or major proposal. It triggers on requests like "we just got an RFP, help us plan the response", "build our proposal response plan", "set up the bid schedule and tracker", or "we need a compliance matrix and timeline for this bid".

## Structure

- `SKILL.md` — the question-first discipline, backward planning, and the two deliverables
- `references/intake-questions.md` — the full intake set across submission, approval gates, team, resources, weight, and governance
- `references/plan-structure.md` — the eight plan components, the backward-planning method, and the exact Word and Excel structures

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
