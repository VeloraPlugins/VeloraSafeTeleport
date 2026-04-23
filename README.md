# VeloraSafeTeleport

VeloraSafeTeleport is a Paper plugin that prevents unsafe teleports and fixes common teleport-related glitch exploits.

It is designed to stop players from abusing teleport mechanics such as ender pearls and chorus fruit to clip into blocks, escape playable areas, or land in invalid destinations.

## Features

- Ender pearl safety checks
- Chorus fruit safety checks
- Unsafe destination blocking
- Space validation for teleport destinations
- World border support
- Custom bounds support
- Configurable teleport cause listening
- Last safe location fallback
- Lightweight and configurable setup

## Current Protection

VeloraSafeTeleport currently focuses on:
- ender pearl glitch prevention
- chorus fruit teleport validation
- blocking teleports into solid or illegal blocks
- blocking unsafe teleport destinations with insufficient space
- optional fallback to the player's last safe location

## Planned Features

Future updates may include:
- command teleport validation
- plugin teleport validation
- portal teleport protection
- broader teleport exploit protection
- extra safety options per teleport cause

## Installation

1. Install **Paper** on your server
2. Install **VeloraEngine**
3. Place `VeloraSafeTeleport` in your server `plugins` folder
4. Restart your server

## Dependency

VeloraSafeTeleport requires **VeloraEngine**.

Download VeloraEngine here:  
[https://modrinth.com/plugin/veloraengine](https://modrinth.com/plugin/veloraengine)

## Configuration

The plugin includes configurable settings for:
- bypass permission handling
- ender pearl checks
- chorus fruit checks
- teleport causes to listen to
- world border and bounds validation
- fallback behaviour

## Issues & Support

This repository is mainly used for:
- bug reports
- issue tracking
- feedback
- feature suggestions

If you find a bug or want to suggest an improvement, open an issue in this repository.

## Notes

- VeloraSafeTeleport is currently in beta
- More teleport protection features will be added over time
- Recommended for servers that want extra protection against teleport clipping exploits
