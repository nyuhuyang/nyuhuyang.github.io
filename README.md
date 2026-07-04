# nyuhuyang.github.io

Personal learning notes, published at <https://nyuhuyang.github.io/>.

- `index.html` — homepage (note list)
- `notes/` — knitted R Markdown HTML files (self-contained, one file per note)

## Publishing workflow

1. Knit the source `.Rmd` (kept in its own project repo) to a self-contained HTML:
   `rmarkdown::render("note.Rmd")`
2. Copy the HTML into `notes/`.
3. Add a list entry in `index.html`.
4. Commit + push — GitHub Pages redeploys automatically in ~1 minute.
