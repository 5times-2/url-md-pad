# Browser Quick Note
This is a quick note page that you can just simply writing notes in your browser.

# Install
## Linux
```bash
xdg-open index.html
```
## macOS
```bash
open index.html
```

# Upload to URL
Or you can just simply upload the content of the file `data-url-encoded.txt` to your browser URL input place, and open it.

# Save it as a bookmark
Simply open your browser and save the url from `data-url-encoded.txt` as your bookmark, and you can use it in the future.

# customize
If you are interesting in change the logo of the page, you can simply change `%3EMD%` to `%3EXX%` (XX indicates the name you want to set)from `data-url`.
```html
<link rel="icon"
          href="data:image/svg+xml,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%201
00%20100%22%3E%3Crect%20width=%22100%22%20height=%22100%22%20fill=%22black%22/%3E%3Ctext%20x=%2250%22
%20y=%2265%22%20font-size=%2260%22%20text-anchor=%22middle%22%20fill=%22lime%22%20font-family=%22mono
space%22%3EMD%3C/text%3E%3C/svg%3E">
```

