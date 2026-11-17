# GAPSTRIKE support website

A small static support and privacy site for the GAPSTRIKE iOS game. It uses local HTML, CSS, and SVG only. There are no frameworks, fonts, analytics, cookies, tracking scripts, or external runtime assets.

## Files

- index.html — support page and gameplay FAQ
- privacy.html — privacy policy, effective November 17, 2026
- styles.css — responsive visual system and reduced-motion behavior
- favicon.svg — local GAPSTRIKE mark

The support address currently uses the reserved example address support@example.com as a visible placeholder. Replace it in index.html and privacy.html before publishing.

## GitHub Pages deployment

1. Push these files to the root of the againstthespread/gapstrike-support repository on its main branch.
2. In GitHub, open the repository’s Settings, then Pages.
3. Under Build and deployment, select Deploy from a branch.
4. Choose main and the /(root) folder, then save.
5. Wait for the Pages deployment workflow to finish.

Expected URLs:

- Support: https://againstthespread.github.io/gapstrike-support/
- Privacy: https://againstthespread.github.io/gapstrike-support/privacy.html

GitHub Pages sites are public on the internet, including sites from private repositories when the account plan permits Pages for private repos. Confirm the repository plan and visibility expectations before enabling deployment. See GitHub’s documentation for configuring a publishing source: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site.
