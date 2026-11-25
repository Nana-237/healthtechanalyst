# Stephen Obeng – Portfolio

A static website (HTML, CSS and a little JavaScript). No build step.

## Files
- `index.html` – all page content
- `assets/css/style.css` – design (colours are at the top, in `:root`)
- `assets/js/script.js` – mobile menu and panel reveal
- `assets/images/stephen-obeng.jpg` – profile photo
- `assets/documents/Stephen-Obeng-CV.pdf` – public CV (home address and NMC PIN removed)
- `assets/documents/Kestrel-Health-Capstone.pdf` and `assets/images/kestrel-fig*.jpg` – capstone case study

## Publish on GitHub Pages
1. Create a new public repository on github.com (for example `portfolio`).
2. Click **Add file → Upload files**, drag in the *contents* of this folder (so `index.html` is at the top level), then **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute or two your site appears at `https://YOUR-USERNAME.github.io/portfolio/`.

## Things to confirm or add
- Dates: the timeline is continuous (Diploma 2009–2013, Nkenkaasu 2013–2020, Obuasi 2020–2022, Acacia Lodge 2022–present). Edit them in `index.html` if any are wrong.
- When you have a real project or case study, copy a panel in the "How I work" section (see the comment in `index.html`) and label it clearly as academic, personal, volunteer or work.
- Social sharing image: add an `og:image` meta tag with the full URL of an image once the site is live.
