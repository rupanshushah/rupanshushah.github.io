Rupanshu Shah — academic website
================================

Files
  index.html     Home: intro, research interests, write-ups (short), education, honours, outside research
  research.html  Research: overview, current directions, write-ups, talks, experience, toolkit
  teaching.html  Teaching assistantships
  personal.html  Personal: photo gallery + reading, cinema, music, sport, leisure
  style.css      Shared styles (light + dark mode, mobile layout)
  files/         PDFs linked from the site (write-ups and symposium slides)
  photos/        Photos for the Personal page
  photo.jpg      Home-page portrait

Adding a photo to the Personal page
  1. Put the image in photos/ (portrait, 3:4 looks best; resize to ~1400 px on the long side).
  2. In personal.html, copy one <li>...</li> block in the gallery and change the file name in both places.
  3. Optionally write a caption inside <figcaption></figcaption>.

Adding an item to a Personal list
  Each list is a set of <li>...</li> lines; copy one and edit the text. The " · " separators appear automatically.

Updating
  PDFs           To update a write-up, replace the PDF in files/ and keep the same file name.
  Footer date    "Last updated October 2026" at the bottom of each page.

Publishing on GitHub Pages (free; the address stays live after you leave IIT Delhi)
  1. Create a GitHub account. Your username becomes the address: https://<username>.github.io
  2. Create a new PUBLIC repository named exactly <username>.github.io
  3. In the repository, choose "Add file" > "Upload files" and drag in everything from this
     folder (index.html must be at the top level; keep the files/ folder as it is). Commit.
  4. Settings > Pages: under "Build and deployment", Source = "Deploy from a branch",
     Branch = main, folder = / (root). Save.
  5. After a minute or two the site is live at https://<username>.github.io
  To edit later: change a file in the repository (or upload a new version); the site updates itself.
