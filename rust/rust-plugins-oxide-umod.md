---
description: >-
  Mod your wasteland. 🛠️ To add plugins (like 2x Gather, Teleport, or Kits),
  you first need to install the Oxide (now called UMod) framework.
---

# 🔌 Rust Plugins (Oxide/UMod)

#### ⚡ Method 1: The "Startup" Switch (Easiest)

Most Witchly servers come with a built-in switch to turn on modding.

1. Go to your Witchly Panel.
2. Stop the server.
3. Go to the "Startup" tab.
4. Look for a variable named "Oxide", "Modding", or "Install Oxide".
5. Turn it on:
   * If it's a text box, type `1` or `true`.
   * If it's a switch, toggle it to On.
6. Reinstall/Update:
   * Go back to the Console.
   * In some versions, you might need to click the "Reinstall" button (don't worry, this won't delete your map, just the server files).
   * Start the server.

> 🔍 Check: Watch the Console. If you see lines saying `[Oxide] Loading plugins...`, it worked!

***

#### 📦 Method 2: Manual Install (If Method 1 fails)

If you don't see an Oxide switch, do this:

1. Download: Go to [umod.org/games/rust](https://umod.org/games/rust) and download `Oxide.Rust.zip`.
2. Upload:
   * Go to the Files tab.
   * Drag and drop the `.zip` file into the main folder.
3. Unzip:
   * Right-click the zip file and choose Unarchive (Unzip).
   * It will ask to "Overwrite" files. Click Yes.
4. Restart: Start the server.

***

#### 🧩 How to Add Plugins

Once Oxide is running, installing plugins is simple.

1. Download: Find a plugin on [UMod.org](https://umod.org/plugins) (e.g., "GatherManager").
2. Upload:
   * Go to Files > `oxide` > `plugins`.
   * Drag the `.cs` file here.
3. Done!
   * You do NOT need to restart.
   * Oxide detects the new file and loads it instantly. Check the Console to see it load.

***

#### 👑 Granting Permissions

Most plugins need "Permissions" to work.

* Example: To let players use `/kit`.

1. Go to the Console.
2. Type: `oxide.grant group default kit.use` (This gives it to everyone).
3. Type: `oxide.grant user Vamp kit.admin` (This gives it just to you).
