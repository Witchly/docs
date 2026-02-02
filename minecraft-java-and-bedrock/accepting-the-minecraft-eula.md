---
description: >-
  The 'Contract' that starts the fun. 📜 If your Minecraft server is stuck on
  "Offline" or crashes immediately after you click Start, it’s usually because
  you haven’t accepted Mojang’s End User License
---

# ✅ Accepting the Minecraft EULA

#### 🔍 How to check if you need this

Check your Console. If you see a message like this, you must follow the steps below:

> `[INFO]: You need to agree to the EULA in order to run the server. Go to eula.txt for more info.`

***

#### 🛠️ How to Accept (The Manual Way)

1. Go to your Witchly Panel > Files.
2. Look for a file named `eula.txt`.
   * _Note: If you don't see this file, try clicking Start on your console once. It will fail, but it will generate the file for you!_
3. Click the file to open the editor.
4. Find the line: `eula=false`
5. Change it to: `eula=true`
6. Click Save Content.
7. Go back to the Console and click Start.

***

#### ⚠️ Still not starting?

If you have set `eula=true` and the server still won't start, it’s usually a Java Version mismatch.

* Minecraft 1.18 - 1.21+: Needs Java 17 or 21.
* Minecraft 1.16 - 1.17: Needs Java 16.
* Old Versions (1.8 - 1.15): Needs Java 8 or 11.

> Fix: Go to the Startup tab and change the Docker Image / Java Version to match your game version!
