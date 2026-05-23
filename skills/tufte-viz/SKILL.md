---
name: tufte-viz
description: |
  Design, build, and critique data visualizations using Edward Tufte's principles. Use this skill WHENEVER the work involves a chart, graph, plot, dashboard, table, diagram, or any visual display of data, even if the user does not name Tufte or "data viz" explicitly. Triggers include:
  (1) Building a new chart, graph, plot, or figure (bar, line, scatter, time-series, small multiples, sparkline, etc.)
  (2) Designing or reviewing a dashboard, report, or slide with quantitative visuals
  (3) Critiquing or improving an existing visualization
  (4) Choosing between visualization approaches ("what's the best way to show this?")
  (5) Reducing chartjunk, improving the data-ink ratio, or fixing a misleading chart
  (6) Planning high-density displays, comparisons, or part-to-whole views
  Applies data-ink ratio, chartjunk elimination, graphical integrity, lie factor, small multiples, layering, sparklines, and analytical design. Consult before producing any chart so output is clear, honest, and high-density.
---

# Tufte Data Visualization

Apply Edward Tufte's principles to produce clear, honest, high-density visualizations, and to critique existing ones. The goal is always the same: maximize the information the viewer extracts per unit of ink and pixel, while never distorting what the data say.

## Core stance

Before drawing anything, hold three questions in mind. What comparison is the viewer meant to make. What is the single insight that must survive a glance. Who is reading it and at what distance. A chart that cannot answer "compared to what?" is usually the wrong chart.

The default aesthetic is restraint. Start from almost nothing and add only marks that carry data. Grayscale is the baseline; color is reserved for encoding a variable or flagging one thing that matters. If an element can be erased without losing information, erase it.

## Workflow for building a new visualization

1. **Clarify the data story.** Identify the key comparison, the headline insight, and the audience. Write it in one sentence before choosing a chart type. If the data are multivariate, resist collapsing to a single variable just to simplify, because the interaction is often the point.

2. **Select the approach** using the principles rather than habit:
   - High need to compare across categories, periods, or conditions → small multiples (identical scales, identical encoding, tight spacing).
   - Dense data where precise values matter → a well-set table, often beating a chart.
   - Trend or shape across time → line chart with a muted or absent grid; consider a range-frame axis that spans only the actual data.
   - Many metrics at once, shape mattering more than exact value → sparklines, one row per metric with the current value and delta beside it.
   - Part-to-whole → bar or table, almost never a pie, and never a 3D pie.
   - Causality or mechanism → put the intervention and the response in one frame and annotate the mechanism directly.

3. **Design with data-ink in mind.** Begin minimal. Every gridline, tick, border, and label must earn its place. Push secondary elements (grids, reference lines, axes) into the background by lightening them so the data dominate; this is layering, and it lets dense displays stay readable.

4. **Protect integrity.** Keep the lie factor near 1, meaning the size of the effect shown matches the size of the effect in the data. Use consistent baselines, do not truncate axes to exaggerate change, and never use area or volume to encode a linear quantity. Label thoroughly and cite the source, because documentation is what lets a stranger trust the evidence.

5. **Apply the Tufte test** in `references/tufte-principles.md` before calling it done. For dashboards, dense displays, sparklines, or explanatory graphics, also work through the extended test in `references/analytical-design.md`.

## Workflow for critiquing an existing visualization

1. **Check graphical integrity first.** Estimate the lie factor if proportions look off. Verify baselines, scales, and intervals. Look for 3D applied to 2D data, which almost always distorts.

2. **Find the chartjunk.** Decorative elements, heavy grids, moiré patterns, gratuitous gradients, and any "duck" where the design promotes itself over the data.

3. **Evaluate the data-ink ratio.** Ask what can be erased and what is redundant, then say so specifically.

4. **Walk the six principles of analytical design** (in `references/analytical-design.md`). The lowest-scoring principle is usually the largest improvement opportunity.

5. **Give specific before/after recommendations**, not general praise. Name the element, name the fix, name the principle it serves.

## Producing the actual artifact

When generating a chart in code, the principles translate directly: remove default chartjunk that libraries add (heavy borders, dark gridlines, drop shadows, 3D), set a grayscale palette and reserve one accent color, label series directly at the line ends rather than relying on a legend where possible, and set axes to the data range. Prefer formats that render as artifacts the user can inspect. A static, honest, well-labeled figure beats an interactive one with distortion built in.

## Reference files

- `references/tufte-principles.md` — core principles from *The Visual Display of Quantitative Information*: graphical excellence, integrity and the lie factor, data-ink ratio, chartjunk, small multiples, data density, multifunctioning elements, plus the seven-question Tufte test. Read when designing or critiquing any single chart.
- `references/analytical-design.md` — extensions from *Envisioning Information*, *Visual Explanations*, and *Beautiful Evidence*: the six principles of analytical design, sparklines, layering and separation, micro/macro design, range-frames and dot-dash plots, confections, and causality, plus the extended test. Read when designing dashboards, dense displays, sparklines, explanatory graphics, or anything multivariate.

## Quick checklist

- [ ] Lie factor ≈ 1.0, honest baselines, no 3D on 2D data
- [ ] Maximum data-ink ratio; non-data marks erased
- [ ] Zero chartjunk
- [ ] Answers "compared to what?"
- [ ] Shows causality or mechanism where relevant
- [ ] Multivariate where the data warrant it, not over-reduced
- [ ] Words, numbers, and images integrated, not segregated
- [ ] Reveals both macro pattern and micro detail
- [ ] Layering: primary data dominates, secondary recedes
- [ ] Clear labeling, sources, and scales
- [ ] Appropriate data density
