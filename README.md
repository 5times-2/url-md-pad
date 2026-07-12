# Browser Quick Note
This is a temporary browser text pad for quick notes, scratch text, and Markdown drafts.

# Versions
- `index.html`: compact Markdown pad with edit/preview toggle.
- `full.html`: single-pane live Markdown pad with direct rendering while you type.
- `data-url-encoded.txt`: bookmarkable data URL for `index.html`.
- `data-url-full-encoded.txt`: bookmarkable data URL for `full.html`.

# Behavior
Text is not saved to local storage. The current text is encoded into the URL hash as `#t=...`, so closing the tab discards the page state unless you keep the URL in browser history or copy/bookmark it.

# Install
## Linux
```bash
xdg-open index.html
xdg-open full.html
```
## macOS
```bash
open index.html
open full.html
```

# Upload to URL
Or you can paste the content of `data-url-encoded.txt` or `data-url-full-encoded.txt` into your browser address bar.

# Save it as a bookmark
Open your browser and save the URL from one of the `data-url-*.txt` files as a bookmark.

# customize
If you are interesting in change the logo of the page, you can simply change `%3EMD%` to `%3EXX%` (XX indicates the name you want to set)from `data-url`.
```html
<link rel="icon"
          href="data:image/svg+xml,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%201
00%20100%22%3E%3Crect%20width=%22100%22%20height=%22100%22%20fill=%22black%22/%3E%3Ctext%20x=%2250%22
%20y=%2265%22%20font-size=%2260%22%20text-anchor=%22middle%22%20fill=%22lime%22%20font-family=%22mono
space%22%3EMD%3C/text%3E%3C/svg%3E">
```
