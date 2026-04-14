# MediNex Static Preview

This repository contains a static GitHub Pages preview of the MediNex healthcare UI.

It is designed for demo and preview purposes only. The pages keep the interface and dashboard layout, but backend features such as PHP, database access, sessions, and real authentication are not included.

## Preview Entry Points

Use these files when previewing or publishing the site:

- `index.html`
- `login.html`
- `signup.html`
- `forgot-password.html`
- `admin/index.html`
- `doctor/index.html`
- `patient/index.html`

## Demo Login Credentials

Use these exact demo accounts from the login page:

- Patient: `patient@medinex.demo` / `123`
- Doctor: `doctor@medinex.demo` / `123`
- Admin: `admin@medinex.com` / `123`

New accounts created from `signup.html` are stored in the browser with `localStorage` and open the patient dashboard in demo mode.

## Project Structure

- `index.html` - landing page
- `login.html` - demo login page
- `signup.html` - demo signup page
- `forgot-password.html` - demo password reset page
- `admin/` - admin dashboard preview
- `doctor/` - doctor dashboard preview
- `patient/` - patient dashboard preview
- `css/` - shared stylesheets
- `img/` - images and icons

## GitHub Pages

This project is now organized to publish directly from the repository root.

For GitHub Pages:

1. Push the repository to GitHub.
2. Open the repository on GitHub.
3. Go to `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main`.
6. Select folder `/ (root)`.
7. Save.

After deployment, the site will be available at:

`https://monowaraman-arch.github.io/Project_Medinex_Preview/`

## Demo Limitations

- Authentication is demo-only
- Signup stores demo users only in the current browser
- Forgot password is preview-only
- Dashboard numbers and content are sample data
- Sidebar links inside dashboards are mostly static preview links

## Local Preview

You can preview the site by opening `index.html` directly in a browser, or by serving the repository root with any static server.
