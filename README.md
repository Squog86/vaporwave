# Vaporwave: Aesthetic of Nostalgia

## Accessibility Fixes (WAVE & WCAG AA)
- I removed a stray closing `</figure>` tag and duplicate `<figcaption>` on `index.html` to fix broken HTML structure for screen readers.
- I changed duplicate `<h1>` tags to `<h2>` and adjusted skipped `<h3>` headings so every page follows a strict `<h1>` to `<h2>` to `<h3>` hierarchy.
- I updated heading colors from `#ff007f` (4.2:1) to `#ff66b2` (6.8:1) and form error states to `#ff8080` (7.4:1) so all text meets WCAG AA contrast standards.
- I added explicit `<label>` elements, `<fieldset>`/`<legend>` grouping, `aria-required="true"`, and `role="alert"` error messages to the contact form on `about.html`.

## Visual Design & Gestalt Principles
- **Proximity:** I used proximity by grouping related subgenre descriptions, visual motifs, and form inputs inside unified `.feature-card` and `fieldset` containers with tight internal padding and wider margins between separate cards.
- **Similarity:** I used similarity by applying a consistent midnight purple (`#0d0221` / `#19053b`), neon cyan (`#00f0ff`), and bright magenta (`#ff66b2`) palette with matching rounded borders across all three pages.
