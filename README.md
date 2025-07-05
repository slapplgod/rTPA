# rTPA
Paper plugin that adds rTPA and TPA functionality.
## Features

- Allows people to request to teleport to another player.
- Also allows people to 'friend' other players. When you request to teleport to a friended player, you bypass the request and immediately teleport to them.
- High customizability. Restrict and allow additional features at your will (assuming you are the server owner).

## Installation

The installation process is similar to any other plugin.
1. Download the latest  .jar file.
2. In your PaperMC server, locate the 'plugins' folder.
3. Paste it into the folder.

## Usage

- `/tpa <player>` - Send a teleport request to the player you specified. If you have friended the user, it acts like `/tp <player>`.
- `/tpaccept` - Accept the pending teleport request; player will teleport to you. If there are multiple teleport requests at once, you will have to specify the player.
- `/tpadeny` - Denies the teleport request. Unlike `/tpaccept`, it denies all requests. If your teleport request gets denied, you have a 30 second cooldown before you can retry.
- `/rtpa` - Opens the settings for the plugin.
- `/rtpa friend <player>` - Sends a request to friend said user. If they accept, you have the ability to bypass the request and are able to teleport to the player immediately.
  
  **WARNING:** You can only send a friend request to a user once. If they deny your request, you cannot request to friend them again; the only exception is if they request to friend you.

## Disclaimer
The project is still in beta and releases are not planned yet. When the project does come out, you will be able to install it from CurseForge or from Modrinth.
<!-- Update this section when the plugin releases. -->
Localization is planned for a major update.
