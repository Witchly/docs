---
description: >-
  Whether you're making a local backup or moving your builds to single-player
  mode, downloading your world from Witchly.host is simple. We provide your
  files in a compressed format so you can get back t
---

# 📥 Downloading Your World

> ⚠️ No Egg Switching: Remember that a world downloaded from a Java server can only be played in Minecraft: Java Edition. Bedrock worlds are strictly for Bedrock Edition.

***

### 🛰️ Step 1: Export from the Panel

To keep things fast and scannable, we recommend using the File Manager to grab your data.

1. Log in to your Witchly Panel and Stop your server.
2. Navigate to the File Manager tab.
3. Locate your world folder (usually named `world`).
4. Right-click the folder and select Compress.
5. Once the `.zip` file is created, right-click it and select Download.

> 💡 Pro Tip: Always use your regular browser for downloads. Third-party download managers can sometimes corrupt your world chunks!

***

### 🔄 Step 2: Preparing for Single-Player

Before you can load into your world locally, you must Unpack (unzip) the archive you just downloaded.

#### For Spigot or Paper Users 🛠️

If you are running a Spigot or Paper server, your Nether and End dimensions are stored in separate folders (`world_nether` and `world_the_end`). You must merge these back into the main world folder before playing in single-player.

***

### 💻 Step 3: Importing to Minecraft

Now, move your unpacked folder to the correct directory on your computer:

#### Minecraft: Java Edition ☕

* Path: Move the folder into your `saves` directory.
* Quick Find: Type `%appdata%\.minecraft\saves` into your Windows search bar.

#### Minecraft: Bedrock Edition 📱

* Path: Move the folder into the `minecraftWorlds` directory.
* Quick Find: This is usually located within the `com.mojang` folder in your local app data.

***

### 🩺 Troubleshooting

| **Issue**           | **Solution**                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------ |
| Missing Builds      | If you are on Java, ensure you merged the `region` folders correctly.                      |
| Corrupted Zip       | Re-download the file without using a download manager.                                     |
| World Not Appearing | Ensure the folder you moved contains the `level.dat` file directly, not another subfolder. |

***
