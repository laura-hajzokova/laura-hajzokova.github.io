# laura-hajzokova.github.io

Personal academic website of Laura Hajzoková. Plain HTML and CSS with no build step.

- `index.html`: all content (edit the text here)
- `style.css`: layout and colour palette (variables at the top)

## Publish on GitHub Pages
1. On GitHub, create a **public** repository named exactly `laura-hajzokova.github.io`.
2. Push this folder:
   ```
   git remote add origin https://github.com/laura-hajzokova/laura-hajzokova.github.io.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages** and set Source to *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. After a minute or two the site is live at https://laura-hajzokova.github.io

## Updating
Edit `index.html`, then run `git commit -am "Update" && git push`.
To add a photo, put `photo.jpg` in this folder and follow the comment in the hero section of `index.html`.
