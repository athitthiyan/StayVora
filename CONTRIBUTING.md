# Contributing to Stayvora

Thanks for helping improve Stayvora. This project welcomes bug reports, feature ideas, documentation fixes, tests, and small UI polish PRs.

## Ways to Contribute

- Pick an issue labeled `good first issue` or `help wanted`.
- Report a bug with the expected behavior, actual behavior, screenshots if useful, and reproduction steps.
- Suggest a feature by describing the guest, partner, or operations problem it solves.
- Improve tests, accessibility, documentation, or production-readiness checks.

## Local Setup

```bash
npm install
npm start
```

The app runs at [http://localhost:4200](http://localhost:4200).

## Before Opening a Pull Request

```bash
npm run lint
npm test
npm run build:prod
```

For user-facing flows, also run:

```bash
npm run e2e
```

## Pull Request Guidelines

- Keep PRs focused on one behavior or improvement.
- Include screenshots for UI changes.
- Add or update tests when behavior changes.
- Describe the user impact and any deployment or environment notes.

## Good First Issue Ideas

- Improve empty states for search results and booking history.
- Add accessibility checks to critical checkout controls.
- Expand Playwright coverage for mobile search and room detail flows.
- Add Storybook stories for shared components.
- Document common local setup errors and fixes.
