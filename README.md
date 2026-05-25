# Skills

A collection of Claude Skills for senior leaders and the people who work alongside them. They are built for the executive who is time-poor and judgement-rich: someone who does not need another tool that produces generic output, but a set of capabilities that carry real operating judgement, ask the right questions before they answer, and hold the standard a good adviser would. If you write to a board, advise a C-suite, run competitive bids, lead a function, or are stepping into a new role, these are built for your week.

They come out of doing the work. I am Hugo Harris, Head of Cognizant Moment for Asia Pacific and Japan, where I lead experience transformation and AI-enabled operating-model work for large enterprises across the region, and I am writing a book, *The Humanity Paradox*, on how leaders stay distinctive and effective as AI reshapes how organisations run. Each skill here is drawn from real executive and client-delivery work over the last decade plus rather than assembled from theory, which is why they tend to interrogate the situation before producing anything and to tell you the unwelcome truth rather than the comfortable one. The bid suite reflects how competitive proposals are actually won and lost; the advisory skills reflect how real decisions get pressure-tested; the writing skills hold an executive register rather than a generic one.

If the thinking behind them is useful, you can follow it here:

- On X: [@Hugo_C_Harris](https://x.com/Hugo_C_Harris)
- On Substack: [The Humanity Paradox](https://substack.com/@thehumanityparadox)

Each skill lives in its own folder under `skills/` with a `SKILL.md` holding the instructions and metadata, plus an optional `references/` folder for supporting material that loads only when needed.

## Available skills

The collection covers the working life of a senior executive: writing and communication, advisory and decision-making, client delivery, the full competitive-bid lifecycle, and running the office around a leader.

### Writing and communication

| Skill | What it does |
|-------|--------------|
| exec-prose | Write and edit executive-level prose in the voice of a senior digital AI consultancy leader. Triggers on emails, memos, strategy notes, board papers, articles, and other professional writing. |
| exec-clarity | Sharpen executive writing so it lands with a senior, time-poor reader. Flags what is weakening a draft and offers a tighter rewrite, learning your voice once and reusing it. |
| executivepitchcrafter | Turn raw insights, research, data, or client context into C-level deliverables: one-page summaries, board readouts, LinkedIn articles, team briefs, keynote outlines. Built on SCQA, the Pyramid Principle, and MECE. |
| whitepaper-to-social | Turn a whitepaper, report, or essay into derivative short-form social posts for LinkedIn, Substack Notes, and X. Tickbox platform choice, then a fixed 1:3:5 ratio. |

### Advisory and decision-making

| Skill | What it does |
|-------|--------------|
| idea-refinement | A strategic sounding board that pressure-tests a raw idea into a sharp, defensible concept through adaptive questioning, then produces a one-page concept brief. |
| competitive-response | Develop a clear-headed response to a competitor's move. Probes first, sizes the threat honestly, maps the full response spectrum including doing nothing, and recommends with reasoning shown. |
| transformation-business-case | Build a rigorous, honest business case for a digital, technology, or AI transformation. Runs NPV, IRR, payback, and TCO while carrying the judgement about the J-curve, foundation value, and the precision trap. |
| first-90-days | Help a new executive win their first 90 days. Diagnoses the transition (STARS, internal or external, team state) then builds a tailored 30-60-90 plan, drawing on the major works on executive transition. |

### Knowledge and analysis

| Skill | What it does |
|-------|--------------|
| document-interrogator | Interrogate one or many documents the way a sharp executive reader would, with grounded, cited answers. Surfaces the buried decision, the softened risk, and what a sceptic would challenge. |
| tufte-viz | Design, build, and critique data visualizations using Edward Tufte's principles. Triggers on charts, graphs, dashboards, tables, and any visual display of data. |
| workflow-spotter | Look back over your recent work, find what you keep redoing by hand, and package the worthwhile ones into a reusable skill, saved process, or automation. Written for an executive, not a developer. |

### The competitive-bid lifecycle

| Skill | What it does |
|-------|--------------|
| win-themes | Develop evaluator-ready win themes for a bid. Probes the client, scoring, competition, and differentiators, then builds one to three themes on the Capability-Value-Differentiator structure, each backed by proof. |
| rfp-response-plan | Turn a received RFP into a backward-planned response plan and tracker. Questions the team's approval process, structure, and workstreams, then produces a Word plan and an Excel tracker. |
| red-team-review | Review a near-final proposal as the client's evaluation panel would. Asks who is scoring and whether an external advisor is involved, then scores against the criteria and forces specific fixes. |
| orals-prep | Prepare a team to win the oral presentation stage. Drills the message, speakers, and Q&A, then runs Mock Orals as a formal independent review gate scoring content, delivery, and Q&A. |

### Running the office

| Skill | What it does |
|-------|--------------|
| chief-of-staff | Act as a senior chief of staff: daily briefings, meeting prep with attendee research, triage, drafted comms, and follow-up tracking. Interviews you once to learn your priorities and people, then tailors every brief. |
| client-engagement-to-collateral | Turn raw client engagement material into polished deliverables: proposals, board readouts, cover emails, discovery summaries. Confirms type and audience, then produces a Word document by default. |

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
  first-90-days/
    README.md
    SKILL.md
    first-90-days.skill
    references/
      frameworks.md
      ninety-day-plan.md
  idea-refinement/
    README.md
    SKILL.md
    idea-refinement.skill
    references/
      question-bank.md
      brief-template.md
  orals-prep/
    README.md
    SKILL.md
    orals-prep.skill
    references/
      orals-intake.md
      presentation-and-qa.md
      mock-orals-gate.md
  red-team-review/
    README.md
    SKILL.md
    red-team-review.skill
    references/
      review-actions.md
  rfp-response-plan/
    README.md
    SKILL.md
    rfp-response-plan.skill
    references/
      intake-questions.md
      plan-structure.md
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
  win-themes/
    README.md
    SKILL.md
    win-themes.skill
    references/
      discovery-questions.md
      cvd-construction.md
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

To add a skill, create a new folder under `skills/` with its own `SKILL.md`, then add a row to the relevant table above.

## About

These skills come out of the work behind *The Humanity Paradox*, on how senior leaders stay distinctive and effective as AI reshapes the operating model. If that is your terrain too, the writing lives here:

- X: [@Hugo_C_Harris](https://x.com/Hugo_C_Harris)
- Substack: [The Humanity Paradox](https://substack.com/@thehumanityparadox)

## License

Released under the MIT License. See `LICENSE`.
