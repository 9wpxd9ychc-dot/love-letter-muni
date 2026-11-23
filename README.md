# LOVE LETTER — MUNI

A premium, mobile-first romantic letter experience built with Three.js and Cloudflare Pages.

## Features

- Real-time Three.js scene: dimensional envelope, hinged opening flap, wax seal, sculpted roses, floating petals, cinematic lighting and pointer parallax.
- Coordinated letter reveal with a repeatable open/close interaction.
- Original ambient melody generated with the Web Audio API; playback starts only after the visitor taps the sound control.
- Soft envelope interaction sound, also gated by the visitor's first interaction.
- Responsive layout, reduced-motion support, keyboard close (Escape), accessible labels and a lightweight mobile rendering profile.
- Loading state and a CSS envelope fallback if the 3D module cannot load.
- No backend, account, paid API, or copyrighted music.

## Personalize the letter

Edit `letter-content.js`:

- `greeting` — salutation.
- `message` — the actual personal note.
- `signature` — sender's sign-off.

The current message is intentionally a placeholder.

## Run locally

Serve the repository root over HTTP:

```bash
python -m http.server 8080
```

Open http://localhost:8080.

Three.js is loaded from jsDelivr and fonts from Google Fonts. An internet connection is needed for those external resources.

## Deployment

Cloudflare Pages is connected to the GitHub repository `9wpxd9ychc-dot/love-letter-muni`, production branch `main`, with the repository root as the output directory. Pushing to `main` triggers a production deployment.
