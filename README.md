# Debloating Script for Debian-based Systems

This script is designed to help users streamline their Linux systems by removing non-essential packages and unnecessary dependencies that might bloat the system. While the script is distro-agnostic, it is primarily focused on Debian-based distributions (like Ubuntu, Mint, etc.), ensuring compatibility with the most common package management tools and system configurations.

The main goal of this script is to provide a simple, efficient, and configurable solution for users looking to "de-bloat" their systems, removing software packages and services that aren’t strictly required for day-to-day use, resulting in a leaner and more performance-efficient system.

#### Important Notes

- Backup: Always backup important data before running any script that modifies your system.
- Compatibility: While this script is designed to work on most Debian-based distributions, it is important to verify compatibility with your specific setup.
- Dependencies: The script may require root privileges to remove system packages. Run the script with sudo if necessary.

Use at your own risk! Do not run before you understood the code.

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

### Guidelines

Here are some strategies and tools you can use to manage bloat without risking system integrity:

#### Regular Maintenance Commands:

sudo apt autoremove: This command removes packages that were automatically installed to satisfy dependencies for other packages and are no longer needed.

sudo apt clean: This command cleans up the local repository of downloaded package files.

#### Managing Logs:

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





