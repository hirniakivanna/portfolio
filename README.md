# Ivanna Hirniak — Personal Portfolio

A static, responsive website designed for GitHub Pages, with a one-page homepage and three separate project pages.

## Included

- `index.html` — scrolling homepage, animated hero, horizontal mouse-following project gallery, interactive map, experience timeline, contact
- `market-entry.html` — market-entry academic case with original PDF
- `hotel-investment.html` — team academic case with original PDF
- `apple-analysis.html` — independent Apple financial analysis with original Excel workbook
- `assets/` — CSS, JavaScript, headshot, world map, case-study visual previews
- `documents/` — résumé PDF, the two case-study PDFs, and Apple workbook

## Publish using GitHub Pages

1. Extract the ZIP on your computer.
2. Open your GitHub repository `portfolio`, or create one.
3. Use **Add file → Upload files**. Drag the **contents** of the extracted folder into the upload box (the root `index.html`, the three other HTML files, and both `assets` and `documents` folders). Do not upload only the ZIP.
4. Click **Commit changes**.
5. Open your repository's **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)**. Click **Save**.
7. Open `https://YOUR-USERNAME.github.io/portfolio/` (replace YOUR-USERNAME with your actual GitHub username). GitHub may take a few minutes to publish.

## Preview locally

Open `index.html` in a desktop browser. For the most consistent local test, use a basic local web server: `python -m http.server 8000` from the extracted folder, then visit `http://localhost:8000/`.

## Notes

- Your three project cards link to real separate HTML pages.
- All relative links work with a GitHub Pages project repository path (not hardcoded to a domain).
- The map uses a geographic world image and representative city/country marker positions. It does **not** reveal former addresses.
- The Apple workbook is the original spreadsheet, not a rendered interactive workbook. Visitors can download or open it in a spreadsheet app.
- PDF embedding is supported by most browsers, with a separate Open PDF link as a fallback.
- External Google Fonts require internet; system fonts are used if offline.
- Your email address, LinkedIn, and résumé are linked.
- This website is not affiliated with Apple Inc. The Apple analysis is an independent academic/personal project.
