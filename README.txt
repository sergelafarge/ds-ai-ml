PERSONAL PORTFOLIO
Serge-Eric Keller | Keller Insight

A static, single-page portfolio built with plain HTML, CSS and JavaScript.
No build step, no framework, no dependencies to install.

FILES
  index.html      Home page: hero, work, case studies, background, tools, contact.
                  Self-contained (its own CSS and JavaScript).
  elements.html   Style guide showing every building block. Copy from here.
  generic.html    Template for any extra content page (e.g. a case study).
  style.css       Shared styles used by elements.html and generic.html.
  images/         Project thumbnails (AI.png, DL.png, and so on).
  images/logos/   Company logos: akira.png, cognizant.png, smbc.png, bmo.png,
                  michael-kors.png.
  LICENSE.txt     MIT license for the code (see the scope note inside).
  README.txt      This file.

EDIT THE CONTENT (all in index.html, in the <script> at the bottom)
  P  Projects: [title, category, description, notebook link, thumbnail path]
  T  Background timeline entries
  E  Companies in the "Worked with" carousel
  S  Tools in the "Tools I use" carousel
  IM Company name -> logo PNG in images/logos/
  L  Tool name -> inline SVG logo path
  M  Initials shown for tools that have no logo yet
Case studies, education and contact buttons are plain HTML further up.

ADD A PAGE
  1. Copy generic.html and rename it (for example my-case-study.html).
  2. Edit the title, headings and text.
  3. Link to it from index.html, for example <a href="my-case-study.html">.

RUN LOCALLY
  Open index.html in a browser, or from this folder run:
    python3 -m http.server 8000
  then visit http://localhost:8000

DEPLOY WITH GITHUB PAGES
  Push all files to a public repo, then in Settings > Pages choose
  "Deploy from a branch", branch main, folder /(root).
  A repo named <username>.github.io is served at https://<username>.github.io

CREDITS
  Fonts: IBM Plex Sans and IBM Plex Serif (SIL Open Font License), loaded
  from Google Fonts.
  Tool logos: Simple Icons (CC0). Logos remain trademarks of their owners.
