# Family Zoo — v01: A Single Room

The smallest Chord story that runs: a header that names the work, one room, and two pieces of scenery you can examine. Everything else in the tutorial is added to this.

Step 1 of sixteen in the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial for [Chord](https://sharpee.net/chord/), the authoring language of the [Sharpee](https://sharpee.net) interactive fiction engine.

## What this step adds

- The `story` header — `title`, `authors`, `id`, `description`
- `create the <Room>` with `a room` and an indented description
- `scenery` for things that belong to the room and cannot be taken
- `in the <Room>` to place a thing
- `before the game starts` naming who the player is

## The source

The whole step is one file: [`familyzoo-v01.story`](./familyzoo-v01.story) — the step before it plus the ideas above. Where it sits in the trail is on the [group page](https://johnesco.github.io/familyzoo/#familyzoo-v01).

## Playing and testing

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v01.tests/
python ../tools/build.py familyzoo-v01 --force
```

## Engine

Pinned in `package.json`, held across the whole `@sharpee/*` scope by an `overrides` block.

The 0.9.x TypeScript edition this replaced is kept in [`legacy/`](./legacy).
