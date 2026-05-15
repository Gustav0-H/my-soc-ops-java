# Copilot Instructions

This repository uses GitHub Copilot guidance to help maintain a consistent design and development experience.

## Design Guide

- Aim for a playful, bright visual language with soft gradients, rounded shapes, and friendly iconography.
- Use the existing CSS utilities in `socops/src/main/resources/static/css/app.css` to keep styling consistent and avoid introducing raw CSS styles where possible.
- Prefer composable utility classes such as `.flex`, `.grid`, `.rounded-xl`, `.shadow-xl`, `.bg-accent`, and `.text-slate-900`.
- Keep UI elements approachable: use clear headings, spacing, and button states with subtle hover/active interactions.
- Apply color accents sparingly to guide attention to primary actions like `Start Game`, `Keep Playing`, and victory banners.
- Use simple motion and animation for delight, such as gentle bounce effects or background sparkles, while keeping interactions accessible.

## Coding Practices

- Maintain the existing Java Spring Boot structure under `socops/src/main/java/com/socops/`.
- Keep templates in `socops/src/main/resources/templates/` and static assets in `socops/src/main/resources/static/`.
- Prefer small, reusable UI components and avoid excessive page complexity.
- For any new feature, ensure the app still builds with `./mvnw clean package` and passes the current test suite.

## Development Checklist

- Follow the existing project conventions for naming and architecture.
- Check styling against the `css-utilities.instructions.md` guidance and avoid duplicated CSS rules.
- Use the GitHub Actions workflow at `.github/workflows/ci.yml` as the standard CI target.
