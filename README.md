# claude-algorithmic-art-skill

A Claude Code skill for creating original generative artwork through computational processes and interactive p5.js sketches.

## Overview

This skill approaches generative art as a two-stage creative process. First, define an algorithmic philosophy that explains the visual idea and the rules that produce it. Then express that philosophy through code using seeded randomness, mathematical structures, and controlled variation.

The result should be an original artwork, not a reproduction of an existing artist's distinctive work.

## Main Capabilities

- Develop a computational visual concept.
- Translate a philosophy into generative rules.
- Build p5.js sketches.
- Use seeded randomness for reproducible output.
- Explore flow fields, particles, noise, and emergent systems.
- Expose parameters for controlled variation.
- Create interactive viewers for exploring seeds and settings.
- Produce self-contained HTML and JavaScript artifacts.

## Design Process

### 1. Create the Algorithmic Philosophy

Describe the central visual idea, the system's behavior, and the relationship between mathematical rules and the resulting composition.

### 2. Define the Generative System

Choose the primitives, fields, forces, randomness, constraints, and parameters that will create the visual result.

### 3. Implement the Sketch

Use p5.js to translate the system into a reproducible algorithm. Keep the generator logic separate from the viewer controls where practical.

### 4. Explore Parameters

Expose a small set of meaningful controls. Use a fixed seed when comparing changes and a new seed when exploring variation.

### 5. Export and Review

Check composition, performance, visual balance, and reproducibility. Save the settings needed to regenerate an output.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-algorithmic-art-skill.git ~/.claude/skills/algorithmic-art
```

## Usage

Invoke the skill for generative-art tasks:

```text
/algorithmic-art
```

Describe the subject, mood, visual constraints, desired interaction, and output format.

## Templates

The repository includes:

- `templates/generator_template.js`: Starting structure for a generative algorithm.
- `templates/viewer.html`: Interactive viewer structure for seeds and parameters.

Use the templates as implementation starting points and adapt them to the artwork's own system.

## Good Generative Art Practices

- Use seeded randomness for reproducibility.
- Keep parameters meaningful and bounded.
- Avoid uncontrolled visual noise.
- Make the algorithm express the concept rather than decorate it.
- Keep rendering performance in mind.
- Separate artistic intent from implementation details.
- Test multiple seeds and parameter combinations.
- Preserve the settings used for final exports.

## Repository Contents

- `SKILL.md`: Main creative and implementation workflow.
- `templates/generator_template.js`: Generator template.
- `templates/viewer.html`: Interactive viewer template.
- `README.md`: Process, usage, and design guidance.

## Output Expectations

A typical project can include a written philosophy, a JavaScript generator, and an HTML viewer. The exact files depend on the requested deliverable.

## Quality Checklist

- The concept is distinct and understandable.
- The algorithm produces intentional visual structure.
- Seeds reproduce the same output.
- Parameters have clear effects.
- The artwork remains performant.
- Exported files render correctly.
- The final composition has been visually reviewed.

## Supporting Resources

| File | Purpose |
|---|---|
| [Algorithmic philosophy brief](resources/algorithmic-philosophy-brief.md) | Shape the generative concept and translate it into computational rules. |
| [Seed reproducibility checklist](resources/seed-reproducibility-checklist.md) | Verify deterministic output, parameter state, and export behavior. |
| [Artwork quality review](resources/artwork-quality-review.md) | Review originality, composition, performance, viewer controls, and exports. |

The existing templates/generator_template.js and templates/viewer.html are retained unchanged. The viewer is the starting point for the skill's interactive artifact workflow. The new resources complement those templates; they do not replace them.
