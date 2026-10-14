# Light Gayi

**When the power goes out, the whole building lights up.**

Interactive blackout-night experience for apartment blocks. Concept & prototype by Chandra Pavansai for DJXHack Everyday Magic 2026.

## Live demo

Open `index.html` in any modern browser (or use GitHub Pages / Vercel).

- Point your mouse (or phone torch via camera) to reveal neighbours
- Hold to throw a shadow bird
- Clap (or press Space) when everyone is found
- The paths of every torch stay as tonight’s constellation poster

## What works right now

- Full event creation, RSVP, join codes, results & impact dashboard
- Live wall engine (torch reveal, 12 neighbour vignettes, shadow-bird, constellation)
- Camera bright-blob torch tracking
- Microphone clap detection
- Host setup guide, safety checklist, lumen calculator

Data stays in the browser (localStorage). No server required for the core loop.

## Deploy

```bash
# Vercel
npx vercel --prod

# or GitHub Pages: Settings → Pages → Deploy from main / root
```

## Credits

Concept, direction & build: Chandra Pavansai  
AI assistance: Claude (Anthropic) for research, writing and code  
All illustrations and sounds are original and generated in code.
