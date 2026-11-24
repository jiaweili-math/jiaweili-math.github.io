# jiaweili-math.github.io

Personal academic website of Jiawei Li, Lecturer in Probability at the University of Edinburgh.

Live at **https://jiaweili-math.github.io**

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site: content, styles and script in one file |
| `freddie.jpg` | Photo of Freddie shown in the About section |
| `README.md` | This file |

## First-time setup

1. On GitHub, create a **public** repository named exactly `jiaweili-math.github.io`.
2. In the repo, click **Add file → Upload files**, drag in `index.html`, `README.md` and `freddie.jpg`, then **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: `main` / `(root)`**, then **Save**.
4. After 1–2 minutes the site is live at https://jiaweili-math.github.io.

**The photo:** to swap it, replace `freddie.jpg` with any portrait image (about 4:5). If the file is missing, the site simply hides that figure.

## Updating content

Open `index.html` on GitHub, click the pencil icon, edit, and commit. The site refreshes within a minute or two.

- **Add a paper:** copy any `<li class="pub" …> … </li>` block in the Publications list and edit it. Set `data-type="preprint"` or `data-type="published"`; the filter counts update automatically. Wrap your own name as `<b>J. Li</b>` so it's highlighted.
- **Add a talk:** copy an `<li>` in the Talks section into the right year (newest first). For an in-person talk keep `data-geo="latitude,longitude" data-city="…" data-country="…"` — that puts it on the globe tour. For an online talk drop those attributes and add `<span class="tag on">online</span>`. Online talks appear on the globe at the home base of the time (Oxford before Sep 2019, Pittsburgh until Sep 2022, Edinburgh afterwards). Counts and globe statistics update automatically.
- **Add a course:** copy an `<li>` inside the Edinburgh card in the Teaching section.
- **Update the CV:** search the file for `drive.google.com/file/d/1Wkdm` (it appears three times) and replace the link; update "July 2026" in the About and Contact sections.
- **Colours:** all colours are defined at the top of the `<style>` block under `:root` (e.g. `--accent`).
