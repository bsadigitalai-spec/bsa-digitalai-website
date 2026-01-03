# BSA Digital AI — Marketing Portal (Static Site)

This is a lightweight, **static** marketing portal designed for AWS Amplify / GitHub hosting.

## Pages
- `index.html` — home / overview
- `professional-examples.html` — curated embeds and links
- `chatbot.html` — marketing concierge intake + chatbot embed placeholder

## Update your email
Replace `add-your-contact-email-here` inside `index.html` and `chatbot.html`.

## Add your official logo
Replace `assets/img/bsa-digitalai-logo.png` with your official logo file.
Keep the same filename, or update the `<img src=...>` references.

## Deploy to AWS Amplify
1. Push these files into your GitHub repo (root level).
2. In AWS Amplify: New App → Host web app → GitHub → select repo → branch `main`.
3. Framework: Static. Build command: none. Output: `/`.
