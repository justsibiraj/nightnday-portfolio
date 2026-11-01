# Night&Day portfolio

## Preview
Open `index.html` in a browser. No build tools or backend needed.

## Update films
Open `projects.js`. Each object in `PROJECTS` represents one film. Edit its `title`, `summary`, `services`, `deliverables`, and `gallery`. Add another object to add a film. Keep `id` unique (lowercase letters and hyphens recommended).

Example image entries:
```js
poster: 'assets/youth-poster.jpg',
banner: 'assets/youth-banner.jpg',
gallery: ['assets/youth-campaign-1.jpg', 'assets/youth-campaign-2.jpg'],
```
Put those files in the `assets` folder. Leave any image entry as `''` for a placeholder. Replace the placeholder text with your verified film credits and campaign details.

## Update company information
Edit `SITE` at the bottom of `projects.js` for intro, about, services, team, email and Instagram. Team photos work the same way: `photo:'assets/team-member.jpg'`.

## GitHub Pages
1. Create a public GitHub repository (e.g. `nightnday-website`).
2. Upload **the contents** of this folder to the repository root (not the enclosing folder).
3. In GitHub go to Settings → Pages → Build and deployment → Deploy from a branch.
4. Choose `main` and `/ (root)` and save.
5. Wait a few minutes. Your site will appear at `https://YOUR-USERNAME.github.io/nightnday-website/`.
6. For edits, update `projects.js` and/or images and commit; GitHub Pages redeploys automatically.

This is a standalone static site. No login/admin dashboard is included. Edit the code to manage content.
