---
description: >-
  Play the version you want. 🕹️ Whether you want the latest features or the
  classic PvP combat, switching versions is easy.
---

# 🔄 Changing Server Version: Minecraft

> ⚠️ Important: You cannot switch software types automatically (e.g., you cannot click a button to turn a "Paper" server into a "Forge" server). You are locked to the software you purchased. To change versions, follow the steps below.

#### ⛏️ Minecraft (Java & Bedrock)

How to Manually Update (The JAR Method) _Use this to update from 1.19 to 1.20, or downgrade to older versions._

Step 1: Download the Server File You need to grab the official "Server JAR" file for the version you want.

* Paper/Spigot: Download from [PaperMC.io](https://papermc.io/downloads).
* Vanilla: Download from [McVersions.net](https://mcversions.net).
* Purpur: Download from [PurpurMC.org](https://purpurmc.org).

Step 2: Remove the Old File

1. Go to your Witchly Panel > Files.
2. Find your current server file. It is usually named `server.jar`.
3. Right-click and Delete it.

Step 3: Upload the New File

1. Drag and drop your new downloaded `.jar` file into the file manager.
2. Rename it:
   * Right-click the new file > Rename.
   * Change the name to exactly: `server.jar`
   * _Why?_ The server is programmed to look for a file with this specific name. If it's named `paper-1.20.1.jar`, it won't start!

Step 4: Check Java Version (Critical!) ☕ Newer versions of Minecraft require newer Java. If you don't do this, the server will crash.

1. Go to the "Startup" tab.
2. Look for "Docker Image" or "Java Version".
3. Match the Java version to your Minecraft version:
   * Minecraft 1.18 - 1.21+: Select Java 17 or Java 21.
   * Minecraft 1.17: Select Java 16.
   * Minecraft 1.16 and older: Select Java 8 or Java 11.
4. Restart the server.
