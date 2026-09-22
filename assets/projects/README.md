Drop project report PDFs here with these exact filenames — the Projects
cards in `index.html` link straight to them. Source paths below are local to
this machine (`~/Documents/IMPERIAL/assessment/...`); full sourcing detail,
confidence levels, and flags are in `~/Downloads/pages_info.md`.

- `buckley-leverett-displacement.pdf` ← `assessment/GEMS2/report/solving_flow_eq.pdf`
- `geothermal-ates.pdf` ← **not yet located** — this paper's source PDF wasn't
  found anywhere under `assessment/`. Point Claude at the real path, or drop
  the file in here yourself.
- `co2-storage-uncertainty.pdf` ← **not yet located**, same situation as above.
- `co2-plume-migration.pdf` ← `assessment/GEMS4/main.pdf` — **do not** use
  `assessment/GEMS4/SWAINE_2026_GEMS4Assignment.pdf`, a byte-identical
  duplicate that's literally filename-branded as an assignment.
- `atlas-co2-structural-model.pdf` ← `assessment/assessment_6/gems1-assessment-ada-jas25/answers.pdf`
  — **CAUTION**: this write-up was built from Imperial-provided contour/fault
  maps and well data. Check it doesn't embed proprietary figures before
  adding it here — it may need figures redacted, or to ship with the card's
  description only and no PDF at all.
- `pressure-transient-analysis.pdf` ← `assessment/GEOMECHANICS/solving_flow_eq.pdf`
  — **note the filename collision**: this source file has the exact same
  name as the Buckley-Leverett source above, but is a completely different
  document. Double-check you're copying the right one.

No PDF is expected yet for the remaining Projects cards (mcsim, the
environmental data pipeline, the numerical verification & validation study,
the wind resource classifier, or the ECG deep learning project) — those are
code-only entries for now.

Same behaviour as `assets/papers/`: a link with `target="_blank"` and no
`download` attribute opens the PDF in the browser's own viewer in a new tab;
the matching `download`-attribute link forces a save instead.
