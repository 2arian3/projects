# docs

Pictures, GIFs and videos for the slides go here. No HTML edits needed.

Each media slot in `index.html` looks for a file by name. It tries these
extensions in order and shows the first one it finds:

`.gif` `.mp4` `.png` `.jpg` `.webp` `.svg`

Each file can sit directly in `docs/`, or in `docs/demo/` or `docs/images/`.
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

All five demo recordings live in `docs/demo/`. Keep demos there and
stills (logo, diagrams, hero shots) in `docs/images/`.

## Tips

- Demo slots are 16:9 (about 760 × 430 px), so record at 16:9.
  Realest's demo slot is a phone frame that takes the recording's own shape.
- Diagram slots are about 760 × 550 px. Opener slots are about 590 × 600 px.
  Files scale to fit, never cropped.
- Demo videos play when their slide opens, restart on each visit, and pause
  when you move on. Each has a playback bar to pause, scrub or go fullscreen.
- For screen recordings, `.mp4` beats `.gif`: much smaller, same loop.
  Videos play muted and loop, like a GIF.
- Keep each file under about 10 MB so GitHub Pages loads it quickly.
- Paths are relative (`docs/...`). The site is served from `/projects/`,
  so a leading slash would break them.
- `images/seventask.png` is the SevenTask logo, shown beside that project's title.
  It is referenced directly, so keep the name.
