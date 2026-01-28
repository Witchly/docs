---
description: >-
  Ready to move your existing masterpiece to a faster home? Whether you’re
  migrating from a local save or another host, bringing your world to
  Witchly.host is a breeze.
---

# 🌎 Uploading Your World (Java & Bedrock)

> ⚠️ No Egg Switching: Ensure you are uploading the correct world type for your server. Java Edition worlds only work on Java servers, and Bedrock worlds only work on Bedrock servers. To convert between them, use a tool like [Chunker](https://chunker.app/).

***

### 📦 Step 1: Prepare Your World

Before uploading, you need to make sure your files are packed and ready for the journey to our nodes (like `germany-1.witchly.host`).

#### Option A: The Folder Method 📂

Ensure your world folder is "healthy" by checking for these essential files:

* `level.dat` (The heart of your world)
* `region/` folder (Contains all your builds)

#### Option B: The .zip Method (Recommended) 🤐

Compressing your world into a `.zip` file is often faster and more reliable for browser uploads.

1. Right-click your world folder.
2. Select Compress to ZIP file.
3. Ensure all subfolders and files are included inside the archive.

***

### 📤 Step 2: Upload to the Witchly Panel

Now, let's get those files onto the Pterodactyl Panel.

1. Log in to your Witchly Panel and stop your server.
2. Navigate to the File Manager tab.
3. Delete the old world: Find the existing world folder (usually named `world`) and delete it to prevent file conflicts.
4. Click the Upload button.
5. Select your folder or .zip archive from your device.
6. Pro Tip: If you uploaded a `.zip`, right-click it in the File Manager and select Unarchive.

> ⏳ Note: Upload times depend on your internet speed and the size of your world. Grab a snack if you're moving a massive kingdom!

***

### 🚀 Step 3: Start the Server

1. Once the upload is finished and unarchived, go to the Console.
2. Press Start to load your custom world.
3. Join the game and verify your builds are exactly where you left them!

***

### 🩺 Troubleshooting

| **Issue**             | **Solution**                                                                             |
| --------------------- | ---------------------------------------------------------------------------------------- |
| "Invalid World" Error | You might be missing `level.dat` or trying to put a Bedrock world on a Java node.        |
| Folder Upload Fails   | Some browsers struggle with bare folders. Use the .zip method instead.                   |
| World Resetting       | Ensure the "World Name" in your Startup tab matches the name of the folder you uploaded. |

> 💡 Pro Tip: If your world is larger than 1GB, we recommend using SFTP (like FileZilla) for a more stable upload experience. Check our "SFTP Guide" for steps!

***

