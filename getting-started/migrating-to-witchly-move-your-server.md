---
description: >-
  Moving house? Let's bring your furniture. 🚚 Switching to Witchly from another
  host is easy. You can keep your world, your inventory, and your buildings.
---

# 📦 Migrating to Witchly (Move Your Server)

#### 1. At Your OLD Host 🏚️

First, we need to pack up your files.

1. Stop your old server.
2. Delete Junk: Remove old backups or massive logs (files ending in `.log` or `.gz`) to make the download smaller.
3. Zip the Files:
   * Select all your files in their file manager.
   * Click "Archive" or "Zip".
   * Name it `backup.zip`.
4. Download: Download that single `backup.zip` file to your computer.

#### 2. At Witchly (Your NEW Host) 🏰

Now, let's unpack.

1. Stop your new Witchly server.
2. Connect via SFTP: (See our [SFTP Guide](../others/using-sftp-file-manager.md) for help connecting).
3. Upload: Drag your `backup.zip` into the Witchly folder.
4. Unzip:
   * Go to the Witchly Panel > Files.
   * Right-click `backup.zip`.
   * Click Unarchive (Unzip).
5. Restart: Go to the Console and click Start.

> ⚠️ Important: Make sure your Witchly server is set to the same game version as your old one (e.g., if you came from Paper 1.20.1, make sure Witchly is running Paper 1.20.1).
