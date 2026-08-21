# Git Café Exercise

# Round 3

1. Start a brand-new repository, record a first commit, then create a `dev` branch and a `qa` branch from it. Return to `dev` and remove `qa`.

2. Create `feat/events`, add an `events.html` page, record it, publish, and open a merge request.

3. Switch to `main` and make a new commit there (e.g. update `index.html`), so `main` is now ahead of where `feat/events` branched from. Go back to `feat/events` and replay your work so it sits **on top of** the latest `main` (keeping history linear rather than creating a merge commit). Then add a change to `events.html`, record it, and publish the updated branch.

4. On `feat/footer-links`, make **two** separate commits. Then, on a new branch `feat/footer-squash` created from main, combine everything from `feat/footer-links` into a **single** commit with the message squashed footer links. Publish and open a merge request.