# Copilot Instructions

This file provides guidance for GitHub Copilot when working in this repository.

## Design Guide

When contributing design or frontend changes, follow these guidelines:

- Aim for memorable and polished visual direction.
- Avoid generic UI patterns and overused fonts. Choose thoughtful, distinctive typography.
- Prefer a cohesive theme rather than mixing too many colors or visual styles.
- Use the existing CSS utilities in `socops/src/main/resources/static/css/app.css` and add new classes only when needed.
- Keep CSS specificity low: prefer utility classes and composable styles over deeply nested selectors.
- Favor atmosphere and mood over minimal tweaks. Background gradients, subtle textures, and layered lighting can make a retro aesthetic feel intentional.
- Use animation sparingly for high-impact moments: page reveal, button press, victory feedback.
- Preserve accessibility: ensure buttons are tappable, text contrast is readable, and interactive elements have clear affordance.
- Maintain the core game experience: the redesign should enhance the social bingo flow, not obscure it.

## Frontend Work

- Start by reviewing the layout in `socops/src/main/resources/templates/game.html`.
- Keep interactions simple and semantic; the project uses server-rendered Thymeleaf templates and inline script logic.
- Test locally by running `cd socops && ./mvnw spring-boot:run` and opening the app.

## Styling Practices

- Reuse existing utility classes before adding new ones.
- Add new utilities to `app.css` only when the design needs a reusable style.
- Avoid hardcoded pixel values unless necessary for the visual effect.
- Keep the design consistent with the project’s current aesthetic and domain.

## Notes

- Do not add credentials, secrets, or external third-party components without explicit direction.
- Focus on a clean implementation that is easy to maintain and matches the repository’s existing structure.
