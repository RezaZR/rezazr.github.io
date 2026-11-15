# rezazr.github.io

Public website for games by rezazr, served by GitHub Pages at https://rezazr.github.io/ from the `main` branch root of the public repository `RezaZR/rezazr.github.io` (personal account; never the employer's).

## Pages

| URL | File | Used by |
|---|---|---|
| `/` | `index.html` | Developer website in Google Play Console and App Store Connect |
| `/rzrfm/` | `rzrfm/index.html` | RZRFM marketing URL |
| `/rzrfm/privacy.html` | `rzrfm/privacy.html` | Privacy policy URL (Play Console app content, App Store Connect, in-game link) |
| `/rzrfm/support.html` | `rzrfm/support.html` | Support URL and contact |
| `/app-ads.txt` | `app-ads.txt` (add when LevelPlay provides its lines) | Ad network seller verification; must sit at the domain root |

Static HTML and one stylesheet (`assets/site.css`); no JavaScript, cookies, analytics or external fonts. `.nojekyll` turns off Jekyll processing.

## Keeping the privacy policy true

The privacy policy describes RZRFM's real data flows, owned by the game repository specs `Docs/Release/COMPLIANCE.md`, `Docs/Features/GLORY_SERVER.md` and `Docs/Release/MONETIZATION.md`. Update `rzrfm/privacy.html` and its effective date in the same change whenever the game adds an SDK, a data field, a server region or a new purpose, and keep the Google Play Data safety form and Apple privacy labels in step.

## Links

- Contact email: `rezazramadan1+games@gmail.com`, in every page footer and contact line.
- Discord: `https://discord.gg/p37fmb7Awj` (a never-expiring invite), in `rzrfm/index.html` and `rzrfm/support.html`.
- Add the Google Play and App Store links to `rzrfm/index.html` when the listings are live.

## Publish

```sh
git push origin main
```

GitHub Pages settings: Source "Deploy from a branch", branch `main`, folder `/ (root)`. Enforce HTTPS.
