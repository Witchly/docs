---
description: >-
  Your World, Your Rules. 🌍 Want to level up faster? Hatch eggs instantly? Or
  maybe just stop losing your stuff when you die? You can change all of this in
  the PalWorldSettings.ini file.
---

# ⚙️ Customizing Palworld Rules

#### 📂 Step 1: Finding the Secret File

This file is hidden deep in the server folders. Follow this path exactly:

1. Go to your Witchly Panel > Files.
2.  Click the folders in this order:

    Pal ➡️ Saved ➡️ Config ➡️ LinuxServer
3. Inside `LinuxServer`, find the file named: `PalWorldSettings.ini`
4. Click to edit it.

> ⚠️ Is the file empty?
>
> If you open the file and it is completely blank, do not panic!
>
> This is normal for a new server. You need to copy-paste the "Default Settings" code into it first.
>
> *   \[Click here to get the Default Settings Code] (Link to a Pastebin or your own snippet)
>
>     (If it already has text, just skip to Step 2).

***

#### 📝 Step 2: The Cheat Sheet

The file looks like a big wall of text. Don't let it scare you! You just need to find the specific word and change the number next to it.

Here are the most popular settings:

| **Setting Name**            | **What it does**                         | **Recommended Change**                              |
| --------------------------- | ---------------------------------------- | --------------------------------------------------- |
| `ExpRate`                   | How fast you level up.                   | `1.0` (Normal) ➡️ `5.0` (Fast!)                     |
| `PalCaptureRate`            | How easy it is to catch Pals.            | `1.0` (Normal) ➡️ `2.0` (Easier)                    |
| `PalEggDefaultHatchingTime` | Egg Hatch Time. (Hours).                 | `72.0` (Slow) ➡️ `1.0` (Fast)                       |
| `DeathPenalty`              | Keep Inventory. What drops when you die. | `All` (Drop Everything) ➡️ `None` (Keep Everything) |
| `GuildPlayerMaxNum`         | Max players in one Guild.                | `20`                                                |

***

#### 🐣 Example: How to make "Instant Hatching"

Everyone hates waiting 72 hours for a huge egg. Let's fix it.

1. Press Ctrl+F (Search) inside the file editor.
2. Search for: `PalEggDefaultHatchingTime`
3. Change the number to 0 or 1.
   * `PalEggDefaultHatchingTime=1.000000`
4. Save Content.

***

#### 🛡️ Example: How to Keep Inventory (No Drop)

Tired of losing your loot?

1. Search for: `DeathPenalty`
2. Change it to None.
   * `DeathPenalty=None`
3. Save Content.

***

#### 💾 Step 3: Apply the Changes

1. Click the blue "Save Content" button.
2. Go to the Console.
3. Restart the server.

> 🚨 Important Syntax Rule:
>
> Ensure there are NO spaces around the = sign.
>
> * ✅ Correct: `ExpRate=5.0`
> * ❌ Wrong: `ExpRate = 5.0` (This will break the server!)
