# Skills

A collection of Claude Skills for reuse across projects. Each skill lives in its own folder under `skills/` and follows the standard layout: a `SKILL.md` with the instructions and metadata, plus an optional `references/` folder for supporting docs that load only when needed.

## Available skills

| Skill | What it does |
| --- | --- |
| [`tufte-viz`](skills/tufte-viz/) | Design, build, and critique data visualizations using Edward Tufte's principles. Triggers on charts, graphs, dashboards, tables, and any visual display of data. |
| [`exec-prose`](skills/exec-prose/) | Write and edit executive-level prose in the voice of a senior digital AI consultancy leader. Triggers on emails, memos, strategy notes, board papers, articles, and other professional writing. |
| [`executivepitchcrafter`](skills/executivepitchcrafter/) | Turn raw insights, research, data, or client context into C-level executive deliverables such as one-page summaries, board readouts, LinkedIn articles, team briefs, and keynote outlines. Built on SCQA, the Pyramid Principle, and MECE, with a strictly enforced British essayistic prose style. Triggers on any request for an executive pitch, summary, deck, or keynote. |

## Using a skill

Each skill folder contains a packaged `.skill` file you can install directly, alongside the readable source. To install, download the `.skill` file and add it through the skills interface in your Claude client.

If you only want to read or adapt the instructions, open the `SKILL.md` in the relevant folder.

## Repository layout

```
skills/
  tufte-viz/
    SKILL.md              # instructions + metadata
    tufte-viz.skill       # packaged, installable
    references/
      tufte-principles.md
      analytical-design.md
  exec-prose/
    README.md
    SKILL.md              # instructions + metadata
    exec-prose.skill      # packaged, installable
  executivepitchcrafter/
    README.md
    SKILL.md              # instructions + metadata
LICENSE
README.md
```

## Contributing

To add a skill, create a new folder under `skills/` with its own `SKILL.md`, then add a row to the table above.

## License

Released under the MIT License. See LICENSE.
