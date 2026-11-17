# Vasta Residences

Demo website for luxury real-estate projects. Scrolling moves the camera from a 3D cutaway floor plan, down a corridor and through an opening door into the living room.

- Single `index.html`, no build step
- 3D scene built with [three.js](https://threejs.org) r128, loaded from cdnjs
- "Vasta Residences" and all unit details are placeholders

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Swap in photoreal frames

For client work, replace the live 3D scene with a pre-rendered image sequence (150–200 JPEG frames) drawn on a canvas and scrubbed by scroll position. The copy, scroll timing and layout stay the same.

---

# Fernhill Custom Homes (`/builder`)

Demo website for custom home builders. Scrolling builds a house in 11 stages over a 34-week timeline: blueprint, staked lot, foundation, framing, sheathing, house wrap, brick, siding and roof, exterior details, landscaping, and finished home.

- `builder/index.html`, single file, no build step, three.js r128
- "Make it yours" section recolours siding, roof and front door live
- The enquiry form validates on the page but has no backend. Connect it to Formspree, a WhatsApp link or the client's CRM before going live.
- Fernhill, its phone number and all figures are placeholders
