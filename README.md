# Arrow Scroller public pages

This public repository hosts the GitHub Pages files used for App Store review of Arrow Scroller.

## Published URLs

- Privacy Policy: https://2jtxggd-tech.github.io/privacy-policy.html
- Support: https://2jtxggd-tech.github.io/support.html

## Source of truth

The authoritative copy lives in the private app repository `2jtxggd-tech/ArrowScrollerSafari` under `docs/`.
Mirror only these files to the root of this repository:

- `docs/index.html` -> `index.html`
- `docs/privacy-policy.html` -> `privacy-policy.html`
- `docs/support.html` -> `support.html`
- `docs/.nojekyll` -> `.nojekyll`

## Update checklist

1. Update and review the files in the app repository.
2. Copy only the published page files into this public repository.
3. Commit to `main`.
4. Verify unauthenticated `curl -I -L` returns `200` for the Privacy and Support URLs.

Keep the app repository private. Do not add app source, screenshots, builds, credentials, or App Store Connect material here.
