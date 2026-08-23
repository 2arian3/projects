# docs

Put icons, diagram exports and any other images for the slides in here.

To use one in a slide, replace the Mermaid block with an image:

```html
<img src="docs/optiserve-arch.svg" alt="OptiServe architecture">
```

Use a relative path (`docs/...`), never a leading slash — the site is served
from `/projects/`, so `/docs/...` would break.

Each diagram in `index.html` has an id in its header bar that matches the
filename to use:

| Slide | Diagram id | Suggested filename |
|---|---|---|
| OptiServe · architecture | `fig-01 · optiserve-arch` | `docs/optiserve-arch.svg` |
| Guardian · architecture | `fig-02 · guardian-arch` | `docs/guardian-arch.svg` |
| BakeryPilot · architecture | `fig-03 · bakerypilot-arch` | `docs/bakerypilot-arch.svg` |
| Applied to EvenUp | `fig-04 · evenup-extraction` | `docs/evenup-extraction.svg` |
