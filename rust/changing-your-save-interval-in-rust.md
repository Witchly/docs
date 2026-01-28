---
description: >-
  Surviving the "Wasteland" of Rust is hard enough without losing progress to a
  sudden crash. By default, your server saves every 10 minutes (600 seconds). If
  you want to ensure every scrap of loot is a
---

# 💾 Changing Your Save Interval in Rust

> ⚠️ The Double-Edged Sword: While saving more often prevents data loss, it also locks in mistakes. If a player dies and the server autosaves immediately after, you won't be able to roll back to a point where they still had their gear.

***

### 🛠️ How to Change the Save Interval

You can take control of your save frequency by editing the `server.cfg` file in your Witchly Panel.

1. Log in to your Witchly Panel and Stop your server.
2. Navigate to the Files tab and find your configuration directory.
   * Path: `server/my_server_identity/cfg/`
3. Locate the `server.cfg` file. If it doesn't exist, click New File and name it `server.cfg`.
4. Add the following line to the file:
   * `server.saveinterval #` (Replace `#` with your desired time in seconds).
   * _Example:_ For a 5-minute save, use `server.saveinterval 300`.
5. Save Content and Start your server from the Console.

***

### 🔄 Reverting to Default

If you decide the default 10-minute interval was perfect all along, reverting is easy.

1. Stop your server.
2. Open `server.cfg` and delete the `server.saveinterval` line.
3. Save and Restart.

***

### 🩺 Quick Reference: Save Times

| **Frequency**        | **Seconds to Enter** |
| -------------------- | -------------------- |
| 5 Minutes            | `300`                |
| 10 Minutes (Default) | `600`                |
| 20 Minutes           | `1200`               |

***
