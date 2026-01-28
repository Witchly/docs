# ⚔️ Getting Started with Minecraft (Java & Bedrock)



Welcome to the world of blocks! 🌍 Witchly makes it incredibly easy to host your own Minecraft world, whether you are playing on PC (Java) or Console/Mobile (Bedrock). Our servers come pre-configured so you can jump straight into the action.

> ⚠️ No Egg Switching: At Witchly, we optimize our hardware for specific games. If you want to change your server type (e.g., from Java to Bedrock), please contact support. To change versions (e.g., 1.20 to 1.21), you can simply replace the `server.jar` in your File Manager.

***

### 🚀 First Launch & Console Setup 🔑

Before you can build your first diamond pickaxe, you need to get your server online.

1. Log in to your Witchly Panel.
2. Select your Minecraft server from the dashboard.
3. Click the Start button in the Console tab.
4. Accept the EULA: Keep an eye on the console logs. You will see a prompt asking you to accept the Minecraft EULA.
5. Go to the Files tab, find `eula.txt`, and change `eula=false` to `eula=true`.
6. Hit Restart and wait for the green "Online" status.

***

### 🎮 Joining the Server 🕹️

Witchly supports Cross-Play! Here is how to join based on your version:

#### For Java Edition (PC)

1. Open the Minecraft Launcher and start your desired version.
2. Go to Multiplayer > Add Server.
3. Enter your Server IP (e.g., `germany-1.witchly.host:25565`) found on your panel.
4. Click Done and double-click the server to join.

#### For Bedrock Edition (Console/Mobile)

1. Open Minecraft and go to the Servers tab.
2. Scroll down to Additional Servers and click Add Server.
3. Enter a Name (e.g., "My Witchly Server").
4. Enter the Server IP and the Port (Bedrock usually uses `19132`).
5. Click Play!

***

### 👑 Claiming Admin (OP) Status 👑

Want to change the game mode or teleport your friends? You need to become an Operator (OP).

1. Go to your Witchly Panel and open the Console.
2. In the command line at the bottom, type:
   * `/op YourUsername`
3. Press Enter.
4. Success: The console should say `[Server: Made YourUsername a server operator]`. You can now use cheats in-game!

***

### ⚙️ Server Settings (World Configuration) 🛠️

Want to change your difficulty or the world seed?

1. Go to the Files tab in your Panel.
2. Locate and click on the `server.properties` file.
3. Find the following common settings to edit:

| **Setting** | **What it does**                      | **Example Value** |
| ----------- | ------------------------------------- | ----------------- |
| difficulty  | Sets how hard the game is             | `hard`            |
| gamemode    | Sets default player mode              | `survival`        |
| level-seed  | Sets a specific world generation seed | `8675309`         |
| pvp         | Enables or disables player fighting   | `false`           |

4. Click Save Content and Restart your server to apply the changes.

***

### 🐛 Troubleshooting 🩺

Can't connect? Don't rage-quit just yet.

* "Connection Refused": Make sure the server status is green and says Online.
* "Invalid Session": Restart your Minecraft Launcher; this is usually a Mojang authentication error.
* Whitelist Issues: If you have the whitelist turned on, make sure to add yourself via the console using `/whitelist add YourUsername`.

> 💡 Pro Tip: If your server is lagging, check the Resources tab. If your RAM usage is hitting 100%, consider upgrading your plan or removing heavy plugins!

***

Would you like me to generate a "Commands Cheat Sheet" for your Minecraft admins next?
