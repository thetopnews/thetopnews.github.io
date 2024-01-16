---
layout: post
title: "Finding Your Terraria Server Address"
date:   2024-04-14 13:28:29 +0000
categories: ['News','Gaming']
excerpt_image: https://steamuserimages-a.akamaihd.net/ugc/579002701497921630/7280C24C958D64776A8511AC5DA916017F7241C7/
image: https://steamuserimages-a.akamaihd.net/ugc/579002701497921630/7280C24C958D64776A8511AC5DA916017F7241C7/
---

Have you ever wondered how to get friends connected to your home Terraria server?  Finding the right **IP address** or **server address** can sometimes be a challenge. However, with a few simple steps you'll be hosting games in no time.
Your **server IP** acts like a unique home address that allows other players on the internet to find your world. But since routers commonly assign private addresses internally, you need to properly configure port forwarding to make your server publicly visible. Let's look at some of the easiest methods for getting this done.
#### Checking Your Home Router 
The simplest place to start is by logging into your home router's administrative page. Almost all routers display a list of connected devices along with their dynamically assigned **local IP addresses**. Once you've identified your server computer, make a note of this **internal IP**.
Typically routers hide your network behind a firewall for security, assigning requests to your public IP across configured port numbers. So while helpful internally, this address alone won't allow outside connections. You'll need to perform some additional router configuration.

![](https://www.ionos.com/digitalguide/fileadmin/DigitalGuide/Screenshots_2022/terraria-enter-server-address.png)
#### Configuring Port Forwarding
Most games utilize standardized ports for hosting servers. Terraria defaults to TCP and UDP port 7777. Within your router's port forwarding or port triggering section, setup a new rule to redirect inbound traffic on port 7777 to your server's local IP. Enable this new forwarding rule and your server should now be visible externally!
To double check, you can visit websites like whatismyip.com which display your **Internet-facing IP address**. This public address is what friends will use when connecting to your server through the standard Terraria multiplayer interface. Combined with the forwarded port, all connections should route properly to your server.
#### Testing From Inside and Out 
Always take some time to thoroughly test your configuration from both inside and outside your local network. Attempt to connect to your public IP from another device on your WiFi to ensure proper internal routing. Then try joining remotely from a phone or another network to verify external accessibility.   
Some firewall or router models also let you check active port forwarding rules and confirm traffic is being allowed and redirected as intended. With a little patience during setup and testing, you'll be sharing adventures in Terraria in no time!