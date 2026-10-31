# EricRobertsLive

Website for Eric Roberts' performer persona, "Eric Roberts Live": casual live acoustic
music (porches, house parties, small rooms, wineries). Eric is a hobbyist player, not a
pro gig worker; keep the tone friendly and easygoing. Domain: ericrobertslive.com.

## Stack

- Plain HTML + CSS: `index.html`, `styles.css`. No build step, no framework, no npm.
- Ask before adding any dependency, script or build tool.
- Hosting plan: Vercel Hobby (free), deployed from GitHub. Not set up yet.
- Domain: ericrobertslive.com, registered at GoDaddy (bought 2026-10-25, auto-renews
  2027-10-25). DNS not set up yet; it still shows GoDaddy parking.

## Song list and requests live in PickThisPlayThat

- "See My Songs" (and the Songs nav link) go to https://pickthisplaythat.com/p/eric.
  That page shows a "Live Now · Request a Song" banner while Eric has an event live.
- Never copy the song list onto this site; link to PT instead.
- PickThisPlayThat is a separate project (`C:\Dev\pt-app`). Don't change files there
  from this project.

## Look

Warm and rustic. Colors are CSS variables at the top of `styles.css`:

- cream #f6efe3 for sections and paper #fbf7f0 for the page
- wood #6b4a2f and dark wood #3b2a1c for headings
- ink #2b211a for text and muted #6b5a4c for secondary text
- PT's orange #a8461c as the accent (primary button, links, eyebrow line)

Headings use Fraunces (serif) and body text uses Source Sans 3, both from Google Fonts.

- Mobile first: check every change at phone width (375px) and on a computer.
- Buttons are pills that size to their text (no full-width buttons) and are at least
  48px tall.
- Use Title Case for headings and buttons.
- No dark mode.

## Page today

- **Hero:** eyebrow line, "Eric Roberts Live", a one-line tagline, "See My Songs" and
  "Book Me" buttons, and the photo.
- **Photo:** `images/hero.jpg`, Eric with his guitar in a hayfield (Aug 2011, from his
  Facebook Profile Pictures album). It's only 465 x 295, so the box is wide (8:5).
  Replace the file with a bigger original if one turns up; if the file is missing, a
  wood-toned placeholder shows.
- **Coming Soon cards:** Upcoming Shows, About, Photos & Video and Contact. Fill these
  in one at a time, as Eric decides what goes in each.
- **Upcoming Shows plan:** keep shows in one simple place that is easy to edit.

## Working style

- Eric likes to see a mockup before a change is built. Explain things in plain
  language.
- Make small, reviewable commits. After each commit, tell Eric the 7-character commit ID
  in CAPITALS (for example 8EB3F12) so he knows which version to check.
- Every commit that changes what visitors see adds a line to `docs/CHANGELOG.md` under
  today's date.
- Ask before any GitHub, Vercel or GoDaddy account change, DNS change or purchase.
  Never type passwords. On GoDaddy, never touch existing @ or www records without
  asking first.
- Use they/them for anyone whose pronouns aren't known.

## Next steps

1. Create a GitHub repo and push.
2. Connect it to Vercel Hobby.
3. Point ericrobertslive.com at Vercel from GoDaddy. Vercel gives the site free HTTPS.
4. Fill in the Coming Soon sections.
