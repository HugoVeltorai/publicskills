# Document Interrogator

A Claude skill that lets you interrogate documents the way a sharp executive reader would, with grounded, sourced answers rather than vague summaries. Upload a report, contract, board pack, research paper, or filing, and question it directly.

## What it does

A time-poor senior reader does not want a book report, they want to interrogate a document the way they would interrogate a person: what does this actually say, what matters to me, what is it not telling me, and can I trust it. This skill turns one or many documents into something you can question directly, and every answer traces back to where it came from in the text, so you can verify rather than take it on faith.

## How it is built

It rests on four disciplines that separate real interrogation from a confident paraphrase. It grounds every answer in the text and points you to where each claim sits, so you can check it. It never invents, treating what a document does not say as a finding rather than a gap to fill. It reads like a decision-maker rather than a student, surfacing the buried decision, the softened risk, and the assumption the case depends on. And on request it reads as the document's sharpest critic, naming the weak claim and the figure that does not reconcile, grounded in the text.

Across multiple documents it attributes every point to its source and surfaces conflicts rather than smoothing them over, since where two documents disagree is often the most important thing on the table.

## How it compares

It is built to rival dedicated document tools on the part that matters most to an executive: faithful, sourced, sceptical reading. It is honest about its edges too. It does not persist a library across sessions and it works from what is in the documents rather than from outside knowledge unless you invite that, keeping the line between what the document says and what the model knows visible at all times.

## When to use it

Reach for it whenever you have a document to understand or question. It triggers on requests like "what do I need to know in this", "what should I be worried about here", "does this say anything about X", "what would a sceptic challenge", or "compare what these two reports say".

## Structure

- `SKILL.md` — the reading protocol and the four interrogation disciplines
- `references/interrogation-modes.md` — orientation, decision, risk, sceptic, reconciliation, extraction, and fact-check passes, plus high-value questions

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
