# Home Lab - Tailscale Mesh VPN

## Overview
This project documents the steup of a self-hosted mesh VPN using Tailscale to securely connect personal devices across iOS, macOS, and Windows. The goal was twofold: enable encrypted device-to-device communication for file sharing during a transition betwen laptops, and protect outbound traffic on public Wi-Fi networks by tunnleing through a designated exit node at home. During testing, I identified a limitation in this architecture, outbound traffic still exits through my home address which informed the next phase of the project: a migration to self-hosted WireGuard for full control over the VPN stack.

## Architecture
A simple diagram or description of what connects to what.

## Setup
Step-by-step what I did. Not a Tailscale tutorial, my spcific implementation.

## Configuration
Devices connected, exit node designation, any ACLs.

## What I Learned
Bullet points of concepts I now understand: mesh VPN, WireGuard protocol, exit node routing, etc.

## Limitationes Identified
The home IP exposure issue (specifically what I've discovered).

## Next Steps
Migrating to self-hosted WireGuard for deeper control.
