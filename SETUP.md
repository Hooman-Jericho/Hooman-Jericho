# Setup — Hooman-Jericho GitHub Profile

## Repository

This is the special public profile repository. Its name must exactly match the GitHub username: `Hooman-Jericho`.

## File layout

```text
Hooman-Jericho/
├── README.md
├── SETUP.md
├── assets/
│   ├── header.svg
│   ├── research-map.svg
│   └── footer.svg
└── .github/
    └── workflows/
        └── snake.yml
```

## Activate the contribution snake

1. Open **Settings → Actions → General** and make sure GitHub Actions are allowed.
2. The workflow declares `contents: write`. Check workflow permissions and repository rules if publishing to the `output` branch is blocked.
3. Open **Actions → Generate contribution snake → Run workflow**.
4. After the first successful run creates the `output` branch, the README can load the generated SVG.

## Notes

- The stats cards and activity graph use third-party services and may occasionally be rate-limited or unavailable.
- The contribution snake depends on GitHub Actions; it is generated, not stored as a static image in this package.
- Check all profile links and remove any tools you do not actually use.
- Add research results only when they are measured, documented, and reproducible.
