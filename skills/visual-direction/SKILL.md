---
name: visual-direction
description: Establish visual direction, interface hierarchy, responsive layouts, and screenshot-based review for websites and product UI.
---

# Visual Design and UI Review

Use this playbook when a task needs strong design judgment, a redesign, a new product interface, a component polished to a high standard, or visual review.

## Direction

- Write a concise design north star from the product, audience, and user's references. Keep product references (what it is) distinct from interaction or style references (how it should feel or behave).
- Offer one well-reasoned direction by default. Make multiple alternatives only when the user asks to compare them.
- Separate design artifacts from implemented product code. Do not change business behavior when the request is design-only.
- If an existing project's brand and UI conventions are clear, preserve them for incremental features. For a requested redesign, retain the brand assets while correcting accidental or inconsistent visual defaults.

## Structure before styling

- Start with a simple content hierarchy or grayscale wireframe. Identify each view's primary content, primary action, secondary actions, and important states.
- Ensure the task flow and information hierarchy work before applying color, imagery, or animation. Use visual decoration to support the structure, not conceal problems.
- Design only the responsive breakpoints and states that change the layout or interaction; do not duplicate every screen without reason.
- Implement one representative page or flow first, verify the direction, then apply its reusable patterns to related views.

## Visual review

- Inspect the page in its actual rendered state at relevant viewport sizes. A source-code read alone is not visual verification.
- Review hierarchy, typography, spacing, contrast, alignment, density, image crops, interaction feedback, and responsive behavior.
- Keep usability and aesthetics as distinct review questions. A beautiful screen must still support the user's task.
- Use an independent reviewer only when the task and available tools justify it. Give the reviewer concrete criteria and rendered evidence, not vague instructions to "make it better."
- Fix issues at their source in shared tokens or components where appropriate. Recheck affected screens after changes.

## Scope and handoff

- Ask a focused question only when a missing choice changes the core visual direction; otherwise choose a reversible default and state it.
- If the user asks for critique only, do not edit files. If the user asks for a design artifact, do not silently turn it into production code.
- Describe what was actually rendered or inspected, and disclose any visual checks that were unavailable.
