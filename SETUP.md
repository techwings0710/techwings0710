# Midnight Blue & Gold GitHub profile

This version rebuilds your GitHub profile in a more aesthetic, premium direction.

## What changed
- New **midnight blue + gold** palette
- More polished **editorial hero banner**
- Proper section headers for every part of the README
- Experience and tools converted into **custom visual panels** instead of plain markdown tables
- More image-driven layout so GitHub renders it more consistently

## Important upload note
If some old graphics are still showing or some headers appear broken, it usually means the old `assets/` folder was not fully replaced.

The safest method is:
1. Delete the old `assets` folder from the `techwings0710` repo.
2. Upload the **new `assets` folder** from this package.
3. Upload the **new `README.md`**.
4. Refresh the profile.

## Required structure
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
   ├─ experience-panel.svg
   ├─ tools-panel.svg
   └─ footer.svg
```

## GitHub limitation
GitHub profile READMEs do not support real CSS or JavaScript, so the lighting and panel effects are simulated using SVG artwork.

## Palette
- Midnight Navy `#07111F`
- Deep Blue `#0F1E3D`
- Gold `#E7C56D`
- Antique Gold `#CDA349`
- Soft Ivory Gold `#F4DE9A`
