---
description: >-
  Make it yours. 🛠️ Want to change the server description, add a password, or
  increase the player limit? You can do all of this in the server.json file.
---

# ⚙️ Hytale Server Configuration

#### 📂 How to access settings

1. Go to your Witchly Panel.
2. Click on "Files" in the sidebar.
3. Find the file named `server.json` (or sometimes `config.json`).
4. Click on it to open the text editor.

> ⚠️ Syntax Warning: Hytale settings are written in JSON.
>
> * Be careful not to delete any commas `,` or quotes `"`.
> * If the file turns red or shows an error, you probably deleted a comma!

***

#### 📝 Common Settings Cheat Sheet

Here are the most important lines you can change.

| **Setting Name**           | **What it does**                         | **Example**                                      |
| -------------------------- | ---------------------------------------- | ------------------------------------------------ |
| `"max_players"`            | Limits how many people can join at once. | `20`                                             |
| `"server_name"`            | The name shown in the server browser.    | `"Witchly Official SMP"`                         |
| `"motd"`                   | The description text under the name.     | `"Welcome to Orbis!"`                            |
| `"password"`               | Private Server. Set a password to join.  | `"secret123"` (Leave empty `""` for no password) |
| `"view_distance"`          | How far players can see (Chunks).        | `12` (Higher = More Lag)                         |
| `"vertical_view_distance"` | How high/deep players can see.           | `5`                                              |

***

#### 🔒 Setting a Server Password

Want to keep your server private for just you and your friends?

1. Find the line that says `"password": ""`.
2. Type your password inside the quotes.
   * _Before:_ `"password": ""`
   * _After:_ `"password": "MySuperSecretPassword"`
3. Save and Restart.
4. Now, players will be asked to type this code when they connect.

***

#### 💾 How to Apply Changes

Just like Minecraft, you must restart for these changes to take effect.

1. Click the blue "Save Content" button.
2. Go to the Console.
3. Click Restart.
