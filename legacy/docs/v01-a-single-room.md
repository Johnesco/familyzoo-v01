# v01 — A Single Room

The smallest Chord story that runs: a header that names the work, one room, and two pieces of scenery you can examine. Everything else in the tutorial is added to this.

## What this step adds

- The `story` header — `title`, `authors`, `id`, `description`
- `create the <Room>` with `a room` and an indented description
- `scenery` for things that belong to the room and cannot be taken
- `in the <Room>` to place a thing
- `before the game starts` naming who the player is

## The source

The whole step is one file: [`familyzoo-v01.story`](../familyzoo-v01.story). Read it top to bottom — it is the previous step plus what is listed above.

## Running it

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v01.tests.json
```

Chord language reference: <https://sharpee.net/chord/>
