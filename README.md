# Signal & Circuit

A responsive, multi-page editorial technology blog. This is a static HTML/CSS/JavaScript site with no build step or runtime dependencies.

## Deploy to Vercel

Import this folder as a Vercel project and choose **Other** as the framework preset. Leave the build command and output directory blank (or use `.` as the output directory). Vercel will serve `index.html` as the landing page. The included `vercel.json` applies clean URLs and basic response headers.

## Pages

- `index.html` — landing page
- `articles.html` — searchable and filterable story library
- `topics.html`, `about.html`, `contact.html`, `privacy.html`
- `article-*.html` — individual story pages using the shared article template in `site.js`

The newsletter and contact forms validate and show a local confirmation. Connect a mailing list or form endpoint before using them to collect submissions.
