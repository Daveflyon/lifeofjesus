# The Life of Jesus - Part 1

Youth Bible study, 8 lessons. Static HTML, no build step.

- Live: https://lifeofjesus.pages.dev/
- Deploy: Cloudflare Pages, auto-deploys on push to `main`.

| Setting | Value |
|---|---|
| Git repository | `Daveflyon/lifeofjesus` |
| Production branch | `main` |
| Framework preset | None |
| Build command | (empty) |
| Build output directory | `/` |

Source of truth: the Google Site "The Life of Jesus". Each lesson page here wraps that lesson's embed HTML unchanged.

Publish: `git add -A && git commit -m "..." && git push origin main`
