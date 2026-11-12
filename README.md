# LOOM Launcher

**A modern, customizable Minecraft Java Edition launcher for Windows.**

LOOM Launcher is an independent desktop application designed to make managing Minecraft installations and mods easier, with a clean, modern interface.

## Features

- Modern black-and-white user interface
- Create and manage separate Minecraft instances
- Support for Vanilla, Fabric, Forge, NeoForge and Quilt
- Browse and install compatible mods from Modrinth
- Manage instance-specific mods and game files
- Configurable Minecraft RAM allocation
- Microsoft account authentication integration

## Microsoft Authentication

LOOM Launcher uses Microsoft OAuth with PKCE to authenticate Minecraft Java Edition accounts.

The application requests Minecraft API access to:

- Authenticate legitimate Microsoft accounts
- Verify Minecraft Java Edition ownership
- Obtain the credentials needed to launch Minecraft

Authentication takes place through Microsoft's official login service. LOOM Launcher does not request or store Microsoft account passwords.

## Development Status

LOOM Launcher is currently in development. Some functionality is experimental, and Microsoft authentication requires Minecraft API approval.

## Disclaimer

LOOM Launcher is an independent, unofficial project. It is not affiliated with, endorsed by, or associated with Mojang Studios, Microsoft, or Modrinth.

Minecraft is a trademark of Mojang Studios.
