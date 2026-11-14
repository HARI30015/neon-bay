# Neon Bay — Realistic Beachfront City Game

A browser-playable 3D open-world city game. No download or install
required to play — open the game link and press START PLAYING. Login is
optional: sign up / log in with email + password on the start screen to
save your cash, respect, completed jobs and profile forever to your
own Firebase account (Firestore); signed-out play is unchanged.

## Play it

- Render (public link): https://neon-bay.onrender.com
- GitHub Pages: https://hari30015.github.io/neon-bay/

## Install it

On the game's start screen, use the INSTALL GAME button. If your browser
does not offer a one-tap install, use its menu instead:

- Android Chrome: menu → Install app
- iPhone / iPad Safari: Share → Add to Home Screen
- Desktop Chrome / Edge: address-bar install icon

Once installed, the game opens fullscreen from your home screen / app list.

## What is in this repo

- `index.html` — the whole game in one file (about 3.9 MB). It contains the
  city, buildings, interiors, landmarks, the supercar, the bike, people, jobs,
  camera views and install support. That is why there are no separate source
  folders: the game was built as a single-file web game.
- `.nojekyll` — intentionally empty. It is a marker file that tells GitHub
  Pages to serve these files as-is, without Jekyll processing.
- `README.md` — this file.

## How to play

Start screen shows only the title, a CONTROLS card and START PLAYING.

- WASD move · Shift run · Space jump
- Mouse — move to look around (no click, no drag, no pointer lock)
- E enter / exit the supercar or the bike · in the supercar: WASD drive, Space handbrake
- E at a glowing building door — go inside · inside, E at the EXIT door — back out
- C or V change camera angle — on foot: Follow · Front · Top · Side · Person's view; in the supercar: Front · Mirror · Door · Top (default Front)
- M map · P profile · B backpack · top-right gear opens Settings
- On a phone, use the on-screen buttons.

## What is in the game

- A realistic beachfront city: modern apartment blocks, a tall white tower,
  a twisting blue-glass spire and a Parliament-style landmark.
- All 35 buildings are enterable, with furnished interiors.
- World Landmarks Park, north of the city: Eiffel Tower, Big Ben, Statue of
  Liberty, Sydney Opera House, Leaning Tower of Pisa, Colosseum, London Eye.
- Two bright silver metallic 3D supercars you can drive: one parked beside the
  hero's start point (nose towards the beach), one on the forecourt of the
  hero's home. Both have a hexagonal grille, a fixed carbon rear wing, slim
  white LED headlights, silver wheels, and a detailed interior with a live
  digital dashboard. No "63" badge.
- Traffic is back: 10 bright silver supercars drive the city roads in both
  directions. No police cars.
- A blue bike, rideable on the beachfront.
- The hero's own separate home, east of the city, marked HOME in gold on the
  map: a modern two-storey white house with a cantilevered warm-lit glass
  upper box, dark grey tower, huge glass doors and red outdoor sofas, with the
  silver supercar parked outside it — press E to drive it.
- Map and profile are separate: a cyan MAP button opens only the total city
  map, an amber PROFILE button opens only the profile panel (with FULL PROFILE
  and BACKPACK). Settings (top-right gear): Sound, Camera, Graphics and City
  Time speed.
- Three jobs, cash and respect, wanted stars, day-night cycle.
- High-end graphics: a real sun disc with glow and haze in the sky,
  sharper textures throughout (MAXANISO), 2048px shadows, bump-mapped
  512px paving, asphalt, sand and ocean (with animated ripples), and
  fuller palm fronds.
- Ultra graphics mode (Settings → Graphics → Ultra): HDR glow on
  lamps, neon, car LEDs and windows at night, sky reflections on
  glass, sea and paint, and a film look. Falls back to High by
  itself if the device can't do it.
- Unity graphics port: GLSL shader water with moving waves, sun
  glitter, shoreline foam and clear-to-deep colour, real glass on
  buildings, the spire and the supercar, a procedural sky with sun
  and moon, lit windows and warm lamp lights at night, and PBR
  materials throughout.
- Email + password login (Firebase, project neon-bay-b8572): an
  account card on the start screen with Sign Up, Log In and Log
  Out. When signed in, cash, respect, completed jobs and profile
  auto-save to Firestore users/{uid} and load back on the next
  sign-in. Login is never forced; the game still plays without it.
- Performance pass — less lag: resolution is capped, Balanced is
  the new default graphics level (1024 shadows, medium water),
  Smooth is cheapest and High is the old full look, and if the
  frame rate stays low the game lowers the resolution and then
  steps one graphics level down by itself, with a small message.
- Unity zip 2 look: detailed tall towers with recessed dark-blue
  glass, floor slabs, mullions, railed balconies, parapets and roof
  plant; leafy forked-trunk street trees; a smooth lofted silver
  supercar body with carved wheel arches, glass canopy and
  twin-spoke wheels; and more detailed pedestrians.
