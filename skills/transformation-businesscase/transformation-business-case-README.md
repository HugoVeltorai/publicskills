# Transformation Business Case

A Claude skill that builds a rigorous, honest business case for a digital, technology, or AI transformation investment. It runs the standard financial metrics correctly while carrying the judgement about where transformation economics break the textbook model.

## What it does

Most business-case templates were built for clean, calculable investments: buy the tool, model the saving, project the payback. Transformation investments do not behave that way, and a case that pretends they do will either be rejected by a sharp CFO or, worse, approved on numbers that do not survive contact with reality. This skill builds the financial case properly, with NPV, IRR, payback, ROI, and TCO run correctly in code, while carrying the judgement about where transformation economics diverge from the textbook and how to be honest about it without losing the room.

## What makes it different from a calculator

It knows the four ways transformation breaks the standard model. The J-curve, where returns dip before they rise, so it refuses to show smooth returns from month one. Foundation versus application economics, where infrastructure spend is justified by option value and the cost of inaction rather than a projected return on the foundation itself. Benefits that resist quantification, which it sizes in honest ranges with stated confidence rather than inventing precision or dropping them. And the precision trap, where it reframes the CFO's demand for a single confident number toward staged investment, kill criteria, and the asymmetric cost of doing nothing.

It does the arithmetic in code so the numbers are right, always runs a sensitivity range rather than a single point estimate, and separates clearly which parts of the case rest on hard numbers and which on judgement. If a case is genuinely weak, it says so.

## When to use it

Reach for it whenever you need to justify, evaluate, or compare a transformation spend, an AI platform, a data or cloud foundation, an agentic capability, a digital rebuild, a core-system migration, or a build-versus-buy decision. It triggers on requests like "build the business case for this AI investment", "justify this platform spend", "should we build or buy", or "help me get this through the board".

## Structure

- `SKILL.md` — how to run the case and where transformation breaks the standard model
- `references/financial-methods.md` — runnable NPV, IRR, payback, TCO functions, sensitivity analysis, and the board-ready structure
- `references/transformation-economics.md` — the J-curve, foundation economics, unquantifiable benefits, and the precision trap, with how to argue each

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
