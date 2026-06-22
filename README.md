# Robert Richter — Personal Site

A simple, dark-themed landing page that links to my resume, LinkedIn, and GitHub.

🔗 **Live:** https://richterrw.github.io/robbie-portfolio/ _(after first deploy)_

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The landing page markup. |
| `styles.css` | Dark, modern styling. |
| `resume.pdf` | My resume — **replace the placeholder** with your real PDF. |
| `.github/workflows/deploy.yml` | Auto-deploys to GitHub Pages on push to `main`. |

## Add your resume

Drop your resume into the repo root named `resume.pdf` (overwriting the
placeholder), then commit and push. The **Resume** button links to it.

## Deploy (GitHub Pages)

1. Push this repo to GitHub on the `main` branch.
2. Go to **Settings → Pages** and set **Source** to **GitHub Actions**.
3. The included workflow publishes the site automatically on every push to `main`.

## Edit your details

Open `index.html` and update the links if anything changes:

- **LinkedIn:** `https://www.linkedin.com/in/robert---richter`
- **GitHub:** `https://github.com/richterrw`
- **Email:** `robbierichter15@gmail.com`

## Local preview

Just open `index.html` in a browser, or run a tiny server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
