# GEB Lab website

Genome Evolution and Bioinformatics Lab, Howard University.
Live at https://compbio-geb.github.io/GEBLab/

Plain HTML and CSS. There is no build step: edit a file, commit, push.

## Files

| File | Page |
| --- | --- |
| index.html | Home: intro, research themes, news |
| research.html | Research areas and funding |
| people.html | PI, students, alumni |
| publications.html | Papers, grouped by year |
| teaching.html | Courses |
| fun.html | Logos, drawings and other fun things |
| join.html | How to join, contact |
| style.css | Colors, fonts, layout for every page |
| images/ | Logo (logo.svg), header cartouche (logo-cartouche.svg), logo sketches, Geb and Nut drawing |
| favicon.svg | Browser-tab icon (same as images/logo.svg) |

## Common edits

- **News:** in index.html, copy one `<li>` in the News list, put it at the top, change the date and text.
- **New paper:** in publications.html, copy one `<li>` and edit it. For a new year, copy an `<h2 class="year">` block with its `<ul>`.
- **New lab member:** in people.html, copy one `<li>` in the right list.
- **Photos:** put the photo in `images/` and add `<img class="photo" src="images/name.jpg" alt="Name">` in people.html. The PI photo is `images/jinrui-xu.png`.
- **Fun page:** put any image in `images/`, then copy the `<article class="entry">` block in fun.html, paste it at the top, and change the title, date, text and image.
- **New page:** copy an existing page, change the content, and add a link to the menu (`<nav>`) on every page.

## Publishing (first time)

1. GitHub Desktop: File → Add Local Repository → choose this folder → "create a repository" if asked.
2. Publish repository: name **GEBLab**, owner **compbio-geb**, uncheck "Keep this code private".
3. On github.com: repo Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. After a minute the site is at https://compbio-geb.github.io/GEBLab/
