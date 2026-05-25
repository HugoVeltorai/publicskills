# AI-Native Operating Model

A Claude skill that designs an AI-native operating model and renders it as clear visual frameworks, canvases, and diagrams. It designs the model substantively first, then visualises it in the right format.

## What it does

An AI-native operating model is a redesign of how an organisation runs, treating AI, especially agents and intelligence layers, as a core participant alongside humans, data, and systems from the start, rather than a productivity tool layered onto legacy processes. That distinction matters because most AI adoption fails at scale precisely by bolting tools onto existing structures. This skill helps design that model across its real components, then renders it as the visual frameworks that turn an abstract model into a shared, actionable blueprint.

## How it works

It begins with extensive discovery, because an operating model designed without understanding the organisation is a generic template, the bolted-on failure the skill exists to avoid. It asks about size and shape, industry and regulatory context, technology and data maturity, geography and footprint, the existing technology estate, the real pain driving the change, the value pools, and the people and culture starting point, pressing and expanding before it designs anything.

Then it does two further jobs that must connect, and in order. First it designs the model substantively across the core components, strategy and value alignment, people and culture, AI-first processes, technology, data and knowledge, governance and autonomy, and the shift from org charts to work charts, with the cross-cutting practices of continuous learning, outcome-based measurement, and maturity progression. Only then does it visualise, because a handsome diagram of a shallow model helps no one.

For the visual, it chooses the format that fits the job: an AI Operating Model Canvas for the whole model on a page, a layered target-operating-model diagram for how AI integrates into existing flows, a workflow or agentic network diagram for how work flows through humans and agents, a governance and autonomy view for where each decision sits on the autonomous-recommend-oversight spectrum, or a maturity heatmap or radar for assessment. It shows AI explicitly and distinctly in every view, always includes autonomy boundaries and governance, and ties each view to outcomes. Rendering defers to the frontend-design skill for diagrams and tufte-viz for data charts.

## When to use it

Reach for it whenever you want to design, assess, or visualise how an organisation operates with AI as a core participant. It triggers on requests like "design an AI-native operating model", "map our AI target operating model", "visualise how AI agents fit into our workflows", "build an AI operating model canvas", or "assess our AI maturity".

## Structure

- `SKILL.md` — the design-before-drawing approach, the components, and the visual formats
- `references/discovery-questions.md` — the extensive discovery to run before designing anything
- `references/operating-model-components.md` — the core components in depth, with why each matters
- `references/visual-frameworks.md` — the catalogue of visual formats, when to use each, and how to construct it

## Installation

Package the folder as a `.skill` file and install it through the skills interface in your Claude client.
