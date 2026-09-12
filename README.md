# German IT Vocabulary Shooter

A browser-based balloon-shooting game for practicing German IT vocabulary, styled after a Berlin/Brandenburg Gate shooting-gallery theme.

## Run it locally
Just open `index.html` in any modern browser (Chrome, Safari, Firefox, Edge). No build step, no dependencies — it's a single self-contained HTML file.

## Publish it live on GitHub Pages (free hosting)

1. **Create a GitHub account** (skip if you already have one): https://github.com/join

2. **Create a new repository**
   - Go to https://github.com/new
   - Name it whatever you like, e.g. `german-it-shooter`
   - Set it to **Public**
   - Click **Create repository**

3. **Upload the file**
   - On your new repo's page, click **Add file → Upload files**
   - Drag in `index.html` from this package
   - Scroll down, click **Commit changes**

4. **Turn on GitHub Pages**
   - In your repo, go to **Settings → Pages** (left sidebar)
   - Under "Build and deployment" → **Source**, choose **Deploy from a branch**
   - Under **Branch**, choose `main` and folder `/ (root)`, then **Save**

5. **Wait ~1 minute, then visit your live game**
   - GitHub will show a URL like:
     `https://YOUR-USERNAME.github.io/german-it-shooter/`
   - That's it — it's live, and free, and updates automatically any time you upload a new `index.html`.

## Updating the game later
Any time you want to change the game, just edit `index.html` (or ask for a new version) and re-upload it via **Add file → Upload files** in your repo, overwriting the old one, then commit. GitHub Pages redeploys automatically within a minute or two.

## Alternative: git command line
If you prefer git instead of the web upload UI:

```bash
git init
git add index.html README.md
git commit -m "Initial commit: German IT vocabulary shooter"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/german-it-shooter.git
git push -u origin main
```
Then enable Pages as in step 4 above.
