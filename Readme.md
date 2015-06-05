# Markdown Editor

GitHub Flavored Markdown editor in a single static ~8.5KB HTML file. Both the editor and version history ship with the document. [Try it!](https://srpeck.github.io/markdowned/)
![](demo.gif)

## Workflow
1. Copy 'new.html' and rename to "XYZSpecification0.1.html"
2. Write in plaintext Markdown
3. Ctrl-s to save changes
4. Ctrl-p to print preview/print to PDF with Markdown applied
5. Rename to "XYZSpecification0.2.html", make edits against the new version
6. Rename the document to "XYZSpecification0.1.html" to view the older version, etc.

## Features
- MS Word not required; everyone can read .html files
- Uses the browser's built-in plaintext editor (textarea), built-in saving (ctrl-s), and built-in print formatting (ctrl-p)
- Best of both worlds:
  + Edit in plaintext
  + Markdown formatting applied on print
- Automatic versioning based on filename
- Version history stored with the document means no need to maintain multiple copies (v1, v2, etc.) or use a sledgehammer like git for a finishing nail size problem (single document, ~3 revisions, emailed around constantly)

Note:
The built-in save (ctrl-s) function in the IE browser saves only the original HTML, not any subsequent changes.