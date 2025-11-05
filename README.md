# Samiyart — Personal Portfolio

This is a small static portfolio website for Samitha Bandara (video editor).

Contents
- HTML files: `index1.html`, `about.html`, `projects.html`, `contact.html`
- Styles: `style.css`
- Images: `/images/` (profile pictures, project thumbnails, background)
- Videos: `/videos/` (showreel / project video files)

How to preview locally
1. Open the project folder in your browser (double-click `index1.html`) or serve it from a simple HTTP server.

On macOS or Linux, from the `webiste` folder run:

```bash
# Python 3
python3 -m http.server 8000
# then open http://localhost:8000/index1.html
```

What I checked (automated)
- Ran a local HTML check using `xmllint --html` on the main HTML files. Output notes are below.

Known issues found by `xmllint`
- Unescaped ampersands (&) in some external URLs appear as parser errors. Replace `&` in URLs with `&amp;` in the HTML (for example in social links) to satisfy strict parsers.
- `xmllint` produced a number of "Tag ... invalid" messages for HTML5 elements (e.g., `header`, `nav`, `section`, `article`, `time`, `video`, `source`). These tags are valid HTML5; different validators have differing strictness. I recommend validating with the W3C HTML validator (https://validator.w3.org/) for authoritative results.

Recommendations before upload to GitHub
- Fix any ampersand (`&`) characters in URLs by replacing them with `&amp;`.
- Optionally run the W3C validator with the live site or by uploading the files.
- Run a quick accessibility check (color contrast, alt text present — all images have alt attributes already).
- Add a license file if you plan to release the code publicly.

If you want, I can:
- Patch the HTML to escape ampersands for you.
- Run a full W3C validation (I can prepare the files or show you how to upload them to the validator).
- Add a `LICENSE` file (MIT or similar).

----
Generated on 2025-11-05 — small helper README to help you upload the project to GitHub.
