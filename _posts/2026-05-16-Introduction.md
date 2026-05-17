---
title: Introduction to my HomeLab adventures
date: 2026-05-16 00:00:00 +0100
categories: [HomeLab, General]
tags: [linux, introduction]     # TAG names should always be lowercase
media_subpath: /media/01
---


# Welcome to my HomeLab Adventures

Hi everyone!

My name is Ander and I am a fourth year Computer Engineering student. Ever since I discovered that I could just leave a PC at home with Ubuntu Server installed and control it from campus via SSH I haven't stopped tinkering with it.


## My current hardware

My current setup is fairly humble:
- **Optiplex 5060 SFF**: Old desktop PC that I bought from an online flea market (Wallapop) for about a hundred euros back in 2023. Specs:
  - Intel i5-8500: 6 core CPU that fares fairly well on not very intensive tasks. Plus it comes with an iGPU that behaves fairly well on transcoding tasks.
  - 64gb DDR4: Enough RAM to mess with lots of VMs since I prefer them to LXC. Bought it before the AI craze so it wasn't as expensive as it might seem.
  - Nvidia Tesla P4: Small gpu that I mainly intend to use for transcoding. Bought it because it was dirt cheap and possesed vGPU capabilities. Haven't even set up the license server so that's pending.
- **AooStar WTR Pro**: This is my newest purchase. I needed a 4 bay NAS that would have a small footprint since it would need to sit behind the TV in the living room. I wasn't looking for performance but this little machine actually outperforms my main server! Specs:
  - 4x IronWolf 4tb: I have these set as RAIDZ1 so I have 12tb of storage available.
  - AMD Ryzen 7 5825U: 8 cores that I haven't really put to use since more intensive workloads.
  - 32gb LPDDR4: This memory was bought in the midst of the AI craze so it actually cost me as much as the 64 for the other server did back in 2023. 

My dad's pretty sensible to noise so I ended up moving both servers to his office. I have to take the car to perform physical changes to the cluster but at least I don't have to worry about the servers being a bit noisy (trust me, the noise threshold for my living room is ridiculous).

![Servers at the Office](servers.jpg)
_My two nodes, alongside the router and another coworker's nas_

## What's next

My homelab currently supplies all my media selfhosting needs but it is a bit of a mess in terms of maintainability and security. So, I've decided to create this blog to document my journey where I'll tackle all those issues and hopefully learn stuff useful for my career. Some of the areas that need to be worked on are:
- Networking
- Backups
- Infrastructure as Code
- Monitoring

So, this is it. I'll try and post my findings and experiments as soon as I can. Thank you for reading and welcome aboard this boat!

