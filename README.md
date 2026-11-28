# Dhinwa Site Lessons

Animated lessons for all 22 chapters of the Dhinwa Construction Engineering Technology Manual.
This is a plain static website: HTML files only, with no build step and no server code.

## What is inside

```
index.html            Home page: all 22 chapters, search, links
chapters/             One self-contained lesson page per chapter
  safety-chapter-1.html … structural-glazing-acp-chapter-22.html
assets/gsap.min.js    Animation library (GSAP 3.12.5), kept locally so lessons work offline
.nojekyll             Tells GitHub Pages to serve the files as they are
```

Every chapter page has an "All chapters" button and previous/next chapter links at the top of its sidebar.
Fonts load from Google Fonts; without internet the pages fall back to system fonts and still work.

## Open it on your computer

Unzip the folder and double-click `index.html`. No installation is needed.

## Put it online (pick one)

**Netlify Drop (easiest, about 1 minute)**
1. Go to https://app.netlify.com/drop and sign in.
2. Drag the whole `dhinwa-site` folder onto the page.
3. Netlify gives you a live link. To update later, drag the folder again in the site's Deploys tab.

**GitHub Pages (free)**
1. Create a new repository on GitHub and upload everything inside `dhinwa-site` (keep the folders).
2. Open Settings → Pages, choose "Deploy from a branch", branch `main`, folder `/ (root)`, then Save.
3. Your site appears at `https://<your-username>.github.io/<repository-name>/` after a minute or two.

**Vercel**
1. Go to https://vercel.com/new, import the GitHub repository from the step above (or use `npx vercel` inside this folder).
2. Framework preset: "Other". Leave the build command empty and the output directory as the root.

**Any web host or company server (cPanel, IIS, Nginx, Apache)**
Upload the contents of `dhinwa-site` to the public web folder (for example `public_html`). Keep the folder structure as it is.

## Notes

- Checklist answers (Yes / NA) are saved in each viewer's own browser only. They are not sent anywhere.
- To change a lesson, edit its file in `chapters/`. Each file contains its own styles, drawings and script.

## Narration (all 22 chapters)

Turn on **Narrate** in the player and pick **English** or **हिंदी**. A point only moves on when its narration has been read in full **and** its animation has finished; Pause/Play stops and resumes both together. Hindi needs a Hindi voice in the browser or OS (Chrome and Edge include one; on Windows add "Hindi" under Settings → Time & language → Speech if it is missing).
