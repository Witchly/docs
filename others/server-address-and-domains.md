---
description: >-
  Connecting to your world. 🔌 Witchly automatically assigns a premium address
  to every server. You don't need to memorize a long string of numbers!
---

# 🌐 Server Address & Domains

#### 1. Your Default Address 🏷️

When you buy a server, check your Panel. Your address will look something like this:

> `germany-1.witchly.host:6969`

* germany-1.witchly.host: This is the "Node" (the computer hosting your server).
* 25565: This is your "Port" (your specific door number).

How to join: Simply copy that entire address and paste it into Minecraft, Rust, or Palworld.

***

#### 2. Using Your Own Domain (Advanced) 🌍

_Do you own a domain like `myserver.com`?_ You can make a custom address like `play.myserver.com` that points to your Witchly server.

The Easy Way (CNAME Record) This is the simplest method. You will still need to type the port number, but the name will be yours!

1. Log into your Domain Registrar (Namecheap, GoDaddy, Cloudflare).
2. Go to DNS Management.
3. Add a CNAME Record:
   * Name: `play` (or whatever you want the prefix to be).
   * Target: Your Witchly Node address (e.g., `germany-1.witchly.host`).
4. Save.

Result: Now your friends can join using: `play.myserver.com:25565` (or whatever your port is).
