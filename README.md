# my-web-page

Here you can find the relevant information on my academic background and interests.

A single-page job-market site: name and contact first, then a short research statement, a featured job market paper, working papers, teaching, and a CV PDF hosted on the site.

## Customize

Edit `index.html`. Search for `TODO` and replace:

- Name, university, email
- The two-sentence research statement
- JMP title, abstract, and coauthors
- Working papers and work in progress
- Teaching, education, and letter writers
- Google Scholar and ORCID links
- `Last updated` in the footer

Then:

1. Put a square portrait at `assets/portrait.jpg`. In the portrait `<div>`, replace the initials `<span>` with `<img src="assets/portrait.jpg" alt="Your Name">`.
2. Drop PDFs into `files/`:
   - `files/CV.pdf`
   - `files/jmp.pdf`
   - optional slides and appendix
3. Change the initials in `favicon.svg`.
4. Set the `<title>`, meta description, and canonical URL.

Host papers in `files/`, not Google Drive or Dropbox. Some campus networks block those.

## Preview locally

Open `index.html` in a browser, or from this folder:

```bash
npx --yes serve .
```

## Put it on GitHub Pages

1. This repository is `ARAzampour/my-web-page`.
2. On GitHub: **Settings → Pages → Deploy from a branch → `main` / root**.
3. The site will be at `https://arazampour.github.io/my-web-page/`.
4. Optional: add a custom domain such as `yourname.com` in Pages settings, then put that domain in a `CNAME` file in this folder.

No build step. GitHub Pages can serve these files as they are.
