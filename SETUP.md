# Midnight Blue & Gold — refined GitHub Profile

## What's fixed
- Removed any mention of the color palette from the banner.
- Email badge now reads **CONTACT ME / EMAIL**.
- Section titles are centered in their panels.
- Upgraded fonts to an editorial serif for major headings and Lato for supporting text.
- All profile graphics displayed by the README are **PNG** rather than SVG, avoiding GitHub XML parsing failures.

## Upload to GitHub
1. Open your local `techwings0710` profile repository in VS Code.
2. Remove the existing `assets` directory in that **profile repo only**, and copy in the new `assets` directory from this ZIP.
3. Replace `README.md` with this file.
4. Run:

```bash
git add -A
git commit -m "Polish midnight-gold GitHub profile"
git push origin main
```

5. Refresh https://github.com/techwings0710 using Command + Shift + R.

The `assets/` folder must be in the repository root, alongside `README.md`.

## Note
Custom background CSS and JavaScript are not supported in GitHub READMEs, so the visual lighting is embedded in the graphics.
