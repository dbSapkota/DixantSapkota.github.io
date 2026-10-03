# Dixant Bikal Sapkota — academic website

A simple, responsive static website. All pages use one stylesheet. There are
no build tools, dependencies, external fonts, or JavaScript. Open `index.html`
in a browser to preview it locally.

## Files to upload

Upload these files together to the directory that already publishes your
GitHub Pages website (usually your repository root, or your configured `docs/`
folder). Upload the **contents** of this folder, not the folder itself.

| File | Purpose |
| --- | --- |
| `index.html` | Home and short research introduction |
| `cv.html` | Education, research experience, and skills |
| `research.html` | Research interests and guiding questions |
| `publications.html` | Conference publications |
| `other.html` | Projects, presentations, and other activities |
| `projects.html` | Project details; preserves your existing projects URL |
| `styles.css` | Shared design and mobile/print styles |

Replace the existing `index.html`, `projects.html`, and `publications.html`
with these new versions. Add the remaining HTML files and `styles.css` beside
them. You do not need to upload this README for the website to work.

Keep your existing `CNAME` file if your repository uses a custom domain.
Keep unrelated repository files and any existing license files. These pages
use fresh HTML and CSS and do not load the previous template's assets.
The old `assets/` and `images/` folders can remain in the repository.

## Personalize before publishing

The site includes a draft based on your known research interests and
background. It does not assume a current university, degree program, or email
address. Search the HTML files for `EDIT` to find customization points.

1. **Current affiliation:** Add your degree, department, and university in the
   home page sidebar; update `cv.html` with your current academic position.
2. **Contact:** Uncomment the contact section near the end of `index.html`
   and replace `YOUR_EMAIL`, `YOUR_SCHOLAR_URL`, and `YOUR_GITHUB_URL` with
   real values. Remove any links you do not want to include.
3. **CV:** Add education and experience dates in `cv.html`. To offer your
   full CV, create a `files/` folder, upload your PDF as `files/cv.pdf`, and
   uncomment the download link in the CV sidebar. The PDF is not included.
4. **Publication details:** The PowerCon entry currently summarizes the topic
   and known venue; it is not a complete citation. Replace it with the exact
   paper title, full author list, venue information, and DOI. Commented
   examples show how to add a PDF or DOI link and additional papers.
5. **Presentations and other activities:** Add the poster title and date in
   `other.html`, and optionally add teaching, service, hobbies, or other work.
6. **Photo (optional):** Upload a portrait as `images/profile.jpg`, then replace
   the initials circle in `index.html` with the commented image element.
   The initials circle works without any image files.

The navigation and footer are repeated in each HTML file so every page works
without scripts. If you change their wording or add a new page, update them
in all six HTML files. To change the color scheme, edit the variables at the
top of `styles.css`.

All internal links are relative, so the site also works when hosted under
a repository subdirectory. File and folder names are case-sensitive on the
published website. Optional PDF/photo links are commented out until their
files exist. The CV page also has print styling: use your browser's Print
command to print the page or save it as a PDF.

## Quick check

Open `index.html`, visit every navigation link, and resize the browser to a
phone width. After uploading, check the published site and your new links.
If an old version appears, refresh the browser after your repository's
existing deployment finishes.
