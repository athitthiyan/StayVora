# Good First Issue Backlog

These are ready-to-create GitHub issues for the public contributor backlog. Apply the `good first issue` label to each one.

## Improve Empty Search Result States

Search currently has the core flow covered, but the empty and no-match states can be more helpful.

Acceptance criteria:
- Add clearer empty-state copy for no matching rooms.
- Keep the UI responsive on mobile.
- Include a component test or screenshot.

## Add Mobile Playwright Coverage for Room Details

Room detail pages are an important conversion step and should have a mobile smoke test.

Acceptance criteria:
- Add a Playwright test that opens a room detail route in a mobile viewport.
- Assert that title, price, gallery, and primary booking CTA are visible.
- Keep the test independent from payment checkout.

## Document Common Local Setup Errors

New contributors need a small troubleshooting section for install, test, and browser setup problems.

Acceptance criteria:
- Add a troubleshooting section to `CONTRIBUTING.md`.
- Cover Node version, `npm ci`/`npm install`, and Playwright browser install issues.
- Keep the language short and practical.

## Improve Checkout Accessibility Labels

Checkout controls should be easy to audit with screen readers and automated checks.

Acceptance criteria:
- Review form controls and action buttons in the checkout component.
- Add missing labels or accessible names.
- Update tests where relevant.

## Add Shared Component Storybook Plan

The roadmap calls out Storybook, but the first slice needs a concrete setup plan.

Acceptance criteria:
- Propose the first 3-5 components to document.
- Note required Storybook dependencies and scripts.
- Identify any styling or asset setup needed.
