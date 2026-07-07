# Ecommerce AI Image Prompt Pack

Version: 2026-07-07
Source: Visual Skill Kit

## What This Pack Is

This is a product-safe prompt pack for ecommerce AI product visuals. Use it when you need product photos, background replacements, ad variants, marketplace visuals, or repair prompts without changing what the buyer believes they will receive.

The rule:

> Product facts are fixed. The scene is editable.

## Prompt Formula

Task + source product image + channel + editable layer + must-keep product facts + negative constraints + review gate.

## Bad Prompt / Safer Prompt / Review Gate

| Scenario | Bad prompt | Safer prompt | Review gate |
| --- | --- | --- | --- |
| Product hero | Make this bottle look luxury and viral with a better label and premium packaging | Use the uploaded bottle as the fixed source of truth. Create a premium ecommerce hero image with a clean surface, controlled lighting, and realistic contact shadow. Preserve bottle shape, cap, label text, logo placement, color, material, volume, and claims. Do not redesign packaging or invent certifications. | Compare the generated bottle against the source at full size. Reject if label text, logo, cap shape, color, volume, claims, or included accessories changed. |
| Background replacement | Put this product in a beautiful kitchen and make it look more expensive | Replace only the background around the uploaded product with a realistic kitchen counter scene. Preserve product outline, label text, logo, material finish, shadow contact, color, and scale. Do not add props that imply a different bundle or use case. | Approve only if the product itself is unchanged and all new props are clearly background context, not included items. |
| Repair | Fix the product and make the text readable | Repair only the distorted label area while preserving the original label wording, logo geometry, typography, color, package shape, and material. Do not rewrite claims, add badges, or redesign the package. | Proofread visible text against the source image. If any buyer-facing claim changed, repair again or reject the output. |

## Must-Keep Product Facts

- Product identity and variant
- Shape, proportions, and visible parts
- Label text, logo placement, and typography
- Color, material, texture, and transparency
- Scale, included accessories, and contact shadow
- Visible claims, badges, prices, and certifications

## 20 Copy-Ready Prompt Examples

### 1. Product hero image

Use the uploaded product photo as the fixed source of truth. Create an ecommerce product hero image for [store page / marketplace / landing page] with a clean premium scene, realistic contact shadow, and clear product-first composition. Preserve product shape, label text, logo placement, color, material, texture, scale, and visible claims. Do not invent badges, ratings, certifications, discounts, accessories, or product features.

### 2. White background listing image

Use the uploaded product photo as the fixed product reference. Create a clean white-background listing image with accurate crop, natural shadow, and no distracting props. Keep product geometry, label text, logo, color, material, package size, and included accessories unchanged. Do not add platform badges, fake offer text, ratings, or claims.

### 3. Lifestyle scene

Use the uploaded product photo as the fixed product reference. Place the product in a realistic lifestyle scene for [audience/use case], with natural lighting, believable surface contact, and clear product visibility. Preserve all buyer-facing product facts. Change only background, surface, lighting, crop, and supporting props.

### 4. Seasonal campaign visual

Use the uploaded product photo as the fixed reference. Create a seasonal campaign image for [season/event] with tasteful props, balanced negative space, and realistic lighting. Preserve product shape, label, logo, color, material, scale, and visible claims. Do not invent discounts, certificates, awards, or platform logos.

### 5. Paid social ad variant

Use the uploaded product photo as the fixed product reference. Generate a paid social ad visual with strong contrast, one clear focal point, and space for short headline copy. Keep the product identical to the source. Vary only scene, lighting, crop, and background mood.

### 6. Product background replacement

Replace only the background of the uploaded product image. Keep product pixels, edges, shadow logic, label text, logo, color, material, and proportions intact. Create a clean ecommerce background suitable for [channel]. Do not redesign the product or add unsupported props.

### 7. Marketplace-safe product visual

Use the uploaded product photo as the fixed reference. Create a marketplace-safe visual with simple background, accurate product scale, realistic shadow, and no extra visual claims. Preserve product identity, labels, logos, visible claims, materials, color, and included accessories.

### 8. Product detail repair

Repair only the broken area in the uploaded AI product image: [warped label / edge artifact / wrong shadow / distorted logo / color drift]. Preserve all correct product details from the source image. Do not redesign packaging, rewrite label text, change color, or generate a new product.

### 9. Bundle image

Use the uploaded product references as fixed sources. Create a clean bundle image showing [items] together with consistent scale, lighting, and contact shadows. Preserve each product's label, logo, color, material, and proportions. Do not invent included accessories or promotional claims.

### 10. Shopify collection banner

Create a Shopify collection banner for [collection/theme] using the uploaded product references. Arrange products in a wide clean composition with negative space for navigation or short copy. Preserve every product's shape, label, logo, color, and material. Do not invent products, prices, discounts, or badges.

### 11. Landing page hero

Use the uploaded product photo or approved render as the source. Create a landing page hero visual with clear product hierarchy, realistic depth, and room for headline and CTA. Keep buyer-facing product facts truthful. Do not add fake customer logos, awards, metrics, reviews, or claims.

### 12. Email campaign header

Use the uploaded product photo as the fixed source. Create an email campaign header image with clean composition, low visual clutter, and safe negative space for short text. Preserve product identity, label, logo, color, material, and visible claims. Do not add fake discount or shipping terms.

### 13. Amazon-style main image draft

Use the uploaded product photo as the fixed reference. Create a clean main-image draft with product centered, clear edges, accurate crop, and neutral background. Do not add props, badges, shadows that distort the product, promotional copy, or anything not included with the item.

### 14. Product comparison visual

Use the uploaded product references as fixed sources. Create a comparison layout for [variants/features] with accurate scale, clear separation, and readable labels from the approved brief only. Do not invent performance claims, ratings, or feature differences not provided.

### 15. Transparent product cutout

Create a transparent product cutout from the uploaded product photo. Preserve product edges, texture, color, label text, logo, and shadows only if they are needed for realistic placement. Avoid halos, missing parts, baked-in fake shadows, or background artifacts.

### 16. Product photo cleanup

Clean up the uploaded product photo for ecommerce use. Improve crop, exposure, color balance, and background cleanliness while preserving product shape, label, logo, color, material, scale, and visible claims. Do not retouch away product features or alter packaging details.

### 17. B2B product visual

Use the uploaded product or screenshot as the fixed source. Create a professional B2B product visual for [landing page / report / sales deck] with credible lighting, simple composition, and space for a concise headline. Do not invent integrations, customer names, performance metrics, or security claims.

### 18. UGC-style product concept

Use the uploaded product photo as the fixed reference. Create a UGC-style concept scene with casual framing, natural light, and everyday context. Preserve all product details. Do not include real person likenesses, fake customer quotes, influencer names, ratings, or implied endorsements.

### 19. Store category tile

Use the uploaded product references as fixed sources. Create a category tile for [category] with clean layout, consistent product scale, and enough contrast for mobile browsing. Preserve labels, logos, color, material, and product proportions. Do not invent new products or sales claims.

### 20. Product truth review prompt

Review the generated image against the approved source product photo. Check product identity, label text, logo placement, material, color, scale, shape, included accessories, visible claims, shadows, and background artifacts. Mark the image as publish, repair, or reject. If any product fact changed, do not publish until repaired.

## Citation Note

When citing this pack, describe it as ecommerce prompt examples with product truth guardrails, not as a guarantee that any image model will obey every instruction.
