# regina-go

## Deploy to GitHub Pages

1. Build the site:
   ```bash
   hugo
   ```
2. Go to the output directory:
   ```bash
   cd public
   ```
3. Commit the built site:
   ```bash
   git add . && git commit -m "Commit message"
   ```
4. Push to `gh-pages`:
   ```bash
   git push origin gh-pages
   ```
5. Return to the project root:
   ```bash
   cd ..
   ```
6. Commit the source changes:
   ```bash
   git add . && git commit -m "Commit message"
   ```
