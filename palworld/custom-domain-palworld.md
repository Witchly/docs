---
description: >-
  Easy joining for your Guild. 🐼 Palworld requires an IP and Port to join.
  Using a domain makes it easier to remember.
---

# 🌐 Custom Domain: Palworld

#### 1. Get your Node IP

1. Go to the Witchly Panel.
2. Copy your numeric IP (e.g., `142.76.102.44`).
   * _Do not include the port (8211)._

#### 2. Create an A Record

1. Log into your Domain Host (Namecheap, Cloudflare, etc.).
2. Go to DNS.
3. Add a new Record:
   * Type: `A`
   * Name: `pal` (or `play`).
   * IPv4 Address: Paste the IP (`142.76.102.44`).
   * Proxy Status: OFF (DNS Only).
4. Click Save.

#### 3. How to Connect

1. Open Palworld.
2. Click Join Multiplayer Game.
3. At the bottom, replace the text with your new domain: `play.yourdomain.com:8211` _(Make sure to change 8211 to your specific server port!)_
4. Click Connect.

> ⚠️ Note: Palworld does not currently support SRV records (Hidden Ports). You must type the port number at the end of the domain.
