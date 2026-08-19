# patterngen

A working set of generative pattern tools — mostly data-driven and tactics-board abstractions
rendered as SVG or canvas, each exportable as SVG and/or PNG. Every tool is a single
self-contained HTML file; no build step, no dependencies.

Open `index.html` to browse all generators through a menu (sidebar on desktop, hamburger on
mobile). Add a new generator by appending one entry to the `REGISTRY` array at the top of
`index.html`'s script.

## Generators

- **Line Field** — [`line_field_generator.html`](line_field_generator.html): abstract
  tactics-board line field with even/random/clustered spread, Blob/Line/L/U bundle shapes,
  arrowheads, SVG/PNG export.
- **Vector**
  - [`vector_telemetry_overlay.html`](vector_telemetry_overlay.html): hairline hatch bands,
    crosshair tags and monospace readouts layered like GPS/EPTS telemetry.
  - [`vector_trace.html`](vector_trace.html): organic metaball blobs rasterized onto a coarse
    vector grid.
- **Data Rhythm**
  - [`data_pattern.html`](data_pattern.html): one column per data set; height and color trace
    the running score.
  - [`data_pattern_soft.html`](data_pattern_soft.html): the same columns rendered as wavy soft
    blooms instead of hard bars.
  - [`data_pattern_soft_animated.html`](data_pattern_soft_animated.html): soft-bloom render with
    a rippled-glass animation pass.
  - [`material_studio.html`](material_studio.html): the soft-bloom engine rendered through a
    tiles & tufted-rug material layer.
- **Tape Numerals** — [`tape_numeral_generator.html`](tape_numeral_generator.html): two-digit
  numbers built from a 7-segment layout, each segment its own hand-cut tape strip.

## Notes

- `_ref/` holds local design-reference images and notes used while building these tools. It's
  gitignored and kept local only — not needed to run or edit any generator.
