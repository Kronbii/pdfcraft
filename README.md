# PR evidence (not for merging)

Screenshots for two pull requests to storytold/pdfcraft. Everything here is synthetic:
`synthetic-scan.pdf` is three pages of Helvetica text written by PdfCraft, rendered at 300 dpi,
thresholded to black and white and placed back as image-only pages (no text layer), the way
office scanners and print-to-image drivers write documents.

- `compare-100.png`, `compare-400.png`: upstream `main` against the rendering PR, the same page
  rendered by `pdfcraft_render::PageRenderer` at 96 dpi and at 400%.
- `app-bar.png`, `app-progress.png`, `app-selected.png`: the real shell (egui_kittest, wgpu,
  headless at 1x) with the scanned-text PR.
