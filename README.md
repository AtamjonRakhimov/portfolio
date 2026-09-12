# Atamjon Rakhimov — Portfolio Site

Plain HTML/CSS/JS — no build tools, no frameworks. Open `index.html` in a
browser to preview it, or deploy it as static files anywhere.

## Before you publish, edit these

1. **Photo** — `.hero__photo` in `styles.css` is currently a placeholder
   gradient box. Add `<img src="your-photo.jpg" alt="Atamjon Rakhimov">`
   inside `.hero__media` in `index.html` and drop your photo file next to
   `index.html`.
2. **CV** — put your résumé PDF at `cv/Atamjon_Rakhimov_CV.pdf` (create the
   `cv` folder), or update the two `download` links in `index.html` to point
   wherever you host it.
3. **Email** — `atamjon.rakhimov.dev@gmail.com` appears in a few places
   (search the file for it) — double check it's exactly right.
4. **Powerbank Rental System project** — the repo link is a `#` placeholder;
   swap it for the real GitHub URL once that repo is public.
5. **Second featured project** — I used the Powerbank Rental System since I
   wasn't fully certain of the project name/URL in your reference design.
   If you'd rather feature a different project, tell me its name, link, and
   a one-line description and I'll swap it in.
6. **LinkedIn** — the LinkedIn icon in the footer links to `#`. Add your
   profile URL.

## Deploying for free (recruiters just need a link)

**GitHub Pages** (recommended, matches your GitHub-heavy profile):
1. Create a repo, e.g. `AtamjonRakhimov/portfolio`.
2. Push these three files (`index.html`, `styles.css`, `script.js`) plus
   your photo and CV.
3. In the repo, go to Settings → Pages → set source to the `main` branch.
4. Your site will be live at `https://AtamjonRakhimov.github.io/portfolio`.

**Netlify / Vercel** also work — drag-and-drop the folder on
netlify.com/drop for the fastest option, no account setup required for a
quick preview link.

## Structure

- `index.html` — content and structure
- `styles.css` — all styling (dark theme, lime-green accent, responsive)
- `script.js` — mobile menu toggle only
