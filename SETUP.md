# Burgundy & Blush GitHub profile — V2

This version moves your README closer to the visual language you liked:
- the **hero banner** now matches the first reference much more closely
- the rest of the README uses **glowing section panels** inspired by Jeh's profile
- all effects are implemented using **SVG assets**, because GitHub READMEs do not allow custom CSS or JavaScript

## How to publish

1. Sign in to your GitHub account **techwings0710**.
2. Open the repository named **techwings0710**. If it does not exist, create a **public** repo with that exact name.
3. Upload **README.md** and the complete **assets/** folder.
4. Commit the files.
5. Refresh `https://github.com/techwings0710` to see the updated profile.

## Required file structure

```text
techwings0710/
├─ README.md
├─ SETUP.md
└─ assets/
   ├─ hero.svg
   ├─ section-about.svg
   ├─ section-projects.svg
   ├─ section-journey.svg
   ├─ section-tools.svg
   ├─ section-contact.svg
   ├─ about-code.svg
   ├─ aegisquant.svg
   ├─ heritage-shield.svg
   └─ footer.svg
```

## Important limitation

GitHub profile READMEs do **not** support:
- custom CSS files
- JavaScript
- animated page backgrounds
- hover effects beyond basic markdown rendering

So the glowing look is simulated using static SVG graphics embedded in the README.

## Easy edit points

- To change banner text, edit `assets/hero.svg`
- To change section labels, edit the corresponding `section-*.svg`
- To change project summaries, edit `README.md`
- To add a Heritage Shield repo later, replace the placeholder text in `README.md`

## Palette

- Deep Burgundy `#2C1421`
- Wine `#482638`
- Dusty Mauve `#99617B`
- Blush `#F5AFC0`
- Soft Ivory `#FFF1F5`
