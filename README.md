# EricMillington.com

Eric's personal site, built straight from his hand-drawn mockup (`source.jpg`).

- The drawing is cut into pieces along its pen strokes (`p-*.jpg`). On desktop each piece sits exactly where it was drawn; on phones (720px and narrower) the same pieces stack vertically.
- The links, the three form fields and the **Go!** button are real, invisible elements laid over the drawn boxes, so the page looks exactly like the drawing but works.
- **Boiling lines:** pointing at a drawn link makes its pen strokes shimmer like hand-drawn animation frames, and the section you jump to boils briefly when you land (SVG turbulence filters in `index.html`). Turned off for visitors who prefer reduced motion.
- No build step: open `index.html` in a browser, or serve the folder from any static host (GitHub Pages, Netlify, Cloudflare Pages).

**Contact form → Formspree.** The form is wired for [Formspree](https://formspree.io): it sends in the background and shows "Thanks! Talk soon." (or a retry message if sending fails), with a hidden spam trap. The form's `action` in `index.html` is `https://formspree.io/f/xbggzdpo`; set it back to `#` for demo mode.

Built from the sketch template in [ericmillington/SampleWebsite](https://github.com/ericmillington/SampleWebsite) (`templates/sketch/`).
