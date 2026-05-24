# Client Engagement to Collateral

A Claude skill that turns raw client engagement material into polished, structured consulting deliverables. You bring the mess from an engagement, call notes, a transcript, a discovery brief, scattered context, and it produces the finished client-facing artifact in a consistent, senior house style.

## What it does

Consultants generate the same handful of deliverables over and over from messy inputs: a pile of call notes becomes a proposal, a discovery session becomes an executive readout, a meeting becomes a follow-up email. The raw material changes every time, but the deliverable structures and the house style do not. This skill captures that mapping, so the work goes from notes to finished collateral fast and consistently, without rebuilding the scaffolding each time.

It confirms the deliverable type and audience before writing, mines the raw material for the substance each deliverable needs, maps it onto a proven structure, and writes it in a senior register that leads with the point and stays grounded in the client's commercial reality. It produces a polished Word document by default for the substantial deliverables, handing off to the docx skill, and keeps cover emails as paste-ready text.

## Deliverables it produces

- **Proposal / Statement of Work** — a confident, scoped response to a defined need
- **Executive / Board readout** — a front-loaded, decision-oriented summary for a senior audience
- **Cover email / follow-up** — a paste-ready email to accompany a deliverable or follow a meeting
- **Discovery / Engagement summary** — an accurate reflection of what was learned, with open questions named honestly

## When to use it

Reach for it whenever you want to convert raw engagement input into a finished deliverable. It triggers on requests like "turn these notes into a proposal", "draft a board readout from this", "write the follow-up email after this client call", or "summarise this discovery session for the client".

## How it behaves

It always confirms what it is building and for whom before it writes, since the same material becomes a very different artifact depending on the deliverable and the audience. It never fabricates client facts, numbers, or commitments that are not in the source, flagging gaps with placeholders or a "to confirm" list rather than inventing detail. And it layers your own writing voice on top of the house style when you have one set, so the structure stays consistent while the words stay yours.

## Structure

- `SKILL.md` — the workflow and behaviour
- `references/deliverable-structures.md` — proven structures for each deliverable type
- `references/house-style.md` — the senior consulting register, written to sit beneath a personal voice

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
