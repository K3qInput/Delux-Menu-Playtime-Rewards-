# Playtime Rewards BoxPvP - Delux Menu Configuration

This repository provides a custom configuration for the Delux Menu plugin, specifically designed for Playtime Rewards in BoxPvP. The `levels.yml` file included here allows server admins to integrate a rewards system based on player playtime.

## Features

- **Customizable Playtime Rewards**: Configure rewards based on player activity.
- **Seamless Integration**: Works smoothly with the Delux Menu plugin.
- **User-Friendly Setup**: Simple and straightforward installation process.

## Prerequisites

- **Minecraft Server** running Spigot, Paper, or any other server software compatible with Bukkit plugins.
- **Delux Menu Plugin**: Make sure you have the Delux Menu plugin installed on your server.

## Installation Guide

### Step 1: Download the `levels.yml` File

1. Click the green `Code` button on the top right of this page.
2. Download the repository as a ZIP file, or clone it using Git:
    ```bash
    git clone https://github.com/yourusername/playtime-rewards-boxpvp.git
    ```
3. Extract the ZIP file (if downloaded) to access the `levels.yml` file.

### Step 2: Upload the `levels.yml` File to Your Server

1. Connect to your Minecraft server using an FTP client (like FileZilla) or through your server's file manager.
2. Navigate to the following directory in your server files:
    ```
    /plugins/DeluxMenus/menus/
    ```
3. Upload the `levels.yml` file to this directory.

### Step 3: Edit Your `config.yml` File (Optional)

If you want to integrate this menu with other existing menus, you may need to edit the `config.yml` file located in the same directory (`/plugins/DeluxMenus/`).

1. Open the `config.yml` file with a text editor.
2. Add or modify the configuration to include the `levels.yml` menu. An example entry might look like this:
    ```yaml
    menus:
      levels:
        file: levels.yml
    ```
3. Save and close the `config.yml` file.

### Step 4: Reload Delux Menu

1. In your server console or in-game, reload the Delux Menu plugin to apply the changes:
    ```bash
    /dm reload
    ```
2. Verify that the menu has been successfully loaded by using the command to open the menu (e.g., `/menu levels`).

## Customization

The `levels.yml` file can be customized to fit your server's needs. Adjust the rewards, thresholds, and other settings according to your preference.

### Example Customization

- **Changing Rewards**: Locate the reward sections in `levels.yml` and modify the commands or items given as rewards.
- **Adjusting Playtime Requirements**: Change the playtime thresholds for each level within the configuration file.

## PREVIEW
- https://ibb.co/CBdKT6G
- https://ibb.co/9HXHPKn
  
## Support

If you encounter any issues or have questions, feel free to open an issue in this repository, and I'll do my best to assist you.

## Contributing

Contributions are welcome! If you have a feature suggestion or want to submit a pull request, please follow the standard GitHub workflow.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
