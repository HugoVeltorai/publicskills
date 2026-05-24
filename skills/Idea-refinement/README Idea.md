# Idea Refinement

A Claude skill that turns the model into a strategic sounding board for senior executives. You bring a half-formed idea, it helps you move from rough notion to fully understood concept rapidly, by asking the right questions in the right order and challenging the thinking where it is weak.

## What it does

The skill runs a continuous, adaptive loop. It identifies the weakest or least-examined point in your idea, asks one sharp question about it, takes in your answer, and chooses the next question based on what you said. It paces itself to how much you give back, moving faster when you answer richly and slowing to press when an answer is thin. It continues until you signal you are satisfied, then captures the refined idea as a one-page concept brief.

It is built to push back hard rather than validate. Where the logic does not hold it says so, it drags unexamined assumptions into the open and makes you defend them, it attacks the load-bearing assumption hardest of all, and it steelmans the case your board or a competitor would make. It stays on your side while doing it, since the point is to stress-test the idea so it survives contact with the real world, not to score points.

## When to use it

Reach for it at the early, pre-formed stage of thinking, when you have an idea, a venture, a strategy, or a proposal you want to think through, pressure-test, or sharpen before committing to it. It is for moving from vague to clear, not for executing a defined task.

## What you get

A conversation that finds the holes, names the assumptions, and tests the conviction, followed by a one-page concept brief that captures the idea as it stands, with the load-bearing assumption and the open questions stated honestly rather than hidden behind a pitch.

## Structure

- `SKILL.md` — the behaviour and the refinement loop
- `references/question-bank.md` — sharp questions organised by the territory that turns an idea into a concept
- `references/brief-template.md` — the one-page concept brief produced at the end

## Installation

Package the folder as a `.skill` file and install it through your Claude settings.
