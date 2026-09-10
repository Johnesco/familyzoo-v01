# Family Zoo — v01 — A Single Room

The simplest possible Sharpee story: one room with a welcome sign and ticket booth. Introduces the Story class structure, entities, and the four essential traits needed to stand up a world.

Step 1 of the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial — a progressive walkthrough of the [Sharpee](https://sharpee.net) TypeScript interactive fiction engine, from a single room to a full multi-file story.

## What this step teaches

- Story interface with config, createPlayer, and initializeWorld
- IdentityTrait for names, descriptions, and aliases
- ActorTrait with isPlayer flag and ContainerTrait for inventory
- SceneryTrait and RoomTrait basics
- Explicit entity placement via world.moveEntity

## Playing

Open `play.html`, or preview the folder:

```bash
python -m http.server 8000 --directory familyzoo-v01
```

## Building

This is a **frozen 0.9.x TypeScript version**. The built player in this folder is the published artifact; it is re-laid from `browser/` by the workspace build:

```bash
python ../tools/build.py familyzoo-v01
python C:/code/ifhub/tools/ship.py familyzoo-v01
```

The authoring tree for every version lives in the [familyzoo](https://github.com/Johnesco/familyzoo) repo.
