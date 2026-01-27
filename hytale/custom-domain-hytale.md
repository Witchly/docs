---
description: >-
  Your gateway to Orbis. 🗡️ Hytale servers use an IP and Port to connect. You
  can replace the numeric IP with a custom domain to make it look professional.
---

# 🌐 Custom Domain: Hytale

#### 1. Get your Node IP

1. Go to the Witchly Panel.
2.  Copy your numeric IP (e.g., `142.76.102.44`).

    <a class="button secondary"></a>

    * _Do not include the port number._

#### 2. Create an A Record

1. Log into your Domain Host (Namecheap, Cloudflare, etc.).
2. Go to DNS Management.
3. Add a new Record:
   * Type: `A`
   * Name: `hytale` (or `play`).
   * IPv4 Address: Paste the IP (`142.76.102.44`).
   * Proxy Status: OFF (DNS Only).
4. Click Save.

#### 3. How to Connect

1. Open the Hytale Launcher.
2. Click Servers > Direct Connect.
3. Enter your new domain + the port: `play.yourdomain.com:25565` _(Make sure to use YOUR specific server port!)_
4. Click Connect.

> 💡 Note: Hytale is still in Beta. Currently, you must include the port number at the end of the address.
