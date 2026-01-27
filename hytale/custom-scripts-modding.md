---
description: >-
  Code your own features. 👨‍💻 Hytale is built to be modded. Unlike Minecraft,
  you don't always need a complex "Plugin API." You can write JavaScript or
  TypeScript files and drop them right into the se
---

# 🧪 Custom Scripts (Modding)

#### 📂 Where do scripts go?

1. Go to your Witchly Panel.
2. Click on "Files".
3. Look for the folder named `scripts` (or sometimes `mods/scripts`).
4. Open it. This is where your code lives.

***

#### 📝 How to add a Script

Let's say you downloaded a script that gives players a "Welcome Gift" when they join.

1. Upload the File: Drag and drop the `.js` or `.ts` file into the `scripts` folder.
2. Check Dependencies: Some scripts need a `package.json` file (just like Node.js). If the script came with one, make sure to upload that too!
3. Restart: Go to the Console and Restart the server to load the new code.

***

#### ⚡ Hot Reloading (for Developers)

Are you writing your own code? You don't always need to restart the whole server!

If you make a small change to a script file:

1. Save the file in the Panel.
2. Go to the Console.
3. Type: `/reload` (or `/reload scripts`).
4. Hytale will try to refresh the code instantly without kicking players.

> ⚠️ Warning: Big changes (like adding new blocks or items) usually require a full Restart.

***

#### 🛑 Troubleshooting Scripts

If the server crashes or the script doesn't work:

1. Check the Console: It will usually tell you exactly which line of code failed (e.g., `Error in welcome.js at line 10`).
2. Check the Extension: Make sure your file ends in `.js` (JavaScript) or `.ts` (TypeScript).
3. Check Permissions: Does your script try to use Admin commands? Make sure the server allows it.

***

#### 🏁 Hytale Category: COMPLETE! 🏆

You now have a fully fleshed-out Hytale section:

1. Getting Started (The Token & Setup)
2. Commands (Admin & Permissions)
3. Configuration (Settings & Password)
4. Scripting (Mods & Custom Code)
