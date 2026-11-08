# S305 Routing Widget

Interactive teaching widget for **BUS-S 305: Technology Infrastructure** (Kelley School of Business, IU).

Built from Lecture 5 — Network & Transport Layers, slides 41–47 (routing, routing tables) and slides 55–60 (TCP/IP team exercise).

## Modes

1. **Explore** — clickable topology of the 10.10.x network from the slides (5 subnets, routers on the 10.10.250.x backbone, Internet gateway). Students send packets and watch each router match a routing-table row. Includes DNS and ARP side-steps mirroring the Q1–Q4 team exercise.
2. **Table Challenge** — three levels: build Router 51's full table (slide 45), simplify it (slides 46–47), and build Router 52's table (slide 44).

## Embed in Canvas

1. Enable GitHub Pages: Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `/ (root)`.
2. In Canvas, edit a page → Insert → Embed, and use:

```html
<iframe src="https://clarkmd1.github.io/s305-routing-widget/" width="100%" height="1400" title="S305 Routing Explorer" style="border:0"></iframe>
```

## Files

- `index.html` — the entire widget (no external dependencies).
