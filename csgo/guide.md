# Intro

This guide is meant describe how you are setting up CS:GO server for a 3v3 tournament.

This server configuration should set the game type and game mode to classic competitive.

# Installing
Use the game server managers tools since it makes everything just easier. https://gameservermanagers.com/lgsm/csgoserver/
Follow their guide on installing CS:GO

The part of creating a new user is optional if you are using a dedicated VM for the server.

During the installation the installer will ask you for a token. The token is used to bind a server to an account. You generate the token by logging in on their manage game server page (https://steamcommunity.com/dev/managegameservers) You should use the number `730` as game ID.

# Config

Following config is for 3v3 tournament matches

Replace `~/lgsm/config-lgsm/csgoserver/common.cfg` with the `common.cfg` found in this repository.
Also replace  `~/serverfiles/csgo/cfg/csgoserver.cfg` with the `csgoserver.cfg` found in this repository.

In the `csgoserver.cfg` change the `rcon_password` and `sv_password` to something appropriate.

# Test

Now find someone that knows how it should work and let them test it out.
