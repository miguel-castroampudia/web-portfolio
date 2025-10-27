
# One-Page MBA Portfolio (Quarto)

## How to use locally
1. Install Quarto: https://quarto.org/docs/get-started/
2. Open a terminal in this folder and run:
   ```bash
   quarto preview
   ```
3. Edit `index.qmd` and `appendix.md`, then render:
   ```bash
   quarto render
   ```

## Deploy to GitHub Pages
1. Create a new GitHub repository named `mba-portfolio` (or any name).
2. Push this folder's contents to the repo.
3. In GitHub, go to **Settings » Pages**, set **Source** to `Deploy from a branch`, and choose the `main` branch and `/docs` folder.
4. Your site will be available at `https://<your-username>.github.io/<repo-name>/`.
