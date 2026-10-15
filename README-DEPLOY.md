# Own the Plot — website

A responsive 3-page site: **Home**, **Schedule**, **Tools** (+ a form thank-you page).

## Files
- `index.html` — home
- `schedule.html` — studios, private/online, beach Pilates waitlist form
- `tools.html` — Honest Check-In + Substack
- `thank-you.html` — shown after the beach form is submitted
- `styles.css` — all styling (shared)
- `images/` — your photos

## Put it live on Netlify (5 minutes)
1. Go to **app.netlify.com** → **Add new site → Deploy manually**.
2. **Drag this whole folder** onto the upload area. Netlify gives you a live URL immediately (e.g. `something-random.netlify.app`) — that's your live preview.
3. **Your domain:** Site settings → **Domain management** → **Add a domain** → enter your domain, then follow Netlify's DNS instructions (add their records at wherever you bought the domain). Free HTTPS turns on automatically.

## Waitlist emails (Netlify Forms — already wired)
- The Beach Pilates form is set up for Netlify. Once deployed, submissions appear under the **Forms** tab in your Netlify dashboard.
- To get emailed on each signup: **Forms → Form notifications → Add notification → Email**.
- Export anytime as CSV from the Forms tab.

## Fonts
- **Ferffernanda Notes** (your handwriting) is embedded and live — files live in `fonts/` and are wired up in `styles.css`.
- Body text still uses **Inter** as a stand-in for TT Norms (TT Norms is paid). When you have the TT Norms files, drop them in `fonts/`, uncomment the block near the top of `styles.css`, and change `--font-sans`.

## Notes
- Booking links go to your studios' live pages (306, AERA, Vybe), so schedules stay current with nothing to maintain.
- Private, online, and health/astrology enquiries open WhatsApp to +971 58 1919647.
