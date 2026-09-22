Drop publication PDFs here with these exact filenames — the Publications
cards in `index.html` link straight to them:

- `seismic-ensemble.pdf` — your own copy of the seismic ensemble paper
  (linked as both "read paper" and "download pdf" on card 1)
- `max-phase-generative.pdf` — optional author copy of the MAX phase paper,
  for the "download pdf" button on card 2 (the "view in journal" button
  already points at the DOI, so this file is only needed if you want to
  offer a separate downloadable copy)
- `euromat-poster.pdf` — the FEMS EUROMAT 2025 poster (card 4)

No file is needed yet for the Brain-EffNet entry (card 3) — it's under
review, so its buttons are wired to show a placeholder message instead of
opening anything. Once it's accepted or otherwise public:

1. Add `brain-effnet.pdf` here (or link out to wherever it's hosted).
2. In `index.html`, replace the two `<button class="pub-link" ... data-unavailable="...">`
   elements on that card with `<a>` links in the same style as card 1 or 4.
3. Delete the now-unused `<p class="pub-note" hidden></p>` line and the
   `data-status="under-review"` attribute on the `<article>`.

Any PDF linked with `target="_blank"` (no `download` attribute) opens
directly in the browser's own PDF viewer in a new tab rather than forcing
a download — that's the "read paper" behaviour. The matching "download pdf"
link points at the same file but adds the `download` attribute, which forces
a save instead.
