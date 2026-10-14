# Minxin Zhang — personal website

A ready-to-publish, static version of the current English website. It includes the ocean sunrise, portrait, publications, teaching and service sections, and Chinese name beneath the English name. It needs no installation, build, or server.

## Publish on GitHub Pages

1. Use the GitHub account `minxin-zhg` and create a public repository named `minxin-zhg.github.io`. If that repository already exists, review its contents before replacing files.
2. Upload the contents of this folder to the root of the repository on its `main` branch. The `index.html` file must be at the root, not inside another folder. Include the `assets` and `zh` folders, `styles.css`, and `.nojekyll`.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. GitHub will provide the live address, expected to be https://minxin-zhg.github.io/. Publication can take a few minutes.

For another account, use `USERNAME.github.io` as the repository name and change the canonical URL in `index.html` and `zh/index.html` to that address.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Editing

- Edit text and publication entries in `index.html`.
- Edit typography, layout, spacing, and colors in `styles.css`.
- Images and the self-hosted Chinese-name font are in `assets/`.
- `zh/index.html` redirects visitors to English; there is no Chinese-language version.
- The IPP preprint retains the updated year **2025**.

## Font credit

The Chinese name uses a three-character subset of Noto Serif SC Regular under the SIL Open Font License 1.1. Its license is included at `assets/fonts/OFL-NotoSerifSC.txt`.

Exported from the current site source commit `9b6cebd87bc0727f047ffa26bb632cdf4828706f`.
