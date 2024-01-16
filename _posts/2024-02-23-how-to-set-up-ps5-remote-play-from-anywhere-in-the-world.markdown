---
layout: post
title: "How to Set Up PS5 Remote Play From Anywhere in the World"
date:   2024-02-23 10:04:28 +0000
categories: ['News','Gaming']
excerpt_image: https://i.ytimg.com/vi/XH20Lm32vpI/maxresdefault.jpg
image: https://i.ytimg.com/vi/XH20Lm32vpI/maxresdefault.jpg
---

### Introduction
When away from home, **PS5 remote play** allows gamers to continue enjoying their PlayStation games from any mobile device or PC with an internet connection. However, connecting over a cellular data network can be limited by bandwidth constraints. This comprehensive guide will walk through setting up **PS5 remote play over the internet** to ensure the smoothest gaming experience possible when away from home.

![](https://www.lifewire.com/thmb/wy8W0aFhMlWj3N2wFwTO0M-aftc=/3840x2160/filters:no_upscale():max_bytes(150000):strip_icc()/001-how-to-use-ps5-remote-play-to-stream-to-ps4-5089217-1dd2d5fdcc05498ebf7596025a55a073.jpg)
### Hardware and Software Requirements
The following equipment is needed to stream PS5 games over the internet:
- A PS5 console connected to the home network via an Ethernet cable for optimal stability and throughput. WiFi can work but may introduce latency.
- A Windows or Mac PC with the cloud gaming software Parsec installed. Parsec acts as the virtual screen and controller to remotely access the PS5. 
- A minimum broadband download speed of 5Mbps is required, though 15Mbps or higher is strongly recommended to minimize latency during intense gameplay.
- A DualSense or DualShock 4 controller connected to the PC to control games remotely. Touchpad and motion controls may not work over Parsec.
- A home router that supports features like port forwarding and UPnP (Universal Plug and Play), or the ability to manually configure port forwarding. This allows connections to reach the PS5 over the public internet.
- A free dynamic DNS service account to keep the home network accessible even if the IP address changes periodically. Dynamic DNS maps a static URL to the home's current IP.
### Configuring PS5 Remote Play Settings  
To begin, remote play must first be enabled and tested locally on the PS5:
- Navigate to "Settings > Users and Accounts > Remote Play Connection Settings" and toggle on the "Allow Remote Play" option.
- Pair the DualSense controller to the PS5 via USB or Bluetooth.
- Test streaming a game to a local device on the home network like a smartphone or laptop to confirm remote play is functioning properly.
### Configuring the Home Network and Router
With the PS5 ready for remote connections, some router settings need adjusting:
- Reserve a static local IP address for the PS5 within the router's DHCP settings, or enable Universal Plug and Play (UPnP) which automatically forwards required ports.
- Look up the specific external port numbers needed by PS5 remote play- 987, 9295, 9296, 9304 - and forward them to the console's internal IP address. This allows inbound connections to reach the PS5.
### Installing and Configuring Parsec
After setting up the network, Parsec allows remotely connecting to the PS5:
- Create a free Parsec account at parsec.cloud and install the desktop client on the streaming PC.
- In Parsec, click the "+" button to add the PS5 internal IP address or dynamic DNS hostname as a "shared computer".  
- Connect to the home PS5 through Parsec. The PS5 screen will appear, then launch PS5 Remote Play from the menu.
### Setting Up Dynamic DNS Service  
For Internet access when the home IP changes:
- Choose a free dynamic DNS service like No-IP and create an account. Many services offer desktop client software to automatically update the home's external IP address binding.
- Download and install the DDNS client program provided. Follow prompts to enter the account credentials and host name.
- The client will periodically check for any IP changes and update the DNS server, keeping the home network accessible via the static hostname.
### Using PS5 Remote Play Remotely
Time to put it all together and remotely stream PS5 games from afar:
- Connect to the home network through the Parsec client using the dynamic DNS hostname, such as "gaming.no-ip.biz". 
- The PS5 screen will load via Parsec. Launch a game using the "Remote Play" option in the menu.
- Control games with the paired DualSense controller connected to the streaming PC. Enjoy streaming PS5 away from home!
### Tips for Best Performance
A few additional optimizations can enhance the remote play experience: 
- Where possible, hardwire networking equipment instead of using WiFi for more reliable throughput and lower latency.
- Invest in powerful PC hardware, especially a solid-state drive and modern processor, to minimize encoding and decoding strain on the system.
- Check bandwidth usage on the home network. Prioritize traffic or use bandwidth management tools to guarantee sufficient speeds for low-latency gameplay.
- Try switching between different connection security protocols in Parsec like UDP or TCP to find the most stable option for the available bandwidth.
- Enable network quality settings in Parsec like bandwidth throttling that can smooth out sharp throughput drops over congested or unstable connections.
### Alternatives to Parsec
If Parsec remote play does not offer the desired performance for a particular network setup or location, some alternatives include:
- Setting up a dedicated VPN server at home, either commercial or self-hosted, to create a more direct tunnel for lowered latency gaming. This fully bypasses the public internet routing.
- Streaming games to mobile or PC using cloud gaming services like PlayStation Remote Play, Rainway, or GeForce Now instead of direct connection. These platforms can offer specialized encoding optimized for remote gaming.
In summary, with some careful network configuration, a dynamic DNS service, and the Parsec virtualization software, it is now possible to enjoy the full PS5 gaming experience from anywhere there is an internet connection. With the right optimization, remote play quality can rival that of local wireless gameplay.