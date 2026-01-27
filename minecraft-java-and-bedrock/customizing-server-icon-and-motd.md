---
description: >-
  Stand out in the list. ✨ A custom icon and a colorful description (MOTD) are
  the first things players see. Here is how to add them.
---

# 🎨 Customizing Server Icon & MOTD

#### 🖼️ Part 1: The Server Icon

You cannot just upload any random picture. Minecraft is very strict about the format!

The Requirements (Important!)

* Size: Must be exactly 64x64 pixels.
* Format: Must be a .PNG file.
* Name: Must be named exactly `server-icon.png`.

How to Install:

1. Resize your logo to 64x64 using a tool like [imageresizer.com](https://imageresizer.com) or Photoshop.
2. Rename the file to `server-icon.png`.
3. Go to your Witchly Panel > Files.
4. Upload the file to the main folder (where `server.jar` is).
5. Restart the server.

> ⚠️ Don't see it? If the icon doesn't update immediately in your Minecraft client:
>
> 1. Delete the server from your list.
> 2. Re-add it. (This clears the cache).

***

#### 📝 Part 2: The MOTD (Message of the Day)

This is the text description under your server name. You can use colors and bold text!

Step 1: Create your Text Writing color codes manually (like `\u00A75aHello`) is hard. We recommend using a generator.

1. Go to a Minecraft MOTD Generator website (search on Google).
2. Type your text and pick your colors.
3. Copy the code it generates (it usually looks like `\u00A75Witchly \u00A76SMP`).

Step 2: Apply it

1. Go to Witchly Panel > Files.
2. Open `server.properties`.
3. Find the line: `motd=A Minecraft Server`
4. Delete the old text and paste your generated code.
   * _Example:_ `motd=\u00A75Witchly \u00A76SMP`
5. Save Content.
6. Restart the server.
