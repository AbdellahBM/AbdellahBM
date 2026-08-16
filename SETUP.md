# Install the clean GitHub profile

This version is intentionally restrained: one visual language, generous spacing, a single accent color, and only subtle motion.

## Files

```text
AbdellahBM/
├── README.md
└── assets/
    ├── hero.svg
    ├── focus.svg
    ├── project-leavecast.svg
    ├── project-scheduler.svg
    └── private-work.svg
```

## Update

Copy `README.md` and the complete `assets` folder into the public profile repository:

```text
AbdellahBM/AbdellahBM
```

Then run:

```bash
git add README.md assets
git commit -m "simplify profile with a clean product-style design"
git push origin main
```

## Remove the old visual clutter

The new README does not use the former neon assets, typing banner, contribution snake, statistics cards, or terminal-style panels. You can delete those unused files after the new version is live.

The old snake workflow is no longer needed. Delete `.github/workflows/snake.yml` only when you are sure no other README element depends on it.

## Suggested GitHub bio

```text
Software Engineer building reliable backend, cloud and data-driven systems with Java, Node.js and Python.
```
