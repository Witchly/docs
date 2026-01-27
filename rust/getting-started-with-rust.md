---
description: >-
  Welcome to the wasteland. 🛢️ Rust servers are powerful, but they work a bit
  differently than Minecraft. Here is how to join and take control.
---

# ☢️ Getting Started with Rust

#### ⏳ First: The "Boot Time" Warning

Please read this! Rust servers are huge. When you click "Start" for the first time, it can take 10 to 15 minutes to generate the map and start.

* Don't Panic.
* Check the Console. If lines are moving, it's working.
* Wait until you see: `Server startup complete`.

***

#### 🎮 How to Join Your Server

You can't always find a new server in the "Community" list immediately. The fastest way to join is using the F1 Console.

1. Open Rust on your PC.
2. Press the F1 key on your keyboard.
3. Type this command: `client.connect <Your-IP>:<Port>`
   * _Example:_ `client.connect 192.168.1.1:28015`
4. Press Enter. You will fly right in!

***

#### 👑 How to Become Owner (Admin)

You need "Owner" status to spawn items, fly, or ban cheaters.

Step 1: Get your Steam64 ID

* Go to a site like [steamid.io](https://steamid.io).
* Search for your Steam Username.
* Copy the number that looks like: `76561198012345678`.

Step 2: Run the Command

1. Go to your Witchly Panel > Console.
2. Type this command: `ownerid <Your-SteamID> "YourName"`
   * _Example:_ `ownerid 76561198012345678 "Vamp"`
3. Press Enter.

Step 3: Save (CRITICAL STEP!) ⚠️

* You MUST type this command next, or you will lose admin status when the server restarts: `writecfg`
* Press Enter.

Step 4: Re-Login

* If you are already in the game, you must disconnect and rejoin for the admin powers to work.

***

#### 🕹️ Verifying Admin Status

Once you rejoin:

1. Press F1.
2. Go to the "Items" tab.
3. If you can spawn an AK-47, congratulations! You are the Owner.
