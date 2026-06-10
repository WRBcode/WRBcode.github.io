# Ruibo Wang — Academic Homepage

Single-file static site (`index.html`), no build step needed.

## Deploy to GitHub Pages (github.io)

1. Create a repo named **`<your-username>.github.io`** on GitHub (must match your username exactly).
2. Push this folder:
   ```bash
   cd ~/projects/cv/homepage
   git remote add origin git@github.com:<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. Wait ~1 minute — the site goes live at `https://<your-username>.github.io`.

## TODO before going live

- [ ] **Photo**: drop a `photo.jpg` in this folder, then in `index.html` replace
      `<div class="ph">RW</div>` with `<img src="photo.jpg" alt="Ruibo Wang">`.
- [ ] **CV PDF**: export the latest CV from Word as `Ruibo_Wang_CV.pdf` and put it in this folder
      (the "CV ↓" button links to it).
- [ ] **Links**: fill in your real Google Scholar / GitHub URLs in the hero buttons (`href="#"`).
