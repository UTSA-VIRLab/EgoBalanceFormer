# EgoBalanceFormer — Project Website

Static project page for **EgoBalanceFormer: Predicting Human Balance from Egocentric Pose and VR-Native Motion**, accepted as a TVCG journal paper for IEEE ISMAR 2026.

## Files

- `index.html` — all page content, authors, tables, and citation.
- `styles.css` — responsive layout and ISMAR-inspired theme.
- `app.js` — Copy BibTeX interaction.
- `assets/` — original paper PDF, extracted figures, ISMAR logo, and BibTeX file.
- `.nojekyll` — makes the package suitable for direct static GitHub Pages publishing.

No npm installation, build process, server, or API keys are required. The page uses relative asset paths, so it works at a project repository URL or in a subfolder. Google Fonts is optional; system fonts are used when it is unavailable.

## Publish as a separate GitHub repository

1. Create a repository named `EgoBalanceFormer` under the intended GitHub account or organization.
2. Extract this ZIP. Upload the **contents** of the extracted folder into the repository root. `index.html`, `styles.css`, `app.js`, and `assets/` must be at the same level. Do not upload just the ZIP.
3. Commit the files to `main`.
4. Go to **Settings > Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then save.
7. GitHub Pages will show the published URL after deployment completes.

If the repository is created under `utsa-virlab` with that exact name, the expected URL is `https://utsa-virlab.github.io/EgoBalanceFormer/`.

## Add to an existing GitHub Pages website

Copy this folder into the existing site's published source directory and name the folder `EgoBalanceFormer`. Preserve the existing site's publishing configuration and root files. For the lab's existing Pages site, the expected path would be `/EgoBalanceFormer/`.

## Preview locally

Open `index.html` in a browser. For a local HTTP preview, run this command inside the extracted folder:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`. Clipboard access can vary by browser; the copy button falls back to selecting the citation for manual copying.

## Edit the page

- Update content, author links, or results in `index.html`.
- Adjust colors and spacing in `styles.css` (the final overrides define the ISMAR theme).
- Replace the paper at `assets/EgoBalanceFormer.pdf` when the final version is available.
- Update the citation in both `index.html` and `assets/egobalanceformer.bib` when the DOI, volume, and pages are confirmed.
- Add code and presentation links to the `btn-row` in `index.html` when available.

The package contains the project webpage source, not the research model's implementation. Code and presentation URLs were not provided, so no speculative links have been added.

## Sources and credits

- Scientific text, figures, and numerical results: supplied EgoBalanceFormer manuscript.
- ISMAR 2026 logo and color reference: https://www.ieeeismar.net/2026/.
- GitHub Pages setup: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site.

No new license is asserted for the supplied paper or third-party branding.
