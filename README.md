# Skills

A collection of Claude Skills for reuse across projects. Each skill lives in its own folder under `skills/` and follows the standard layout: a `SKILL.md` with the instructions and metadata, plus an optional `references/` folder for supporting docs that load only when needed.

Built and shared by Hugo Harris. If these are useful to you, you can follow the thinking behind them:

- On X: [@Hugo_C_Harris](https://x.com/Hugo_C_Harris)
- On Substack: [The Humanity Paradox](https://substack.com/@thehumanityparadox)

## Available skills

| Skill | What it does |
|-------|--------------|
| tufte-viz | Design, build, and critique data visualizations using Edward Tufte's principles. Triggers on charts, graphs, dashboards, tables, and any visual display of data. |
| exec-prose | Write and edit executive-level prose in the voice of a senior digital AI consultancy leader. Triggers on emails, memos, strategy notes, board papers, articles, and other professional writing. |
| exec-clarity | Sharpen executive writing so it lands with a senior, time-poor reader. Flags what is weakening a draft and offers a tighter rewrite, learning your voice once and reusing it. Triggers on requests to tighten, clarify, or review writing before it goes out. |
| executivepitchcrafter | Turn raw insights, research, data, or client context into C-level executive deliverables such as one-page summaries, board readouts, LinkedIn articles, team briefs, and keynote outlines. Built on SCQA, the Pyramid Principle, and MECE, with a strictly enforced British essayistic prose style. Triggers on any request for an executive pitch, summary, deck, or keynote. |
| whitepaper-to-social | Turn a whitepaper, report, essay, or article into derivative short-form social posts for LinkedIn, Substack Notes, and X. Presents a tickbox to choose platforms and a second question for volume, then produces posts at a fixed 1:3:5 ratio. Triggers on any request to repurpose long-form content into social posts. |
| idea-refinement | Act as a strategic sounding board that pressure-tests a raw executive idea into a sharp, defensible concept through continuous, adaptive questioning, then produces a one-page concept brief. Triggers when bringing a half-formed idea, venture, or strategy to think through or sharpen. |
| client-engagement-to-collateral | Turn raw client engagement material such as notes, transcripts, or briefs into polished consulting deliverables: proposals, board readouts, cover emails, and discovery summaries. Confirms type and audience, then produces a Word document by default. Triggers on any request to turn engagement input into client-facing collateral. |
| workflow-spotter | Look back over your recent work, find the tasks you keep redoing by hand, and package the ones worth packaging into a reusable skill, a saved process, or an automation. Written for an executive, not a developer. Triggers on "what do I keep repeating", "audit my workflows", or "what should I systematise". |
| competitive-response | Develop a clear-headed strategic response to a competitor's move or market threat. Probes extensively first, then interprets the move, sizes the threat honestly, maps the full response spectrum including doing nothing, and recommends with reasoning shown. Triggers on competitor moves, deal losses, or competitive planning. |
| document-interrogator | Interrogate one or many documents the way a sharp executive reader would, with grounded, cited answers rather than vague summaries. Surfaces the buried decision, the softened risk, and what a sceptic would challenge. Triggers on "what do I need to know in this", "what should I be worried about", or "compare these reports". |
| transformation-business-case | Build a rigorous, honest business case for a digital, technology, or AI transformation investment. Runs NPV, IRR, payback, and TCO correctly while carrying the judgement about where transformation economics break the textbook, the J-curve, foundation value, and the precision trap. Triggers on "build the business case", "justify this spend", or "build or buy". |
| chief-of-staff | Act as a senior executive chief of staff: daily briefings, meeting prep with attendee research, inbox triage, drafted comms in your voice, and follow-up tracking. Interviews you once to learn your priorities and people, then tailors every brief after. Triggers on "give me my morning brief", "prep me for my meetings", or "what should I focus on". |

## Using a skill

Each skill folder contains a packaged `.skill` file you can install directly, alongside the readable source. To install, download the `.skill` file and add it through the skills interface in your Claude client.

If you only want to read or adapt the instructions, open the `SKILL.md` in the relevant folder.

## Repository layout

```
skills/
  chief-of-staff/
    README.md
    SKILL.md
    chief-of-staff.skill
    references/
      onboarding-interview.md
      cos-playbook.md
  client-engagement-to-collateral/
    README.md
    SKILL.md
    client-engagement-to-collateral.skill
    references/
      deliverable-structures.md
      house-style.md
  competitive-response/
    README.md
    SKILL.md
    competitive-response.skill
    references/
      analysis-framework.md
  document-interrogator/
    README.md
    SKILL.md
    document-interrogator.skill
    references/
      interrogation-modes.md
  exec-clarity/
    README.md
    SKILL.md
    exec-clarity.skill
    references/
      diagnostics.md
      formats.md
  exec-prose/
    README.md
    SKILL.md
    exec-prose.skill
  executivepitchcrafter/
    README.md
    SKILL.md
  idea-refinement/
    README.md
    SKILL.md
    idea-refinement.skill
    references/
      question-bank.md
      brief-template.md
  transformation-business-case/
    README.md
    SKILL.md
    transformation-business-case.skill
    references/
      financial-methods.md
      transformation-economics.md
  tufte-viz/
    SKILL.md
    tufte-viz.skill
    references/
      tufte-principles.md
      analytical-design.md
  whitepaper-to-social/
    README.md
    SKILL.md
    whitepaper-to-social.skill
    references/
      platform-voice.md
      ratio-and-counts.md
  workflow-spotter/
    README.md
    SKILL.md
    workflow-spotter.skill
    references/
      shortlist-example.md
LICENSE
README.md
```

## Contributing

To add a skill, create a new folder under `skills/` with its own `SKILL.md`, then add a row to the table above.

## About

These skills come out of the work behind *The Humanity Paradox*, on how senior leaders stay distinctive and effective as AI reshapes the operating model. If that is your terrain too, the writing lives here:

- X: [@Hugo_C_Harris](https://x.com/Hugo_C_Harris)
- Substack: [The Humanity Paradox](https://substack.com/@thehumanityparadox)

## License

Released under the MIT License. See `LICENSE`.
