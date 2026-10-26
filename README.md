# ruang website

The website for ruang (Ruang Psychological Solutions).

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `about.html` | About us |
| `who-are-we.html` | Who are we |
| `services.html` | Services |
| `group-therapy.html` | Group therapy |
| `events.html` | Events |
| `book.html` | Book a session |

Photos and videos are in `assets/`. `support.js` runs the pages' interactive parts (tabs, pickers, the photo viewer and so on), so keep it next to the HTML files.

## Publishing on GitHub Pages

1. Push everything in this folder to the root of your repository, including the hidden `.nojekyll` file.
2. On GitHub, open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick your main branch and the `/ (root)` folder, then save.
4. After a minute or two, the site will be live at the address GitHub shows on that page.

## Previewing on your own computer

The pages need to be opened through a web server. Double-clicking an HTML file won't work. From inside this folder, run:

```
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.
