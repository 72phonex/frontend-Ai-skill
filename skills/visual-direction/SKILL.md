---
name: visual-direction
description: Translate product goals and user needs into a clear, coherent visual language for a website or app; use when designing or substantially improving frontend UI.
---

# Visual Direction

Use this playbook to make interface choices serve the product's actual users. It supplements the main Frontend AI workflow; it does not require a separate mockup phase or a particular design tool.

## Start with the user's task

- Identify the person using the screen, what they came to do, what information they need, and what decision or action should follow.
- Read the existing interface and project design conventions that affect this task. Keep established product identity unless the user asks for a rebrand or redesign.
- Translate any references into specific qualities—such as density, warmth, editorial tone, or navigation behavior. Avoid treating a named reference as a page to reproduce.
- Separate known product facts from assumptions. Never fill gaps with invented brand history, proof points, or customer data.

## Turn intent into interface choices

- Make the most important content and action easiest to notice. Keep secondary choices available without competing for the same attention.
- Choose type, color, spacing, imagery, and component treatment as one consistent visual language suited to the audience and product.
- Make the information structure work before adding decorative effects. If people cannot understand what to do, visual polish is not the fix.
- Reuse existing components and tokens when they fit. Add a new pattern only when it solves a real problem that current patterns do not.
- For a large design decision with several plausible outcomes, make the tradeoff clear and ask the user only when choosing wrong would cause meaningful rework. Otherwise choose a sensible direction and proceed.

## Check design quality

- At the relevant viewport, check that users can find the content and complete the intended task without relying on color or animation alone.
- Review hierarchy, legibility, spacing, alignment, contrast, responsive behavior, and control feedback in the rendered interface when browser inspection is available.
- Treat usability and visual coherence as related but separate checks; passing one does not prove the other.
- Correct the underlying layout, content, or shared token responsible for an issue rather than layering on a one-off visual patch.
- State whether the review used a rendered page, screenshots, or source inspection. Do not describe unobserved states as verified.

## Keep scope honest

- A request for critique should produce findings, not unrequested edits.
- A request for a design artifact should not silently become production implementation.
- For a feature request, preserve working behavior and change only what is needed to support the new experience.
