# jxn

Six concept sites built for Jackson Myles from his own work, plus a hub page that walks through the thinking behind each one (palette, layout, assets, the one bold move).

Static site. No build step. `index.html` is the hub; the six concept pages are siblings and load as live previews inside it.

## Deploy (Vercel)
Import this repo as a new Vercel project. No framework, no build command, output directory is the repo root. It serves `index.html` at `/`.

## The share card
`og.jpg` (1200x630) is the social preview. The OG tags in `index.html` point at `https://jxn.vercel.app/`. If the Vercel URL is different, update the domain in the three `og:`/`twitter:` image and url tags near the top of `index.html`.

## Pages
- `the-room.html` — the room (the door behind the feed)
- `movement-into-music.html` — the live class
- `movement-director.html` — the fashion / movement-director cut
- `myles-from-home.html` — the faith zine, direct to fan
- `in-motion.html` — the white gallery, artist statement
- `the-drop.html` — the membership club
