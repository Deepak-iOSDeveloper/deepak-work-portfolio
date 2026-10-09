# Deepak Behera — Cinematic Portfolio

A responsive React + Vite + Tailwind portfolio starter for a freelance video editor, short-form filmmaker and travel creator.

## Run locally

```bash
npm install
npm run dev
```

For a production build:

```bash
npm run build
npm run preview
```

## Change your content

Most content lives in `src/data.js`: project titles/categories/images/links, services and starting rates, gallery, tools, social URLs and stats. The layout is in `src/main.jsx`, with styles in `src/style.css`.

- **Your two uploaded photos:** `public/images/deepak-trek-back.png` and `public/images/deepak-trek-portrait.png`. They are used in the trekking gallery and About section; other imagery remains placeholder stock photography.
- **Instagram:** set in `src/data.js` as `https://www.instagram.com/deepak_trek/`; linked as your work showcase and social contact.
- **Reel media:** update each item in `profile.reels` with your own `image`, `link`, and optional `video` URL. The `video` field is ready for adding previews in the card markup.
- **Hero video:** add an MP4 URL/path to `profile.heroVideo` and wire it into the hero if desired; currently a cinematic still is used to keep the starter fast.
- **Contact form:** front-end demo only. Connect Formspree, Web3Forms, or your own endpoint to receive submissions.
- **Email and other socials:** replace the placeholder email, YouTube and WhatsApp links in `src/data.js`.
- **Prices, testimonials and counters:** all are placeholders; edit them to match your actual rates and experience before publishing.

## Deploy

Deploy the folder to Vercel or Netlify as a Vite app. Build command: `npm run build`; output directory: `dist`.
