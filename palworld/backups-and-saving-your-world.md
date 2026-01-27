---
description: >-
  Rule #1 of Palworld: Always Backup. ⚠️ Palworld is an "Early Access" game.
  This means it has bugs that can sometimes delete your progress. We highly
  recommend making a backup.
---

# 💾 Backups & Saving Your World

#### 🔄 Method 1: The "1-Click" Backup (Recommended)

Witchly makes this super easy. You don't need to download files manually.

1. Go to your Witchly Panel.
2. Click on the "Backups" tab in the sidebar.
3. Click the blue "Create Backup" button.
4. Name it: Give it a name like "Before Boss Fight" or "Weekly Save".
5. Wait: It will take a few seconds to zip your files.
   * When it says "Successful", your world is safe!

How to Restore (Undo): If something breaks, just go to the Backups tab, find your save, click the three dots (...), and choose Restore. Your server will travel back in time to that moment. ⏳

***

#### 📂 Method 2: Manual Download (For your PC)

Want to keep a copy of your world on your own computer?

1. Go to Files.
2. Navigate to this _exact_ folder: `Pal` ➡️ `Saved` ➡️ `SaveGames` ➡️ `0`
3. You will see a folder with a weird name (like `A1B2C3D4...`). This is your World Folder.
4. Right-click that folder and choose Archive (Zip).
5. Download the zip file to your PC.

***

#### 🚑 Troubleshooting: "My World Reset!"

Did you log in and find yourself at Level 1 creation screen? This is a known Palworld bug where the server forgets which "Save Slot" to use.

1. Stop the server.
2. Go to Files > `Pal/Saved/Config/LinuxServer/GameUserSettings.ini`.
3. Look for `DedicatedServerName`.
4. Make sure it matches the folder name you saw in Method 2 (the weird code like `A1B2C3D4...`).
5. If it's empty, paste that folder name in.
6. Restart.
