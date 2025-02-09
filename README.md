# Debloating Script for Debian-based Systems

This script is designed to help users streamline their Linux systems by removing non-essential packages and unnecessary dependencies that might bloat the system. While the script is distro-agnostic, it is primarily focused on Debian-based distributions (like Ubuntu, Mint, etc.), ensuring compatibility with the most common package management tools and system configurations.

The main goal of this script is to provide a simple, efficient, and configurable solution for users looking to "de-bloat" their systems, removing software packages and services that aren’t strictly required for day-to-day use, resulting in a leaner and more performance-efficient system.

### Features

- Distro-agnostic: Works across different distributions using `apt` (though optimized for Debian-based systems).
- Target Audience: Primarily targets at unnecessary packages in **Debian** and its derivatives, ensuring the system still remains functional.
- Customizable: You can configure the script to remove specific packages or leave certain packages untouched, giving you full control over which software stays or goes.
- Safe Defaults: The script focuses on non-critical packages—those that aren't essential for core system functionality—so your system won't break.
- Easy to Use: A simple command-line script that requires minimal configuration to get started.

### Benefits

- Reduced System Footprint: Removing unneeded packages can save valuable disk space.
- Improved Performance: A leaner system may lead to improved boot times, faster system performance, and reduced resource consumption.
- Clean Installation: It helps in starting fresh by removing bloated software that typically comes pre-installed in certain Linux distributions.

### Usage

Clone this repository:

```bash
git clone https://github.com/yourusername/debloat-script.git
cd debloat-script
```

```bash
chmod +x debloat-gui.sh
```

```bash
./debloat.sh
```

Optionally, configure the script before running (e.g., modifying the configuration file to include or exclude specific packages).


#### Important Notes

- Backup: Always backup important data before running any script that modifies your system.
- Compatibility: While this script is designed to work on most Debian-based distributions, it is important to verify compatibility with your specific setup.
- Dependencies: The script may require root privileges to remove system packages. Run the script with sudo if necessary.

Use at your own risk! Do not run before you understood the code.

### Guidelines

Here are some strategies and tools you can use to manage bloat without risking system integrity:

- Regular Maintenance Commands:

sudo apt autoremove: This command removes packages that were automatically installed to satisfy dependencies for other packages and are no longer needed.

sudo apt clean: This command cleans up the local repository of downloaded package files.
Managing Logs:

Journalctl: You can use journalctl to manage logs more effectively. For example, journalctl --vacuum-size=100M will limit the size of the logs to 100MB. You can also set up a cron job to regularly clean up logs.

- Disable Unnecessary Logging: Some services might have options to disable logging or reduce the verbosity of logs. Check the documentation for these services.

#### Cleaning Up After Applications:

- Manual Cleanup: After uninstalling an application, check common locations like /var/log, /var/cache, and your home directory for any lingering files. Be cautious and ensure these files are not critical before deleting them.

- Use Specific Tools: Some applications might leave configuration files in your home directory. These are usually hidden and can be found using find or by manually checking directories like ~/.config and ~/.local/share.

- Automated Cleanup Tools:

- BleachBit: This is a system cleaner that can delete various types of files that are no longer needed, including cache, cookies, and temporary files.

### Preventative Measures:

- Be Selective with Software: When installing new software, consider whether you really need it and if it's necessary for your workflow.
Use Lightweight Alternatives: If bloat is a major concern, consider using lightweight versions of applications or different software that is known for being less resource-intensive.

### System Configuration:

- Tweak System Settings: Depending on your system and usage, you might be able to tweak settings to reduce the amount of logging or cache generation.

### Backup and Restore:

Use Snapshots or Backups: Before making significant changes to your system, consider using tools like Timeshift to create a snapshot. This way, if something goes wrong, you can restore your system to a previous state.

### Packages

Here's a brief overview of each individual package (optionally) removed from your System and their purpose:

- ncurses-term | Provides terminal definitions for ncurses, a library that supports text-based user interfaces. This package ensures proper terminal behavior on different terminal types (e.g., xterm, vt100).

- pidentd | Daemon used for handling ident requests. It helps identify the user associated with a specific connection (based on the RFC 1413 standard).

- usbutils | Set of tools for managing and displaying information about USB devices connected to the system. It includes lsusb, which shows a list of connected USB devices.

- gnome-software | A graphical software management tool for GNOME, enabling users to discover, install, and update software packages.

- malcontent | A library that integrates privacy features with GNOME, helping applications track and enforce privacy-related settings.

- uim | A framework for input method management in UNIX-like systems, allowing users to enter text in various languages through customizable input methods.

- uim-xim | A plugin for uim that allows it to work with the X Input Method (XIM) protocol, enabling better integration with X-based applications.

- im-config | A tool for configuring input methods on Linux systems, making it easier to select and manage different input methods.

- fcitx5-data | Contains data files for fcitx5, a popular input method framework for Linux that supports various languages.

- fcitx-bin | The core components and binary files required to run the fcitx5 input method framework.

- fcitx-module-dbus | A DBus module for the fcitx5 input method framework, enabling communication between the input method and other applications.

- fcitx-config-common | Common configuration files for the fcitx5 framework, used for setting up input methods on Linux systems.














