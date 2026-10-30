# xivn.dev — Midnight Winter V6

Source code for the complete **xivn.dev** Minecraft developer portfolio.

## What's included

- 9 HTML pages: Home, Work, Services, Reviews, About, Contact, plus SaverCraft, The Vale, and AceMC case studies
- `styles.css`: complete responsive design, winter atmosphere, and entrance animations
- `site.js`: snowfall effect, snow preference toggle, mobile navigation, reveal animations, and copy-to-clipboard inquiry form
- `assets/`: original Discord review screenshots
- `favicon.svg`: favicon

## Preview the entire site

**Option 1 — GitHub Pages (no installation):**

1. Extract the ZIP. Keep the **contents** of this folder together. Do **not** upload the ZIP as one file to your repository.
2. Create a new GitHub repository, such as `xivn-website`. Don't name it `xivn.dev` unless that is your preferred repository name.
3. On GitHub, choose **Add file → Upload files**, and upload the extracted contents, including the `projects` and `assets` folders. Keep `index.html` in the repository root. If your browser won't upload folders, use Git or VS Code instead.
4. Commit the files to the `main` branch.
5. Go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select **main** and **/(root)**, and save.
6. Open the public preview URL GitHub Pages provides. A project repository is usually served at `https://YOUR-USERNAME.github.io/xivn-website/` (replace both placeholders).

No `.github/workflows` file, `npm install`, or build command is required. The site's internal links use relative paths so they work under a GitHub Pages project URL.

**Option 2 — local browser:** Extract the folder and double-click `index.html`. Most of the site can be browsed directly, but clipboard features can require a secure browser context (HTTPS or localhost).

**Option 3 — Netlify Drop:** Extract the ZIP and upload the folder containing `index.html` to https://app.netlify.com/drop for a temporary shareable site. Do not connect your live xivn.dev domain until you approve the preview.

## Update the site

- Edit page content in the corresponding `.html` file.
- Edit colors, layout, snowfall appearance, and animations in `styles.css`.
- Edit snow density, navigation, and inquiry clipboard behavior in `site.js`.
- Replace or extend review screenshots in `assets/` and update links in `reviews.html`.
- Update server hyperlinks in `work.html` after verifying the current official URLs.
- The main commission link is `https://discord.gg/Pr4ZYjNA2f`. Search that exact URL if you need to change it later.

## Important limitations before launching

- The contact form does **not** send messages. It copies the inquiry to the user's clipboard for pasting into Discord; the fallback box appears if copying fails.
- No public price list is included. Commissions are handled privately via Discord.
- Some project details and external links still need your final approval. Check individual server URLs and case-study wording before publishing the site as your official portfolio.
- This is a **static website**, not a Next.js project. No package manager, backend, database, or secrets are required.
- The review screenshots are part of your supplied content. Confirm you want them publicly visible before releasing the site.

## File structure

```text
index.html
work.html
services.html
about.html
reviews.html
contact.html
projects/
  acemc.html
  savercraft.html
  the-vale.html
assets/
  discord-reviews-1.webp
  discord-reviews-2.webp
styles.css
site.js
favicon.svg
.nojekyll
.gitignore
README.md
```
