# Game Host Bros - Default Configurations

This repository contains default server configuration files for various game servers. These configs are ready to use with [Game Host Bros](https://gamehostbros.com) hosting services, but can be used with any server setup.

## Available Configurations

Currently, this repository includes configuration files for:

- **Half-Life Dedicated Server (HLDS)**
- **Quake Live**
- **Counter-Strike 2**

## How to Use These Files

You don't need to be tech-savvy to use these configuration files! Just follow these simple steps:

1. Download the folder for the game you want to set up
2. Upload the files to your game server (replace any existing ones)
3. Restart your server

That's it! Your server will now use these configurations.

## Customizing Your Server

Each config file has a section marked "Custom Commands" where you can add your own settings without interfering with the panel-managed settings.

Example from HLDS server.cfg:
```
hostname "Game Host Bros Server"
rcon_password "password"
sv_password ""

/// Custom Commands
// Add your custom settings below this line
```

## Contributing

Feel free to suggest improvements to these configuration files by opening an issue or pull request!