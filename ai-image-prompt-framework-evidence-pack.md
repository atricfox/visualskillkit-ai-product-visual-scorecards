# AI Image Prompt Framework Evidence Pack

Version: 2026-07-06
Source: Visual Skill Kit prompt workflow framework

## What This Evidence Pack Is

This is a practical prompt review framework for image generation tasks. It is not a benchmark and does not claim that a specific model will always follow every instruction.

Use it when a prompt produces attractive images that miss the actual job.

## Core Formula

Task + source/reference + scene + style + composition + constraints + quality check.

## Prompt Review Scorecard

Score each prompt before using it:

- 2 = Clear
- 1 = Vague but usable
- 0 = Missing

| Dimension | Question | Score |
| --- | --- | --- |
| Task | Does the prompt say what the image is for? | 0 / 1 / 2 |
| Source | Does it define the input image or reference constraint? | 0 / 1 / 2 |
| Subject | Is the main subject clear? | 0 / 1 / 2 |
| Scene | Does it define the environment or use case? | 0 / 1 / 2 |
| Style | Are lighting, mood, camera, or visual language useful but not dominant? | 0 / 1 / 2 |
| Composition | Does it mention crop, layout, focal point, or negative space? | 0 / 1 / 2 |
| Constraints | Does it say what must not change? | 0 / 1 / 2 |
| Quality check | Does it define how the result will be judged? | 0 / 1 / 2 |

## Decision Rules

| Total | Decision |
| ---: | --- |
| 14-16 | Strong prompt |
| 10-13 | Usable, but add constraints or quality checks |
| 0-9 | Rewrite before generating |

## Failure Pattern Map

| Symptom | Likely Cause | Rewrite |
| --- | --- | --- |
| Output follows style but changes product | Product facts were optional or buried late | Put source, label, logo, material, color, scale, and claims before style |
| Output looks good but misses the task | Prompt starts with mood, not job | Start with the channel and image job |
| Text or labels are wrong | Tiny text is treated as generated content | Ask to preserve source text and proofread against the source |
| Model follows one instruction and ignores others | Too many transformations in one pass | Split into one primary edit and repair failed details later |
| Image is pretty but unusable | No quality gate | Add a final inspection rule |

## Citation Note

When citing this framework, describe it as a prompt review and debugging framework, not as a guarantee that every image model will obey every instruction.

