# Exec Clarity

A Claude skill that sharpens executive writing so it lands with a senior, time-poor reader. You paste a draft, it tells you plainly what is weakening it and hands you a tighter version you can send.

## What it does

Senior readers skim. They want the point first, the reasoning second, and the ask made obvious. Most professional writing fails them not because the thinking is weak but because the writing buries it, opening with throat-clearing, hedging the conclusion, padding with jargon, and leaving the reader to dig for what they are meant to do. This skill fixes that. It names what is weakening a draft, so you learn the pattern, and offers a sharper rewrite you can use immediately.

## The editorial stance

The skill is opinionated on purpose, because vague "improve my writing" help is useless. It edits toward a clear view of what executive writing should do: lead with the answer, cut the throat-clearing, kill the hedging, make the ask explicit, strip decorative jargon, and shorten. Most executive drafts are improved by removing a third of the words.

## How it works

Give it a draft and it responds in four moves: a one-line verdict so you know immediately what you are dealing with, a short list of specific flags each tied to a spot in your text, a clean rewrite you can use as-is, and an honest note on anything it could not fix without more information. It never invents facts, numbers, deadlines, or commitments that were not in your draft.

It learns your voice once and reuses it. On first use it asks in a single tap how you want to sound, blunt, warm, formal, dry, then remembers that and applies it to every rewrite after, so you never re-explain yourself. You can change your default any time, or override it for a single draft. If you would rather not set anything up, it proceeds with a credible senior default and never blocks you.

## When to use it

Reach for it whenever you want to tighten or pressure-test a piece of writing before it goes out. It triggers on requests like "make this clearer", "tighten this", "is this too long", "does this get to the point", or "review this before I send it".

## Structure

- `SKILL.md` — the editorial stance and the response workflow
- `references/diagnostics.md` — common executive writing problems, how to spot each, how to fix it
- `references/formats.md` — how the clarity principles flex across email, board notes, Slack, LinkedIn, and sensitive messages

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
