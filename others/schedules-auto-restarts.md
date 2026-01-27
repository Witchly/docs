---
description: >-
  Put your server on autopilot. 🤖 You can tell your server to automatically
  restart, send commands, or backup at specific times.
---

# ⏰ Schedules (Auto-Restarts)

#### ⚡ Example: Setting up a Daily Restart

Restarting your server every day clears the RAM and reduces lag.

Step 1: Create the Schedule

1. Go to the "Schedules" tab.
2. Click Create Schedule.
3. Name: `Daily Restart`.
4. Time Settings (Cron):
   * Minute: `0`
   * Hour: `4` (This means 4:00 AM).
   * Day of Month: `*` (Every day).
   * Month: `*` (Every month).
   * Day of Week: `*` (Every week).
5. Click Create Schedule.

Step 2: Add the Task A schedule does nothing without a "Task."

1. Click on the schedule you just made (`Daily Restart`).
2. Click New Task.
3. Action: Select "Send Power Action".
4. Payload: Select "Restart".
5. Click Create Task.

Done! Your server will now restart every day at 4:00 AM automatically.
