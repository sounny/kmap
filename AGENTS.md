# Agent Working Memory

## Purpose
This file tracks the actions, observations, and reasoning performed by autonomous agents working on the `kmap` project. Future agents should append their notes chronologically to preserve continuity and share important context.

## Log
### 2024-08-29
- **Agent:** gpt-5-codex
- **Task:** Create a persistent working-memory AGENTS file and add a project README.
- **Actions:**
  - Inspected the repository and noted it currently contains a single `index.html` implementing the Orbital Logic Synthesizer interface and logic.
  - Authored this working-memory document to capture intent and guidance for subsequent contributors.
  - Drafted a comprehensive `README.md` describing the project purpose, features, and contribution workflow.
- **Thoughts:**
  - The project appears to be a browser-based Karnaugh map simplifier and circuit visualizer; the README should highlight the interactive features and describe how to run the app locally.
  - Encourage future agents to continue appending to this log with clear timestamps and actionable insights.
  - Consider adding more detailed developer setup instructions if build tooling or dependencies expand beyond the current static HTML implementation.

### 2026-02-08
- **Agent:** gpt-5-codex
- **Task:** Improve the app as a teaching tool.
- **Actions:**
  - Added a new “Learning Walkthrough” panel that explains canonical minterms, grouping strategy, and the final simplified expression.
  - Added term-by-term group explanations showing covered minterms, derived term, and group size.
  - Added helper guidance text near the expression output and fixed canvas text/stroke colors to a valid value for circuit rendering.
  - Captured an updated UI screenshot for documentation of the teaching-oriented changes.
- **Thoughts:**
  - The walkthrough now gives learners immediate context for why each grouped region contributes a specific product term.
  - A future improvement could include toggling individual groups on/off for interactive what-if exploration.

### 2026-03-14
- **Agent:** gpt-5-codex
- **Task:** Make the app a better teaching tool.
- **Actions:**
  - Added lesson presets so learners can load curated 2-, 3-, and 4-variable examples with one click.
  - Expanded the walkthrough with literal-count metrics that compare canonical vs simplified complexity.
  - Added a quick-check quiz card that generates random input assignments and supports reveal/regenerate interactions.
  - Updated UI styling to support inline preset controls and quiz action controls.
- **Thoughts:**
  - Presets lower the barrier for first-time learners who do not yet know which minterm sets create interesting K-map behavior.
  - Quantifying literal savings helps students connect grouping decisions to implementation cost.
