# Plan

## Story

As a user, I want to switch between light and dark themes, so that I can use the dashboard comfortably in low-light environments.

## Acceptance criteria

- [ ] Given the dashboard is visible, when the user toggles dark mode, then the background switches to a dark palette and text remains readable.
- [ ] Given dark mode is enabled, when the page refreshes, then the theme stays dark.
- [ ] Given dark mode is disabled, when the user opens settings, then the toggle shows the current theme.

## Plan

- [ ] Define the theme context and provider: `npm run typecheck` passes.
- [ ] Add theme variants for the dark palette: visual check of the dashboard in both themes.
- [ ] Add a settings toggle to switch the theme: component test passes.
- [ ] Persist the choice across sessions: unit test for storage round-trip passes.
- [ ] Run the full suite: `npm test` passes.

## Out of scope

- Export of theme preferences.
- Dark mode for print layouts.

## Suggestions

- Use the storage API already present in the codebase, if any.
