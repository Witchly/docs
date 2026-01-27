---
description: >-
  Want to change the rules? You can customize almost everything about your
  server (like difficulty, player limits, and game modes) using one special file
  called server.properties.
---

# ⚙️ Basic Server Settings

#### 📂 How to find the settings

1. Go to your Witchly Panel.
2. Click on "Files" in the sidebar.
3. Scroll down and find the file named `server.properties`.
4. Click on it to open the editor.

***

#### 🔓 Enabling "Cracked" Mode (Free Players)

By default, only players who bought the official Minecraft can join. If your friends use TLauncher or other free launchers, you need to change this setting.

1.  In the server.properties file, look for line 22 (usually):

    online-mode=true
2.  Change it to false:

    online-mode=false
3. Click Save Content.
4. Restart your server.

> ⚠️ Warning: If you change this, player skins might disappear. This is normal!

***

#### 📝 Common Settings Cheat Sheet

Here are the most useful settings you might want to change.

| **Setting Name** | **What it does**                             | **Options**                                  |
| ---------------- | -------------------------------------------- | -------------------------------------------- |
| `difficulty`     | How hard the game is.                        | `peaceful`, `easy`, `normal`, `hard`         |
| `pvp`            | Can players hurt each other?                 | `true` (Yes), `false` (No)                   |
| `max-players`    | How many people can join at once.            | Type any number (e.g., `20`)                 |
| `allow-flight`   | Allows flying in Survival mode (Anti-cheat). | `true` (Allow), `false` (Kick them)          |
| `level-seed`     | Want a specific world seed? Paste it here.   | Leave blank for random.                      |
| `motd`           | The message shown in the server list.        | Type your text (e.g., "Welcome to Witchly!") |

***

#### 💾 How to Apply Changes

This is very important!

Your changes will not work immediately.

1. Click the blue "Save Content" button at the bottom right.
2. Go back to the Console.
3. Click Restart.
