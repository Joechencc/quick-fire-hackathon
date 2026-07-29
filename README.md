# Quick Fire 🔥

A fast-paced perception game for May Days Hackathon — race May's AV at spotting
objects in a driving scene.

## ▶ Play

**https://joechencc.github.io/quick-fire-hackathon/**

(If the link 404s, GitHub Pages hasn't finished deploying yet — give it a
minute after enabling Pages in repo Settings, or after the latest push.)

## How it works

A cartoon driving scene flashes on screen for a few seconds, then hides.
Tap every object type you spotted (pedestrians, cyclists, cones, buses,
police cars, traffic lights, dogs, trucks, ducks) from the buttons at the
bottom, hit **Done**, then see how you stack up against May's AV — which
never blinks. Each level shortens the flash time and adds more objects.
3 lives, combo streaks, and a final "REAL TIME" level.

## Run it locally

No build step, no dependencies — it's a single self-contained HTML file.

```
git clone https://github.com/Joechencc/quick-fire-hackathon.git
cd quick-fire-hackathon
python3 -m http.server 8000
# open http://localhost:8000
```

Or just double-click `index.html` to open it directly in a browser.
