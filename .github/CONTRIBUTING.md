# Contributing

- Work on a branch and open a pull request; nothing goes straight to `main`.
- One change per commit, with a message that says what changed and why. Reference the issue (`Fixes #N`).
- Lint, tests and the build must pass. Changes to checkout, payments, refunds or stock need a test that fails without the change.
- Never commit secrets (`.env` files, API keys). Use the hosting platform's secret store.
