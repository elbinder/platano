# The Plantain Circle

A simple field guide for growing stronger plantains, with better soil and better water.

For the people of the Darién, Panama. A public good by [Plantain Goods](https://plantaingoods.org).

---

## What this is

A bilingual (English / Spanish) field guide that introduces the **plantain circle** — a permaculture growing pattern with a central organic-matter pit ringed by six plantain plants on a raised mound. Tested across many tropical climates, the design is being introduced as a test pattern in the Darién, Panama, with the Wounaan community.

The guide is a single HTML page with five illustrations. It works offline once loaded and prints cleanly to PDF.

## Repository contents

```
.
├── index.html          The full bilingual guide
├── favicon.svg         Site icon
├── images/             Five illustrations (PNG)
├── plantain-circle.pdf Offline download (printed version)
├── LICENSE             CC BY-NC-SA 4.0
└── README.md           This file
```

## License

Released under **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International** ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)).

You may copy, translate, print, teach, and adapt this guide for any non-commercial purpose, as long as you give attribution and share derivative works under the same license.

## Contributing

This guide is a working draft and benefits from real-world testing and translation.

**Ways to contribute:**

- **Field feedback.** If you build a plantain circle from this guide, tell us what worked and what didn't. Open an issue describing your site, your results, and what you'd change.
- **Translations.** The current version is English and Spanish. Woun Meu, French (for Haitian growers), Portuguese, and Kreyòl are all welcome. Fork the repo, add a translated version of `index.html`, and submit a pull request.
- **Illustrations.** All current illustrations are released under the same CC BY-NC-SA license. Replacement or supplementary illustrations in the same warm-sepia engraved style are welcome.
- **Local plant names.** The companion plant list uses Spanish names; community-specific names (Woun Meu and others) should be added.

**To contribute:**

1. Fork this repository.
2. Make your changes on a new branch.
3. Open a pull request describing what you changed and why.

## Deploying your own copy

### On Cloudflare Pages (recommended)

1. Fork this repository to your own GitHub account.
2. Sign in to [Cloudflare](https://dash.cloudflare.com/).
3. Go to **Workers & Pages → Create → Pages → Connect to Git**.
4. Select your forked repository.
5. Build settings: leave **Build command** empty, set **Build output directory** to `/`.
6. Deploy. Your site will be live at `your-project.pages.dev` in under a minute.
7. (Optional) Add a custom domain under **Custom domains**.

### On Netlify

1. Fork this repository.
2. Sign in to [Netlify](https://www.netlify.com/).
3. **Add new site → Import an existing project → Deploy with GitHub.**
4. Select your forked repository. No build command needed.
5. Deploy.

### On GitHub Pages

1. Fork this repository.
2. Repository **Settings → Pages → Source: Deploy from a branch → main → / (root).**
3. Save. Site goes live at `username.github.io/plantain-goods` within a minute or two.

## Local preview

This is a static HTML file with no build step. To preview locally:

```bash
# Any one of these works:
python3 -m http.server 8000
# or
npx serve .
# or just open index.html in a browser
```

Then visit `http://localhost:8000`.

## Acknowledgments

The plantain circle design is rooted in the work of **Bill Mollison** (the founder of permaculture) and **Geoff Lawton**, whose tropical permaculture teachings have refined the pattern for decades. This guide adapts that work for the Darién climate and the working knowledge of the Wounaan community.

## Contact

For questions, partnership, or to share field results from your own test plot, reach out through [plantaingoods.org](https://plantaingoods.org).
