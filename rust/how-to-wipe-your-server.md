---
description: >-
  It's time for a fresh start. 🧼 In Rust, "Wiping" means resetting the world.
  Most servers do this weekly or monthly to reduce lag and give everyone a fair
  start.
---

# 🧹 How to Wipe Your Server

There are two types of wipes. It is important to know the difference!

#### 1. The "Map Wipe" (Most Common) 🗺️

What it does: Deletes all buildings and the map. Players keep their researched blueprints (recipes). When to do it: Usually every week (Thursday).

How to do it (The Easy Way): The fastest way to get a new map is simply to change the "Seed" (the map's ID number).

1. Stop your server.
2. Go to the "Startup" tab.
3. Find the box labeled "Level Seed" (or just Seed).
4. Change the number.
   * _Current:_ `12345`
   * _New:_ `67890` (Just type any random number!)
5. Start the server.
   * Because the seed is new, the server will ignore the old save file and generate a brand new world.

***

#### 2. The "Full Wipe" (Blueprints + Map) 💥

What it does: Deletes EVERYTHING. Buildings are gone, and players forget all recipes (Blueprints). They start naked on the beach. When to do it: Usually once a month (on the first Thursday).

How to do it: You need to manually delete the "brain" files of the server.

1. Stop your server.
2. Go to "Files".
3. Open the folder: `server` > `my_server_identity` (or whatever your "Server Identity" is named).
4. Delete these files:
   * Looking for files ending in `.db` or `.sav`.
   * To wipe Blueprints: Delete `player.blueprints.x.db`.
   * To wipe Player Data (Inventory/Position): Delete `player.identities.x.db` and `player.tokens.db`.
5. Start the server.
   * The server will see the files are missing and create fresh, empty ones.

***

#### 🗓️ The "Forced Wipe"

Warning: On the first Thursday of every month (around 2 PM EST), Facepunch (the developers) forces an update that wipes ALL servers globally.

* You cannot stop this.
* When this happens, you just need to run the Steam Update button (or "Reinstall") to get the server working again.

***

#### ❓ FAQ

"Can I keep the same map but delete buildings?" Yes, but it's harder.

1. Go to `server` > `my_server_identity` > `save`.
2. Delete the `.sav` files inside.
3. Do NOT change the Seed in the Startup tab.
4. Restart. You will have the same terrain, but no buildings.
