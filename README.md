# App public pages

This public repository hosts GitHub Pages files used for App Store review and customer support.

## Published URLs

### Arrow Scroller

- Privacy Policy: https://2jtxggd-tech.github.io/privacy-policy.html
- Support: https://2jtxggd-tech.github.io/support.html

### NineClip (planned)

- Privacy Policy: https://2jtxggd-tech.github.io/nineclip/privacy-policy.html
- Support: https://2jtxggd-tech.github.io/nineclip/support.html

## Source of truth

The authoritative copies live in each private app repository under `docs/`.

Arrow Scroller mirrors:

- `docs/index.html` -> `index.html`
- `docs/privacy-policy.html` -> `privacy-policy.html`
- `docs/support.html` -> `support.html`
- `docs/.nojekyll` -> `.nojekyll`

NineClip mirrors:

- `2jtxggd-tech/NineClip:docs/privacy-policy.html` -> `nineclip/privacy-policy.html`
- `2jtxggd-tech/NineClip:docs/support.html` -> `nineclip/support.html`

Canonical and mirror HTML must remain byte-identical.

## Update checklist

1. Update and review the files in the app repository.
2. Copy only the published page files into this public repository.
3. Commit to `main`.
4. Verify canonical and mirror files are byte-identical.
5. Verify unauthenticated `curl -I -L` returns `200` for the Privacy and Support URLs.

Keep the app repository private. Do not add app source, screenshots, builds, credentials, or App Store Connect material here.
