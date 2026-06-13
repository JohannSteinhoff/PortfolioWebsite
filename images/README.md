# Project thumbnail images

The work cards on the homepage use a **two-image hover**:
- the **black & white** image shows by default (currently loaded from Framer's CDN)
- the **red-accent** image fades in on hover — these are loaded from THIS folder.

## Drop your red-accent images here with these exact names:

| Project | File to add |
|---|---|
| Offensive Security Simulation | `offensive-security-simulation-color.png` |
| Predicting Texas Agricultural Production | `machine-learning-color.png` |
| Arithmetic Logic Unit | `arithmetic-logic-unit-color.png` |
| Object Oriented Chess | `object-oriented-chess-color.png` |

Notes:
- Any web format works — if you use `.jpg`/`.webp` instead of `.png`, update the
  matching `src="images/...-color.png"` in `index.html` (search for `class="color"`).
- Recommended: same dimensions/crop as the B&W version (roughly 16:10) so the
  crossfade lines up.
- Until a file is added, the card simply stays black & white on hover (the missing
  image is auto-removed, so there's no broken-image icon).

If you'd also like the **B&W base images served locally** (instead of from Framer's
CDN), drop those too and tell me — I'll repoint the `class="bw"` sources here.
