---
description: >-
  Make your server professional. 🎩 Instead of germany-1.witchly.host:25565, you
  can use your own domain like play.myserver.com.
---

# 🌐 Custom Domain: Minecraft

#### 🛑 Prerequisites

* You must own a domain (e.g., from Namecheap, GoDaddy, or Cloudflare).
* You need access to your DNS Records.

***

#### ☕ Method 1: The "Simple" Way (Java & Bedrock)

_Best for: Servers that support both Java and Bedrock (Geyser)._ This method creates a simple address. Players will still need to add the Port number if it's not default (25565).

Step 1: Get your Node IP

1. Go to your Witchly Panel.
2. Look at your IP Address.
   * _Example:_ `142.76.102.44:25566`
3. Copy ONLY the numbers before the colon (The IP).
   * _Copy:_ `142.76.102.44`

Step 2: Add an A Record

1. Log into your Domain Host (e.g., Cloudflare).
2. Go to DNS.
3. Click Add Record.
   * Type: `A`
   * Name: `play` (This makes `play.yourdomain.com`).
   * IPv4 Address: Paste your Node IP (e.g., `142.76.102.44`).
   * Proxy Status: OFF (DNS Only). _Very important for Cloudflare users!_
4. Click Save.

Step 3: How to Join

* Java: `play.yourdomain.com:25566`
* Bedrock:
  * IP: `play.yourdomain.com`
  * Port: `25566` (or `19132` if using Geyser default).

***

#### 💎 Method 2: The "Pro" Way (Java Only)

_Best for: Java Servers wanting to hide the port._ You can use an SRV Record so players don't have to type the numbers at the end.

Step 1: Create the A Record (Same as above)

* Follow Method 1 first. You need that A Record (e.g., `play.yourdomain.com`) to exist.

Step 2: Create the SRV Record

1. Click Add Record.
2. Type: `SRV`
3. Name: `_minecraft` (some hosts ask for `_minecraft._tcp.play`).
4. Service: `_minecraft`
5. Protocol: `_tcp`
6. TTL: Auto (or 3600).
7. Priority: `0`
8. Weight: `5`
9. Port: Your Witchly Port (e.g., `25566`).
10. Target: `play.yourdomain.com` (The A Record you made in Step 1).
11. Click Save.

Step 3: How to Join

* Java: `play.yourdomain.com` (No port needed! 🎉)
* Bedrock: _SRV records do not work on Bedrock. Use Method 1._
