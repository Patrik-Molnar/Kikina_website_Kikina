# Kristy & Ondra — GitHub Pages

This folder contains the complete white-and-navy wedding website based on the
supplied PDF. It needs no build tools or external font services. Both attendance
buttons open the Google Form in a new tab. The final section also lets guests
expand and fill in the same Google Form directly on the page.

## Publish on GitHub Pages

1. Open your GitHub repository in the browser.
2. Upload everything **inside** this folder to the repository root, keeping the
   `photos` subfolder and all image filenames unchanged. Do not upload the ZIP.
3. Commit the changes to the `main` branch.
4. In **Settings → Pages**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

GitHub will show the public website URL after the first deployment finishes.

## Edit the website

- Text and page structure: `index.html`
- Colors, typography and layout: `styles.css`
- Photographs: `photos/`
- Typeface used in this version: `cormorant-regular.ttf` and `cormorant-semibold.ttf`
- Browser icon: `favicon.svg`

Keep the existing image filenames when replacing photographs, or update the
matching paths in `index.html`.

## Credits

The opening couple photograph, church illustration, Pálava field image and
closing photograph come from the supplied project assets and PDF reference.
The included Cormorant Garamond and legacy Italianno fonts are distributed
under the SIL Open Font License in `OFL.txt`.

The unused `photos/palava-hero.webp` from the earlier design is retained in the
package. It is by Tadeáš Bednarz, used under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), and is not
displayed in this version.
