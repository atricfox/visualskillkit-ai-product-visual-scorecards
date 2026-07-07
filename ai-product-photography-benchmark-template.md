# AI Product Photography Benchmark Template

Version: 2026-07-07
Source: Visual Skill Kit

## What This Benchmark Is

This is a small product truth benchmark template for ecommerce AI product photography.

Use it before writing a tool comparison, choosing a production workflow, or publishing generated product images.

It is not a model leaderboard. It is a repeatable review template for product truth.

Every tested image should end with one decision: Publish, repair, or reject.

## Test Matrix

| Product Category | Scene 1 | Scene 2 | Scene 3 | Key Failure Risks |
| --- | --- | --- | --- | --- |
| Bottle or jar | Studio background | Lifestyle surface | Paid social crop | Label drift, reflection drift, cap deformation |
| Box or pouch | Marketplace image | Seasonal background | Landing page hero | Package geometry, typography, fake badges |
| Transparent or glossy product | White background | Dark surface | Shelf-style scene | Transparency, finish, contact shadow |
| Apparel or soft goods | Flat lay | Model-free lifestyle | Ad variant | Fabric texture, scale, color drift |
| Accessory or small object | Macro crop | Bundle image | Comparison layout | Scale, missing parts, invented accessories |

## Product Truth Checks

Score each check:

- 2 = Pass
- 1 = Needs repair
- 0 = Reject

| Check | Question | Score |
| --- | --- | --- |
| Identity | Is the same product and variant preserved? | 0 / 1 / 2 |
| Label and logo | Are label text and logo geometry preserved? | 0 / 1 / 2 |
| Material and color | Are finish, texture, transparency, and color truthful? | 0 / 1 / 2 |
| Geometry and scale | Are proportions, shadows, contact points, and scale believable? | 0 / 1 / 2 |
| Claims and channel | Were no unsupported claims, badges, ratings, or platform marks added? | 0 / 1 / 2 |

## Decision Rules

| Score | Decision |
| ---: | --- |
| 18-20 | Publish after final channel review |
| 14-17 | Repair failed details before publishing |
| 0-13 | Reject or regenerate with narrower edit scope |

## Benchmark Record Template

| Product | Scene | Tool / Workflow | Prompt Version | Product Truth Score | Decision | Notes |
| --- | --- | --- | --- | ---: | --- | --- |
| | | | | | Publish / Repair / Reject | |

## Citation Note

When citing this benchmark, describe it as a small workflow review template for ecommerce AI product photography, not as an empirical ranking of image models.
