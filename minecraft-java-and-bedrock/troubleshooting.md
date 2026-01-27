---
description: >-
  Uh oh, something broke? 🚑 Don't worry! 99% of server problems can be fixed in
  seconds. Here are the most common issues and how to solve them.
---

# 🛠️ Troubleshooting

#### 🛑 Problem 1: "My Server Won't Start!"

You clicked "Start," but it crashes immediately or stays offline.

Solution: The EULA Agreement Mojang requires you to agree to their rules before the server runs.

1. Go to your Witchly Panel > Files.
2. Find the file named `eula.txt`.
3. Click to edit it.
4. Change `eula=false` to `eula=true`.
5. Save and Start the server again.

Solution: Wrong Java Version

* Minecraft 1.18 - 1.21+: Needs Java 17 or Java 21.
* Minecraft 1.8 - 1.12: Needs Java 8.
* How to fix: Go to the Startup tab in your panel and change the "Docker Image" or Java Version.

***

#### 🚫 Problem 2: "I Can't Join!"

You try to connect, but it kicks you out.

Error: "Connection Refused"

* Cause: Your server is offline or restarting.
* Fix: Check your Panel. Is the status light GREEN? If it is Grey or Red, the server is off.

Error: "Failed to Verify Username" / "Authentication Servers Down"

* Cause: You (or your friends) are using a cracked launcher (TLauncher, etc.).
* Fix: You need to enable "Cracked Mode."
  * _Go to our \[Basic Settings] page to see how to switch `online-mode` to false._

Error: "Outdated Server" or "Outdated Client"

* Cause: Version mismatch. (e.g., Server is on 1.20, but you are playing 1.21).
* Fix: Update your game to match the server version.

***

#### 🐌 Problem 3: "It's Lagging!"

Is the server running in slow motion? Blocks breaking 2 seconds later?

1\. Check your TPS (Ticks Per Second)

* Go to the Console and type: `/tps`
* 20.0 = Perfect. No lag. 🟢
* 15.0 - 19.0 = Okay. Little stutter. 🟡
* Below 10.0 = Bad Lag. 🔴

2\. Common Fixes

* Too many entities: Did you spawn 5,000 cows? Kill them using `/kill @e[type=!player]`.
* Need more RAM: If your RAM usage bar is full (100%), the server will freeze. You might need to upgrade your plan at the \[Billing Area].

***

#### 💥 Problem 4: "It Crashed!"

The server stopped by itself.

1. Go to Files > Crash-Reports folder.
2. Open the newest file.
3. Read the top 5 lines. It usually tells you exactly which Mod or Plugin caused the error!
