# Plan

## Story

As a user, I want to switch between light and dark themes, so that I can use the dashboard comfortably in low-light environments.

## Acceptance criteria

- [ ] Given the dashboard is visible, when the user toggles dark mode, then the background switches to a dark palette and text remains readable.
- [ ] Given the user toggles dark mode, then the switch happens without a full page flash or reload.
- [ ] Given dark mode is enabled, when the page refreshes, then the theme stays dark.

## Plan

- [ ] Define the theme context and provider: `npm run typecheck` passes.
- [ ] Add theme variants for the dark palette: visual check of the dashboard in both themes.
- [ ] Add a settings toggle to switch the theme: component test passes.
- [ ] Run the full suite: `npm test` passes.

## Out of scope

- Export of theme preferences.
- Dark mode for print layouts.
