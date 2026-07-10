# FallCube

**A sovereign fractal demonstration. Every tool holds the tree. Every leaf is a root.**

Three flavors of the same idea: the AI-Native Solutions estate isn't 45+ separate tools — it's one recursive pattern that composes into itself at every scale.

- Live: **https://sjgant80-hub.github.io/fall-cube/**
- Machine summary: **[llms.txt](llms.txt)**

## The three flavors

### A · Cube
Six faces of a rotating 3D CSS cube. Each face is a live iframe of a real fall\* tool on GitHub Pages. Click any face to zoom fullscreen. From inside a zoomed tool, click "Wrap this tool in a new cube" and it re-embeds itself as the front face of a fresh cube. Cube in cube in cube.

### B · Matryoshka
A nested doll made of base64 data URIs. The outer HTML embeds a mini-app rendered from a `data:` URI. That mini-app embeds another `data:` URI. That one embeds a third. Save this HTML file to disk, unplug the internet — the entire nested doll still works, because every level travels inline with its parent.

### C · Reflex
FallCube is a fall\* tool. Any fall\* tool can host any other. So FallCube can host FallCube. Click "Nest me inside me" and a live iframe of this same page appears below. Each nested instance keeps its own state, its own IndexedDB, its own identity. Depth counter shows you where you are.

## Why this exists

Because "sovereign single-file tool" sounds theoretical until you see 45 of them composing into one another at multiple scales. This isn't a product — it's a demonstration that the pattern actually holds.

## Architecture

- One HTML file · vanilla JS · no build step · MIT
- 3D CSS transforms for the cube
- base64 data URIs for the matryoshka
- Reflexive iframe embedding for the reflex mode
- Autopilot kit wired in

## License

MIT · Copyright 2026 AI-Native Solutions · https://ai-nativesolutions.com
