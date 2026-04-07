# WebUI

This folder contains the static GitHub Pages demo version of the Healthcare UI.

## Demo entry points

Use these files when publishing or previewing the site:

- `index.html`
- `login.html`
- `signup.html`
- `forgot-password.html`
- `admin/index.html`
- `doctor/index.html`
- `patient/index.html`

The demo keeps the design and dashboard layouts, but replaces backend-driven features with sample data so it can run as a fully static site.

## Included assets

- shared styles in `css/`
- dashboard and landing page assets in `img/`
- local font files in `css/fonts/`

## Demo limitations

- Login, signup, password reset, and dashboard statistics are demo-only in the static version
- Sidebar navigation inside dashboard previews uses anchored sections on the same page
- No PHP, database, sessions, or real authentication are included in this folder

## GitHub Pages

For GitHub Pages, publish this folder with `index.html` as the main entry page.
