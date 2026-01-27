---
description: >-
  Welcome to Orbis! 🌍 Witchly is proud to be one of the first hosts in the
  world to support the Hytale Open Beta (released Jan 13th).
---

# 🗡️ Getting Started with Hytale

> ⚠️ Beta Warning: Hytale is in Beta. You might find bugs. If the server crashes, check the Troubleshooting section below!

#### 1. First Launch & The "Admin Token" 🔑

This is the most important step. When you start your Hytale server for the very first time, it generates a secret "Admin Token" (or Setup Code) in the logs. You need this to prove you are the owner.

1. Go to your Witchly Panel.
2. Start the server and wait for it to say "Online".
3.  Don't close the Console! Scroll up and look for a message that looks like this:

    > `[Auth] Admin Token Generated: XXXXX-XXXXX-XXXXX` _or_ `[System] Use /claim <token> to gain superuser privileges.`
4. Copy this code. You will need it in 1 minute.

#### 2. Joining the Server 🎮

1. Open the Hytale Launcher.
2. Go to Servers > Direct Connect.
3. Enter your Server IP (from the Witchly Panel).
4. Click Connect.

#### 3. Claiming Ownership 👑

Once you join the world, you will be a "Guest" (no permissions). To become the Owner:

1. Press `T` or `/` to open the chat.
2. Paste the command you found in the Console:
   * `/claim XXXXX-XXXXX-XXXXX`
   * _(Note: If the log gave a different command like `/auth` or `/setup`, use that instead!)_
3. Press Enter.
4. Success! The game should say: _"You are now a Superuser"_ or _"Admin permissions granted."_

***

#### ⚙️ Server Settings (World Name)

Want to start a fresh save file?

1. Go to the "Startup" tab in your Panel.
2. Find "World Name".
3. Change it (e.g., from `world` to `MySmp`).
4. Restart the server to generate the new world.

***

#### 🐛 Troubleshooting

Can't find the Token? If you missed the token in the logs:

1. Stop the server.
2. Go to Files > logs.
3. Open the file named `latest.log`.
4. Search (Ctrl+F) for "Token" or "Claim".

"Invalid Token" Error? The token might expire after a few minutes. If it doesn't work:

1. Go to the Console.
2. Type `admin generate-token` (or `token create` depending on the version).
3. Use the new code it gives you.
