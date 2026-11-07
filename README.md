# NEXORA 2027 website

Sponsor-facing hackathon site built with Vite.

## Start the site

```sh
npm install
npm run dev
```

Vite prints the local address to open in a browser. Create a production build with `npm run build`; preview it with `npm run preview`.

## Project map

```text
index.html              Page content and Vite entry point
src/
  scripts/main.js       Navigation, forms, track filters, FAQs, motion
  styles/style.css      Layout, colors, responsive rules, and animations
public/
  partner-deck.html     Printable partner presentation
  assets/               Social card and favicon
package.json            Vite commands and dependency
package-lock.json       Locked dependency versions
dist/                   Generated production build, created by Vite
```

Interest forms open a prefilled email draft for the visitor to review; the site does not send or store form data. The partner deck can be downloaded as HTML or opened and printed to PDF. After deployment, replace the social-card path in the Open Graph metadata with the site's absolute public URL. `dist/` is excluded from version control.
