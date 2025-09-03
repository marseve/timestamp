# Timestamp (Jekyll on GitHub Pages)

## Quick Start
1. Create a new **public** repo on GitHub named `timestamp`.
2. Upload these files to the repo root.
3. Go to **Settings → Pages**. Under **Build and deployment**, set:
   - Source: **Deploy from branch**
   - Branch: **main**, Folder: **/** (root)
4. Wait ~1 minute. Your site will be at `https://USERNAME.github.io/timestamp`.

## Daily Post
- Create a new file in `_posts/` named `YYYY-MM-DD-title.md` with the front matter:
  ```yaml
  ---
  layout: post
  title: "Your Title"
  date: YYYY-MM-DD
  tags: [timestamp, oracle]
  ---
  ```
- Put images in `assets/img/YYYY/` and link like:
  `![caption](/assets/img/2025/09-03.jpg)`

## Notes
- Uses the built-in **minima** theme (clean, simple).
- You can change theme later by editing `_config.yml`.