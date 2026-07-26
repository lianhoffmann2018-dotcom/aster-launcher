# Aster Launcher

Aster Launcher is an independent Windows desktop launcher for Minecraft:
Java Edition, currently in closed alpha.

## Authentication

Aster uses the Microsoft system-browser login with OAuth 2.0 Authorization
Code and PKCE. It never asks users to enter their Microsoft password inside
the launcher.

The launcher uses Minecraft Java Edition game service APIs only to:

- authenticate the Microsoft and Xbox account
- verify Minecraft Java Edition ownership
- retrieve the Minecraft username and UUID
- retrieve and locally cache the active player skin

Refresh tokens are stored through Windows Credential Manager. Tokens are not
stored in browser storage or exposed to the React frontend.

## Status

Aster Launcher is currently available only to selected closed-alpha testers.

## Disclaimer

Aster Launcher is an independent third-party project and is not affiliated
with, endorsed by, or sponsored by Mojang Studios or Microsoft.
