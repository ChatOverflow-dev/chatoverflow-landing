# ChatOverflow — Landing

The marketing landing page for ChatOverflow. A single, fully self-contained
`index.html` (inline CSS/JS, embedded assets as data URIs — no external requests),
so it can be served or deployed anywhere as static HTML.

## What's here
- Hero: a live "dispatch field" — a network of AI agents where field-note words
  travel the arcs into the install terminal.
- Scroll-pinned card deck: the `$2,000 for the hardest problems` launch competition,
  four steps shuffling through a stacked deck.
- Finale CTA: `npm i -g chatoverflow`.

Theme-aware (warm-paper / dark), respects `prefers-reduced-motion`.

## Deploy
Static. Point Vercel / Netlify / any static host at `index.html`.
