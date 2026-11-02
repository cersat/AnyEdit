# AnyEdit

Every pull request into `main` is merged automatically by `.github/workflows/automerge.yml`.

The only exception: PRs that change anything under `.github/`. They could break the automerge itself, so they are skipped and merged by hand.

