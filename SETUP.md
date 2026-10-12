# Publish your Burgundy & Blush profile

## Quickest option: GitHub web interface

1. Sign in to the GitHub account **techwings0710**.
2. Create a **public** repository named **techwings0710** (exact spelling, same as your username). If it already exists, open it instead.
3. Extract the ZIP locally. Open the extracted `malavika-editorial-github-profile` folder.
4. On the GitHub repository, choose **Add file → Upload files**. Drag **README.md** and the **assets** folder together onto the upload area. You can also upload `SETUP.md`, though it is optional.
5. Before committing, ensure the uploaded paths show `README.md`, `assets/hero.svg`, `assets/aegisquant.svg`, `assets/heritage-shield.svg`, and `assets/section-divider.svg`.
6. Commit changes. Visit https://github.com/techwings0710 to see your profile.

If GitHub's upload UI does not keep the folder, use Git in the terminal:

```bash
git clone https://github.com/techwings0710/techwings0710.git
cd techwings0710
# Copy README.md and the complete assets/ directory into this cloned directory.
git add README.md assets SETUP.md
git commit -m "Design Burgundy and Blush profile"
git push origin main
```

Do not move the SVG files out of `assets/`: the README uses relative paths like `./assets/hero.svg`.

## Personalize before publishing

- Confirm your exact college and degree names, internship details, and personal contributions.
- Add a Heritage Shield repository URL when it is public.
- If you have a portfolio site later, add its link beside the existing contact badges.
- To edit colors or text in a banner, open the corresponding `.svg` in VS Code; SVGs are plain text.
- All graphics are included locally. The contact badges use shields.io (an external service), so they need internet access.

## Palette
Deep Burgundy `#2C1421` · Muted Wine `#482638` · Dusty Mauve `#99617B` · Blush `#F5AFC0` · Soft Ivory `#FFF1F5`.

No GitHub Actions, secret tokens, installs or additional build steps required. GitHub automatically renders the profile README when the repository name matches your username.
