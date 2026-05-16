# Personal Website

A minimal personal website built with plain HTML & CSS.
No build tools, no dependencies, no JavaScript frameworks — just files.

## Pages

| File | URL | In nav? |
|------|-----|---------|
| `index.html` | `/` | ✅ (about) |
| `curriculum.html` | `/curriculum` | ✅ |
| `books.html` | `/books` | ❌ — link from about |
| `films.html` | `/films` | ❌ — link from about |
| `notes.html` | `/notes` | ❌ — link from about |

## Deploying to GitHub Pages

1. **Create a new GitHub repository** named `username.github.io`
   (replace `username` with your actual GitHub username).

2. **Upload all files** to the root of that repository:
   - `index.html`
   - `curriculum.html`
   - `books.html`
   - `films.html`
   - `notes.html`
   - `style.css`
   - `cv.pdf` *(your CV file — optional)*

3. **Enable GitHub Pages** in the repo settings:
   - Go to **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / `(root)`
   - Save

4. Your site will be live at `https://username.github.io` within a minute or two.

## Customising

- **`style.css`** — all colours and fonts live here as CSS variables at the top.
  Change `--accent`, `--bg`, `--ink` etc. to retheme the whole site at once.
- Replace every `Your Name` / `your@email.com` placeholder with real content.
- The `cv.pdf` link in `curriculum.html` assumes you place your PDF there;
  update or remove it if not needed.
- Add a `favicon.ico` or `<link rel="icon">` tag if you want a browser icon.

## Adding more hidden pages

Copy any of the log pages (`books.html`, `films.html`) as a template.
Keep the nav links pointing only to `index.html` and `curriculum.html`
so the page stays off the menu. Link to it from wherever you want.
