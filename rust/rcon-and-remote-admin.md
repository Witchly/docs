---
description: >-
  Control your server like a Pro. 🕶️ The web console is great, but sometimes
  you want a dedicated tool to see player stats, chat logs, and ban cheaters
  easily. We recommend using RustAdmin.
---

# 📡 RCON & Remote Admin

#### 1. Download RustAdmin

* Free Version: Download "RustAdmin" (the legacy free version is fine) from [rustadmin.com](https://www.rustadmin.com).

#### 2. Find Your RCON Details

To connect, you need three secret keys from your Witchly Panel.

1. Go to the "Settings" or "Startup" tab.
2. Look for:
   * IP Address: (e.g., `192.168.1.1`)
   * RCON Port: (This is usually your Server Port + 1, e.g., `28016`. Check your Network tab to be sure!)
   * RCON Password: (Click the "Eye" icon to reveal it).

#### 3. Connect the Tool

1. Open RustAdmin.
2. Go to the Configuration tab.
3. Fill in the boxes:
   * Server IP: Your Server IP.
   * Port: Your RCON Port (Not the Game Port!).
   * Password: Your RCON Password.
   * Type: Select "WebRcon" (Important! Standard Rcon often fails).
4. Click Save and Connect.
5. If the light turns Green, you are connected!

***

#### 🚀 Performance Tips (The "Lag" Fix)

Rust servers eat RAM for breakfast. If your server feels slow, follow these rules:

1\. The Daily Restart Rust servers get "memory leaks" over time.

* Rule: Restart your server at least once every 24 hours.
* How: Go to "Schedules" in your Panel and create an auto-restart task (e.g., at 4:00 AM).

2\. World Size Limit Don't make your map too big!

* 3000 - 3500: Best for performance (FPS).
* 4000+: Good for exploration, but might lag on smaller plans.
* Change this: In the Startup tab > "World Size".

3\. Entity Count Too many buildings = Lag.

* If you have 200,000+ entities, it's time to Wipe!
