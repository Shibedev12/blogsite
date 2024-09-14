---
title: Converting a Surface RT into a Linux Machine!
published: 2024-09-13
description: Turn that bit of e-waste that papa Microsoft made into something slightly more useful!
image: ./laptop.jpg
tags: [Linux, SurfaceAdventures]
category: Surface-Adventures
draft: false
---

# The Surface RT, Where Did It Go Wrong?

You _may_ have heard of the Surface RT.  
A super lightweight laptop-tablet hybrid.  
It seemed to be great. Only issue were the multiple issues.

There were many critically acclaiming issues on this device ranging from:

- There being no apps other than ones that run off the (now shutdown) Windows Store.  
- ARM32, so even if you downloaded apps, they would never run.  
- 2GB of RAM, which at its MSRP of $599 was quite overpriced. $599 for something that can barely run its own OS.  
- The small trackpad, which causes cramps.

Even then, that's not even a full list, but these are the notable ones.  
Let's fix this thing.  
But what can run on abysmal hardware, look good, be customizable, and lightweight enough to run great on the Tegra 3?

Let's compare the options.

## WINDOWS 8/8.1 RT

**Pros**  
- Native, just run and go.  
- Clean UI.  
- Simple to use, and intuitive.

**Cons**  
- Can't run much since the one place that supported it, the Windows Store, has shut down.  
- Lags out, can barely manage more than 3 windows open.  
- It’s just Windows, but with no support anywhere, and it's basically a paperweight maker.

**Overall rating**: 2/10. Built-in apps are okay.

---

## OLD ANDROID BUILDS

**Pros**  
- Somewhat familiar interface for those who’ve used Android phones.  
- Light on resources—can run reasonably well on older hardware.  
- Play Store access (if you use compatible builds) gives you way more app options than Windows RT.

**Cons**  
- Android was never designed for desktop-like usage, so it can feel awkward on a tablet-laptop hybrid.  
- Touchscreen support might be hit-or-miss on older Android versions.  
- Potential hardware incompatibility with the Surface RT, especially with the ARM32 architecture.  
- Customization is often limited in older builds.

**Overall rating**: 3/10 for surface usage, with slightly better app support but not optimized for this form factor.

---

## A NEW HOPE: LINUX!

Now we get to the exciting part. **Linux** can breathe new life into Surface RT by replacing its outdated OS with something that's both powerful and lightweight.

The best choice for this project? **Raspbian 32-bit**.

Why Raspbian?  
- **ARM32 Support**: Raspbian is built for ARM devices, so it’s perfect for the Surface RT's Tegra 3.  
- **Lightweight**: Designed for devices with limited resources, like the Raspberry Pi, it can handle 2GB of RAM with ease.  
- **Customizable**: It’s Linux, which means you can tweak it as much as you like to optimize performance.  
- **Active Community**: Tons of Raspberry Pi users means there’s a lot of online support and tutorials.

**Overall rating**: 9/10 It's the obvious choice, but 9 as camera is not working as of now. 

---

(Expecting the guide here? yeah uh, I'm tired. check back tomorrow for the guide :3)
