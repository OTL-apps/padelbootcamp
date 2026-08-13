# Ladies Padel Boot Camp — static website

Plain HTML/CSS. No build step, no dependencies, no server-side code.
Works on any static host. The mobile hamburger menu works here (it's pure CSS).

## Files

```
index.html                 the whole page
assets/icons/*.svg         all section icons
assets/logo-*.png          partner logos
uploads/LPBC LOGO.svg      nav logo
uploads/*.png              hero + gallery photos
uploads/SSP-Video1.mp4     SSP video (plays inline)
```

Keep the folder structure as-is — paths in `index.html` are relative.

## Hosting options (all free)

**Netlify Drop** — easiest. Go to app.netlify.com/drop and drag this whole
folder onto the page. Live in about 10 seconds, gets a free URL you can later
point a custom domain at.

**Cloudflare Pages** — dash.cloudflare.com → Workers & Pages → Create →
Pages → "Upload assets". Drag the folder. Free custom domains and SSL.

**Vercel** — vercel.com/new → drag the folder. Same deal.

**GitHub Pages** — create a repo, upload these files to the root of the
`main` branch, then Settings → Pages → Source: `main` / root.

## Editing

Everything is inline-styled in `index.html`. Common edits:

- **Waitlist link** — search for `forms.gle/m1YKYWrUtr9qc4rc6` (3 places).
- **Spots remaining** — search for `Only 12 Spots` and `Only <span...>12 spots`.
- **Dates** — search for `September 2026`.
- **Price** — search for `R1000`.
- **Palette** — sage `#8b9878`, deep sage `#7c8b68`, blush `#eec2b9`,
  gold `#a3813f`, cream `#f1eee4`, SSP navy `#163568`.
- **Fonts** — Playfair Display (headings) + Jost (body), loaded from Google Fonts
  in `<head>`.

## Custom domain

All four hosts above let you add a domain for free (you still pay your
registrar for the domain itself). Look for "Custom domains" in the project
settings and follow their DNS instructions.
