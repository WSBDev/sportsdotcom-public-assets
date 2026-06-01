sportsdotcom-public-assets

This repo holds the public legal documents served to the sports.com PREDICT frontend. The frontend fetches these files at runtime via raw.githubusercontent.com — no frontend deploy required to update copy.

Files
-----

terms.md
  Raw URL: https://raw.githubusercontent.com/WSBDev/sportsdotcom-public-assets/main/terms.md

privacy.md
  Raw URL: https://raw.githubusercontent.com/WSBDev/sportsdotcom-public-assets/main/privacy.md

Updating copy
-------------

Edit either file on the main branch (directly or via PR) and the change goes live to the site within a few minutes. No frontend deploy needed.

File format convention
----------------------

- First line of each file must be a plain text line: "Last updated: <Month D, YYYY>" (no markdown heading, no blank line before it)
- Document title (e.g. "PRIVACY POLICY", "TERMS & CONDITIONS") is NOT included — the app renders that as chrome
- Section headings use "## " (h2)
- Body text is normal paragraphs separated by blank lines
- Bullet lists use "- " with bold lead-in terms where applicable, e.g. - **"Account"** means...
- Links use standard markdown: [support@sports.com](mailto:support@sports.com)
- No emojis
