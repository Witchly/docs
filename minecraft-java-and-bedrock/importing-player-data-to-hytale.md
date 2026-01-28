---
description: >-
  Don't leave your legendary loot behind! If you’ve been grinding in
  single-player and want to bring your character, inventory, and progress to
  your Witchly.host server, you can import your player data
---

# 👤 Importing Player Data to Hytale

> ⚠️ Universe Match: Player data is tied to the specific universe it was created in. Make sure you are uploading the data to the correct universe folder on your server to avoid losing your progress.

***

### 🔍 Step 1: Locating Your Single-player Data

First, you need to find where Hytale hides your character's soul on your local machine.

1. Launch Hytale and click on Worlds.
2. Right-click any world belonging to the universe you want to migrate.
3. Select Open Folder to reveal the universe directory.
4. Navigate to the following path: `universe/players/`.
5. Keep this window open; these are the files that store your inventory and stats.

***

### 📤 Step 2: Uploading to the Witchly Panel

Now, let's move that data to your high-performance node (like `germany-1.witchly.host`).

1. Log in to your Witchly Panel and Stop the server for the best results.
2. Go to the Files tab.
3. Navigate to the directory: `universe/players/`.
4. Drag and drop your player data files from your computer into this folder.
5. Restart your server from the Console and log in to see your character.

***

### 🩺 Troubleshooting

| **Issue**                | **Solution**                                                                                                                       |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| Empty Inventory          | You likely uploaded the data to the wrong universe folder. Double-check the folder names!                                          |
| Data Not Saving          | Always ensure the server is Stopped before uploading to prevent the panel from overwriting your files.                             |
| Missing "players" Folder | If the folder doesn't exist on the server yet, start the server once to generate the directory structure, then stop it and upload. |

***
