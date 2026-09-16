# docs

Pictures, GIFs and videos for the slides go here. No HTML edits needed.

Each media slot in `index.html` looks for a file by name. It tries these
extensions in order and shows the first one it finds:

`.gif` `.mp4` `.webm` `.png` `.jpg` `.jpeg` `.webp` `.svg`

If no file exists, the slot keeps its built-in diagram, sketch or placeholder.

| Slide | File name (any extension above) | Shown until you add one |
|---|---|---|
| SevenTask · opener | `docs/seventask-hero` | board sketch |
| SevenTask · system design | `docs/seventask-architecture` | Mermaid diagram |
| SevenTask · workflow engine | `docs/seventask-workflow` | Mermaid diagram |
| SevenTask · demo | `docs/seventask-demo` | empty placeholder |
| OptiServe · opener | `docs/optiserve-hero` | cost-curve sketch |
| OptiServe · system design | `docs/optiserve-architecture` | Mermaid diagram |
| OptiServe · demo | `docs/optiserve-demo` | empty placeholder |
| Guardian · opener | `docs/guardian-hero` | expert-grid sketch |
| Guardian · system design | `docs/guardian-architecture` | Mermaid diagram |
| Guardian · demo | `docs/guardian-demo` | empty placeholder |
| Realest · opener | `docs/realest-hero` | verified-card sketch |
| Realest · system design | `docs/realest-architecture` | Mermaid diagram |
| Realest · demo | `docs/realest-demo` | empty placeholder |
| BakeryPilot · opener | `docs/bakerypilot-hero` | action-card sketch |
| BakeryPilot · system design | `docs/bakerypilot-architecture` | Mermaid diagram |
| BakeryPilot · demo | `docs/bakerypilot-demo` | empty placeholder |

The five demo slots show an empty placeholder until you add a file.
Fill those before presenting.

## Tips

- Demo and diagram slots are about 760 × 550 px, a bit wider than 4:3.
  Opener slots are about 590 × 600 px. Files scale to fit, never cropped.
- For screen recordings, `.mp4` beats `.gif`: much smaller, same loop.
  Videos play muted and loop, like a GIF.
- Keep each file under about 10 MB so GitHub Pages loads it quickly.
- Paths are relative (`docs/...`). The site is served from `/projects/`,
  so a leading slash would break them.
