---
layout: post
title:  "The hunt for a DP MST hub with VRR support"
---

# The Problem

I have a laptop with USB-C. The laptop plugs into a USB-C docking station,
which provides the laptop with two extra DisplayPorts and one HDMI port. By
using DP 1.4 in HBR3 mode and DSC (Display Stream Compression), it can easily
drive a 3440x1440 144Hz monitor.

I can plug everything I need into the dock, and using a single cable (or KVM
switch) plug into my laptop, or desktop, or or Steam Deck, or even phone, with
a single cable.

My laptop and desktop have AMD GPUs, which means they support FreeSync. The
monitor also supports FreeSync. Great! It means I can get smooth framerates in
games, video and general desktop usage. It's especially useful when gaming on
my desktop and I would never want to go back to not having variable refresh
rate in some form.

But there's a problem. When I plug my gaming monitor to my dock, VRR doesn't
work. Both Linux and Windows no longer see the monitor as supporting VRR. What
gives?

Thus begins my slow descent into madness of DisplayPort MST, DSC, DPCD, closed
datasheets, HDMI Forum being a big doo doo head and Linux GPU driver hacking.
