# Giacomo Borghi — personal academic website

A static academic website for https://giacomoborghi.github.io.

## Pages

- `index.html`: biography, portrait, affiliation, and academic profiles
- `research.html`: broad research overview and current interests
- `publications.html`: preprints, articles, chapters, reports, and doctoral thesis
- `talks.html`: complete list of talks and conference contributions, with planned talks identified
- `service.html`: organization and refereeing
- `cv.html`: academic appointments and education

No build system, external fonts, analytics, or JavaScript is required. Edit the corresponding HTML file to update text and links. `styles.css` controls the layout; `portrait.png` is the supplied portrait.

## GitHub Pages

Use the repository `giacomoborghi/giacomoborghi.github.io`. In **Settings → Pages**, select **Deploy from a branch**, then **main** and **/(root)**, and save. These files belong directly in the root of that repository. GitHub Pages publishes subsequent commits automatically.

## Local preview

Run `python3 -m http.server 8765` in this directory and open http://localhost:8765.

Content is based on the CV and publication list supplied in September 2026. The source application documents are not included. Teaching, private home address, date of birth, and application-specific material are omitted from the public site. The CV page is a concise public academic CV rather than a copy of the application PDF.
