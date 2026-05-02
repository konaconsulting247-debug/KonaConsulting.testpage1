# Kona Consulting Test Page

This repository hosts a static landing page for Kona Consulting.

- The deployable site entry point is `index.html`.
- This page is ready to deploy on Vercel as a static site.

## Contact Form Setup

The contact form uses Formspree to send emails. To set it up:

1. Go to [Formspree](https://formspree.io/) and sign up for a free account.
2. Create a new form and note the form ID (it looks like `xeqwryqk`).
3. In `public/index.html`, replace `YOUR_FORM_ID` in the form action with your actual form ID.
4. Set the form's email destination to `konaconsulting247@gmail.com` in your Formspree dashboard.

## Deployment

1. Push this repository to GitHub.
2. Connect the repository in Vercel.
3. Vercel will automatically deploy the static site.
