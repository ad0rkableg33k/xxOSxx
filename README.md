# xXOnlineStatusXx Podcast

The official site for the xXOnlineStatusXx Podcast — three hosts, one Discord server, zero filter. Migrated from Replit to a static GitHub Pages site.

## Pages

- `index.html` — Home
- `hosts.html` — Meet The Hosts (BabyyBATxoxo, Drag0n, The Intoxicologist)
- `episodes.html` — Episodes Board (aired, on-air, and upcoming schedule)
- `guest-signup.html` — "Be A Guest" application form
- `volunteer.html` — "Volunteer Your Soul" crew signup form

## Forms

Both forms are connected to Formspree and submit to the same endpoint (`https://formspree.io/f/xnjenwdj`). Submissions land in the inbox tied to that Formspree account.

**One-time step:** Formspree requires a confirmation submission before it starts forwarding to email — submit each form once after publishing to activate it, if you haven't already.

If you'd rather split guest applications and volunteer signups into separate inboxes later, create a second form at [formspree.io](https://formspree.io) and swap the `action="..."` URL in `volunteer.html` to the new endpoint.

## Tech Notes

- Vanilla HTML/CSS, no build step, no framework — one shared `styles.css`.
- Fonts: Cinzel (display/headers) + Poppins (body), loaded from Google Fonts.
- Color system: pink/magenta/purple neon-glow accents on a white background, defined as CSS variables at the top of `styles.css`.
