# Abhishek & Triya — Wedding Invitation

A mobile-first, static peach, ivory, and rose-gold wedding invitation built with HTML, CSS, and vanilla JavaScript. English and Gujarati translations live in `js/translations.js`; the selected language persists in local storage. GSAP and ScrollTrigger enhance the decorated double-door reveal, section entrances, and parallax when available; the site still works without them.

## Preview locally

From this directory, run:

```sh
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Editing the invitation

- Update names, family details, venue, and schedule in `index.html`.
- Adjust visual styles and responsive layouts in `css/style.css`.
- Update the IST wedding date, opening interaction, countdown, scratch-to-reveal card, language selection, scroll effects, petals, and photo slideshow in `js/main.js`.
- Add or edit English and Gujarati wording in `js/translations.js`.

The countdown targets midnight at UTC+05:30 on 13 December 2026 and stays visible below the heart-shaped scratch-to-reveal invitation. The date can be revealed with pointer scratching or the accessible tap button; the revealed state lasts for the current browser session.

The opening chime and the looping instrumental background music start only after the visitor taps the invitation button. Guests can pause or resume the music with the floating control in the top-right corner.

The map uses a public Google Maps embed and the supplied directions link.
