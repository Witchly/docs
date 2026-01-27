---
description: >-
  Control your Orbis. 🧙‍♂️ As a Superuser, you have access to powerful tools to
  manage players, build faster, and control the world.
---

# 📜 Admin Commands

#### ⚡ The Basics

You can run these commands in the Witchly Console (without the `/`) or in-game (with the `/`).

| **Command** | **Description**                         | **Example** |
| ----------- | --------------------------------------- | ----------- |
| `/help`     | Shows all available commands.           | `/help`     |
| `/stop`     | Safely saves and shuts down the server. | `/stop`     |
| `/save`     | Forces the world to save immediately.   | `/save`     |

***

#### 👮‍♂️ Player Management

Keep your server safe from griefers.

| **Command**                 | **What it does**                                       |
| --------------------------- | ------------------------------------------------------ |
| `/kick [player] [reason]`   | Disconnects a player.                                  |
| `/ban [player] [reason]`    | permanently blocks a player.                           |
| `/unban [player]`           | Removes a ban.                                         |
| `/tp [player] [target]`     | Teleports one player to another.                       |
| `/gamemode [mode] [player]` | Switch between `adventure`, `survival`, or `creative`. |

> 💡 Note: Hytale's "Adventure Mode" is the default story mode experience. "Survival" is the standard sandbox mode.

***

#### 🛡️ The Rank System (Permissions)

Unlike Minecraft, Hytale has a group system built-in! You don't need a plugin to create ranks.

1\. Create a Group

* Command: `/group create [group_name]`
* _Example:_ `/group create Moderators`

2\. Add Permissions to Group

* Command: `/group addperm [group_name] [permission]`
* _Example:_ `/group addperm Moderators kick`
* _Example:_ `/group addperm Moderators ban`

3\. Add Player to Group

* Command: `/group adduser [player] [group_name]`
* _Example:_ `/group adduser Vamp_ Moderators`

***

#### 🌍 World & Environment

Control the elements of Orbis.

* Set Time: `/time set [value]` (e.g., `day`, `noon`, `midnight`).
* Weather: `/weather [type]` (e.g., `clear`, `rain`, `storm`).
* Game Rules: `/gamerule [rule] [true/false]`
  * _Example:_ `/gamerule pvp false` (Disables fighting).
