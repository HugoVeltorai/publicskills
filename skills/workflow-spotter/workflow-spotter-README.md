# Workflow Spotter

A Claude skill that looks back over your recent work, finds the tasks you keep redoing by hand, and packages the ones worth packaging into a reusable skill, a saved process, or an automation. Written for an executive, not a developer.

## What it does

Senior people lose hours to the same handful of tasks done by hand every week: the update written from scratch, the meeting notes reshaped into the same summary, the recurring report assembled the same way, the same kind of email drafted again and again. This skill reviews your recent history, spots those repeated patterns, and turns the ones worth fixing into something done once and reused. It works like a sharp chief of staff handing you a list of what you keep redoing and what has been set up to fix it.

## How it works

It gathers evidence from your past conversations, memory, and any connected calendar, email, or documents, then filters for genuine repeated workflows: things that have happened at least twice, have a stable shape, and would be improved by being systematised. It presents a compact shortlist first, so you decide what gets built, then creates only the high-confidence items and tells you plainly what it made, what it skipped, and what needs more evidence.

It recommends the lightest tool that fits each job, a reusable playbook, a delegated task, a recurring automation, or an extension of something you already have, and it is as ready to skip or defer a candidate as to build one.

## When to use it

Reach for it when you want to find what you keep repeating and systematise it. It triggers on requests like "what do I keep redoing that I could automate", "look at my recent work and find what's worth a skill", "where am I wasting time on repeat tasks", or "audit my workflows".

## Structure

- `SKILL.md` — the discovery workflow and the rules for what to package
- `references/shortlist-example.md` — a worked example of the shortlist format

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
