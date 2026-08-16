# Install the clean GitHub profile

This version is intentionally restrained: one visual language, generous spacing, a single accent color, and only subtle motion.

## Files

```text
AbdellahBM/
├── README.md
├── .github/
│   └── workflows/
│       └── snake.yml
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
git add README.md assets .github/workflows/snake.yml
git commit -m "add subtle animated contribution grid"
git push origin main
```

## Contribution animation

The profile keeps one restrained animation: the GitHub contribution snake. The included workflow generates light and dark SVG versions and publishes them to the `output` branch.

After the first push, open **Actions → Generate contribution snake → Run workflow** once. After that, GitHub Actions refreshes the animation automatically every day.

If the workflow cannot publish the `output` branch, check **Settings → Actions → General → Workflow permissions** and allow read/write permissions for `GITHUB_TOKEN`.

## Suggested GitHub bio

```text
Software Engineer building reliable backend, cloud and data-driven systems with Java, Node.js and Python.
```
