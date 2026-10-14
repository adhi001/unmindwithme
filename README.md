# Unmind with Me — website

A responsive single-page website for Pavithra Jayanthi / Unmind with Me, styled around the cream, olive, terracotta, and gold palette of the supplied brand image.

## Preview locally

Open `index.html` in a web browser. The site uses a Google Fonts link, so the custom fonts load when there is an internet connection; fallback fonts are included.

## Contact and booking forms

Both the session request form and enquiry form currently use FormSubmit and target `positivel071@gmail.com`:

- Session request subject: `New session request — Unmind with Me`
- Enquiry subject: `New enquiry — Unmind with Me`

**One-time activation:** FormSubmit normally sends a verification/activation email to the recipient when the form is first used. Open that message in `positivel071@gmail.com` and activate the form. After activation, new form submissions can be delivered to that inbox. Test both forms after activation. Form submissions are not a live booking calendar; they are requests pending confirmation.

If you prefer not to use a third-party form processor, replace the form actions with your own secure backend endpoint. Do not put email account passwords or SMTP credentials in browser-side HTML or JavaScript.

## Deploy

Upload the entire `unmind-with-me` folder (including `assets/unmind-brand.png`) to a static host such as Netlify, GitHub Pages, or your existing web host. No build step is needed. The site is responsive and includes reduced-motion support for accessibility.

## Before publishing

- Confirm the public-facing name, title, professional credentials, services, and whether sessions are online or in person.
- Add only accurate qualifications and claims.
- Consider adding a privacy notice explaining how booking/enquiry data is handled, and set up a custom domain if desired.
