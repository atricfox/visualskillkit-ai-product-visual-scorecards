# AI Product Photography Product Truth Scorecard

Version: 2026-07-06
Source: Visual Skill Kit workflow framework

## What This Scorecard Is

This is a review protocol for AI-assisted ecommerce product images. It is not a model benchmark and does not claim that one generator is better than another.

Use it when an AI tool creates or edits a product image from a real product reference. The goal is to decide whether the image can be published, needs local repair, or should be rejected.

## The Rule

Product facts are fixed. The scene is editable.

Fixed product facts:

- Product identity
- Variant, pack size, and included accessories
- Shape, geometry, and proportions
- Label text and logo placement
- Material, color, texture, transparency, and finish
- Visible claims, badges, certifications, prices, and offer details

Editable layer:

- Background
- Surface
- Lighting
- Crop
- Composition
- Negative space
- Campaign mood
- Channel layout

## Review Method

Compare the AI output against the approved source image at full size.

Score each item:

- 2 = Pass
- 1 = Needs repair
- 0 = Reject

If any product fact scores 0, do not publish the image until repaired or regenerated from a safer workflow.

## Product Truth Tests

| Test | Question | Score |
| --- | --- | --- |
| Identity | Would the buyer recognize the exact same product and variant? | 0 / 1 / 2 |
| Shape | Are proportions, silhouette, edges, and visible parts unchanged? | 0 / 1 / 2 |
| Label | Are label words, typography, and placement still faithful? | 0 / 1 / 2 |
| Logo | Is logo geometry, color, and placement unchanged? | 0 / 1 / 2 |
| Material | Does the finish still match the real product? | 0 / 1 / 2 |
| Color | Are color, variant, transparency, and texture truthful? | 0 / 1 / 2 |
| Scale | Does the product scale make sense against props or hands? | 0 / 1 / 2 |
| Shadow | Do contact shadows and reflections support the product instead of deforming it? | 0 / 1 / 2 |
| Claims | Were no fake claims, badges, reviews, discounts, or certifications added? | 0 / 1 / 2 |
| Channel | Would the image pass store, marketplace, ad, or landing-page review? | 0 / 1 / 2 |

## Decision Rules

| Total | Decision |
| ---: | --- |
| 18-20 | Publish after final channel review |
| 14-17 | Repair the failed details before publishing |
| 0-13 | Reject or regenerate with narrower edit scope |

Automatic reject:

- Product variant changed
- Label or logo rewritten
- Fake certification, rating, price, claim, endorsement, or marketplace badge added
- Product size, included accessories, or material misrepresented
- The image implies a buyer will receive something different

## Citation Note

When citing this scorecard, describe it as a workflow review protocol for AI product photography, not as an empirical model benchmark.

