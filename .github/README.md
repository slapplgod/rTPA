# rTPA
Minecraft Server (primarily PaperMC) plugin that adds rTPA and TPA functionality.
## Features

- Allows people to request to teleport to another player.
- Also allows people to 'friend' other players. When you request to teleport to a friended player, you bypass the request and immediately teleport to them.
- The plugin has high customizability. Server owners have the ability to set a large majority of the plugin.

## Installation

The installation process is similar to any other plugin.
1. Download the latest  .jar file.
2. In your server filed, locate the 'plugins' folder.
3. Paste it into the folder.

## Usage

- `/tpa <player>` - Send a teleport request to the player you specified. If you have friended the player, it acts like `/tp <player>`.
- `/tpahere <player>` - Send a request for the player to teleport to you. If you have friended the player, it acts like `/tp <player>`.
- `/tpaccept` - Accept the pending teleport request; player will teleport to you. If there are multiple teleport requests at once, you will have to specify the player.
- `/tpadeny` - Denies the teleport request. Unlike `/tpaccept`, it denies all requests. If your teleport request gets denied, you have a 30 second cooldown before you can retry.
- `/tpacancel` - Cancels the teleport request you sent in.
- `/rtpa` - Opens the settings for the plugin.

  *Notice for server owners:* For technical and safety reasons, you cannot change server settings in-game. Locate the plugin's config files and change the settings from there.
- `/rtpa friend <player>` - Sends a request to friend said user. If they accept, you have the ability to bypass the request and are able to teleport to the player immediately.
  
  **⚠️ WARNING:** You can only send a friend request to a user once. If they deny your request, you cannot request to friend them again; the only exception is if they request to friend you.

## Contributing

### Do you have an issue or did you find a bug?
Please refer to this file explaining how to file a bug report.

### Do you wish to contribute to the project?
Please refer to this file for contributing.

## Disclaimer
The project is still in beta and releases are not planned yet. When the project does come out, you will be able to install it from CurseForge or from Modrinth.
<!-- Update this section when the plugin releases. -->
Localization is planned for a major update.

The plugin is built for Paper primarily, other server softwares may not work as intended due to this. Please do not open issues if you are not using Paper.

❗Do NOT attempt to change any of the settings while the server is running; there is a major risk for corruption otherwise.
By downloading and installing rTPA, you agree to [the following terms.](TERMS.md)
<!-- Link to be addded. -->
> TL;DR: I am not liable for any damages the plugin causes to your server; it is your responsibility to back up your server frequently.
