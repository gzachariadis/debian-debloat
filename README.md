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

### Packages

Here's a brief overview of each individual package (optionally) removed from your System and their purpose:

- XTerm+Thai | A variant of the XTerm terminal emulator that includes additional support for displaying Thai characters.

- XTerm | Terminal emulator for the X Window System.

- MLTerm | Another terminal emulator for X11, similar to XTerm, but with enhanced features like better internationalization support.

- Cheese | A simple application for taking photos and videos using a webcam.

- Kasumi | Privacy-focused application designed to help users manage and anonymize their internet usage; often used to route connections through Tor and VPNs for privacy and security.

- GoldenDict | Dictionary program that provides a rich, customizable dictionary interface.

- ImageMagick | Open-source software suite used to create, edit, and convert bitmap images.

-  Redshift | Adjusts the color temperature of your screen according to the time of day.

- GNOME Klotski | Sliding block puzzle game for GNOME. 

- GNOME Mahjongg | Mahjong solitaire game for GNOME. 

- GNOME Mines | Minesweeper game, where the player has to clear a grid of cells without triggering hidden mines.

- GNOME Robots | Puzzle game, where the goal is to guide a robot through a maze-like area while avoiding obstacles.

- GNOME Sudoku | Digital version of the classic Sudoku puzzle.

- GNOME Tetravex | Puzzle game in which you have to arrange tiles with numbers so that the numbers on adjacent edges match.

- GNOME Nibbles | Snake-like game, like on old smartphones.

- Quadrapassel | Puzzle game similar to Tetris, where the player manipulates falling blocks to create complete lines.

- Tali | Dice game that involves rolling dice and attempting to match the rolled numbers with certain scoring patterns.

- LightsOff | Puzzle game where the objective is to turn off all the lights on a grid.

- Swell Foop | Puzzle game where the player must rotate pieces on a grid to form a continuous, connected pattern.

- HexChat | A popular IRC (Internet Relay Chat) client.

- Thunderbird | A free, open-source email client developed by Mozilla. 

- LibreOffice Core | The main part of the LibreOffice suite, which is an open-source office productivity suite.

- LibreOffice Common | Contains common files shared across the LibreOffice suite, such as icons, templates, and other resources used by all the different LibreOffice applications.

- Transmission GTK | Graphical user interface (GUI) for the Transmission BitTorrent client.

- Baobab | Disk Usage Analyzer, it is a graphical tool used to scan and visualize disk space usage.

- Seahorse | Graphical front-end for managing encryption keys and passwords, often used with GPG (GNU Privacy Guard).

- Rhythmbox | Music player and manager for GNOME, designed to play and organize music.

- Pix | Simple photo manager for GNOME.

- Simple Scan | Straightforward scanning application designed for GNOME.

- Drawing | Simple vector graphics editor designed for quick and easy drawing and illustration tasks.

- Gnote | Note-taking application for GNOME, inspired by Tomboy.

- XReader | Document viewer for GNOME, primarily designed for reading PDFs.

- Onboard | An on-screen keyboard application for users who need a virtual keyboard for accessibility purposes.

- GNOME Calendar | Simple calendar application for the GNOME desktop. It allows users to manage events, tasks, and appointments. It integrates with other calendar systems like Google Calendar or Exchange for syncing.

- Celluloid | Simple media player for Linux, which focuses on ease of use and a minimalistic interface.

- GNOME Logs | System log viewer for GNOME, allowing users to read and filter system logs.

- GNOME Power Manager | A power management utility for GNOME that allows users to manage power settings, battery usage, and energy consumption for laptops and desktops.

- Warpinator | File-sharing tool designed to transfer files between Linux machines over a local network. It provides a simple and easy way to send files and folders without needing additional setup or complex configurations.

- Aisleriot | Collection of card games for GNOME, typically known as Solitaire games.

- BRLTTY | Screen reader for braille devices. It allows blind or visually impaired users to interact with the system by using a braille display. It converts the text displayed on the screen into braille.

- Duplicity | Backup tool that supports encrypted, bandwidth-efficient backups.

- Empathy | Messaging application for GNOME that supports various chat protocols (like Jabber, Google Talk, MSN, Facebook, etc.).

- Empathy Common | Contains common files used by Empathy to support various messaging protocols and features, such as account management, chat logs, and other shared components.

- Example Content | Package containing sample files and content, usually for testing purposes or as an example for users.

- GNOME Accessibility Themes | Provides themes specifically designed to improve the accessibility of the GNOME desktop environment.

- GNOME Contacts | Contact management application for GNOME.

- GNOME Orca | Screen reader for GNOME, designed to assist users with visual impairments.

- GNOME Screensaver | The screensaver application for the GNOME desktop environment.

- GNOME Video Effects | Set video effects for the GNOME desktop, offering various visual enhancements for videos, including transitions, effects, and filters.

- Landscape Common | A set of common files for the Landscape system management tool, which is used to manage and monitor Ubuntu systems in an enterprise environment.

- LibreOffice Avmedia Backend GStreamer | Backend plugin for LibreOffice that integrates with the GStreamer multimedia framework, enabling LibreOffice to handle audio and video content.

- LibreOffice Base Core | Core components of LibreOffice Base, the database management application.

- LibreOffice Calc | Spreadsheet application in the LibreOffice suite, similar to Microsoft Excel. It allows users to create, analyze, and manage data with powerful calculation tools and functions.

- LibreOffice Draw | Vector graphics editor in the LibreOffice suite, used for creating diagrams, illustrations, flowcharts, and technical drawings.

- LibreOffice GNOME | LibreOffice with the GNOME desktop environment, ensuring seamless interaction between LibreOffice applications and GNOME features such as GTK and theme integration.

- LibreOffice GTK | Provides support for GTK-based themes, ensuring LibreOffice looks and feels integrated within the GTK desktop environments (like GNOME).

- LibreOffice Impress | The presentation application in the LibreOffice suite, similar to Microsoft PowerPoint.

- LibreOffice Math | The mathematical formula editor in LibreOffice, used for creating and editing mathematical formulas and equations within documents, spreadsheets, and presentations.

- LibreOffice Ogltrans | LibreOffice plugin for 3D OpenGL presentations.

- LibreOffice PDFImport | A plugin that allows users to import PDF files into LibreOffice Draw or Writer, enabling editing and modifying of PDF content.

- LibreOffice Style Galaxy | A theme/style pack for LibreOffice that provides a set of icons and visual themes (specifically the "Galaxy" style) for the LibreOffice suite.

- LibreOffice Style Human | A theme/style pack for LibreOffice that offers a set of icons and visual themes (specifically the "Human" style) to match the default GNOME theme.

- LibreOffice Writer | The word processor application in the LibreOffice suite, similar to Microsoft Word. It is used for creating, editing, and formatting text documents.

- libsane | A library that provides access to scanners and other imaging devices. It serves as the backend for various scanning applications (e.g., Simple Scan, XSane).

- libsane-common | Contains the common files for libsane, including configuration files and other resources necessary for the proper operation of scanner software.

- python3-uno | A Python binding to the LibreOffice UNO (Universal Network Objects) API, allowing developers to create Python scripts and extensions for interacting with LibreOffice applications.

- Rhythmbox Plugins | A collection of plugins for the Rhythmbox music player. These plugins extend Rhythmbox with additional features such as new audio formats, media controls, or integration with online music services.

- Rhythmbox Plugin Zeitgeist | A plugin for Rhythmbox that integrates with the Zeitgeist framework, which tracks user activity. It helps provide better recommendations based on listening history and behavior.

- Sane-utils | A package containing utilities for interacting with scanners and image acquisition devices. It includes command-line tools like scanimage and sane-find-scanner for scanning tasks.

- Shotwell | Photo manager for GNOME that allows users to import, organize, and edit their photos. It supports features like tagging, metadata editing, and simple image adjustments.

- Shotwell Common | Contains common files for the Shotwell photo manager, such as shared resources and libraries used by Shotwell for managing images and metadata.

- Telepathy Gabble | A protocol plugin for the Telepathy framework that enables instant messaging support for XMPP/Jabber (e.g., Google Talk, Facebook chat).

- Telepathy Haze | Plugin for the Telepathy framework that provides support for MSN Messenger (Windows Live Messenger) chat protocols, enabling users to chat with others using MSN.

- Telepathy Idle | Plugin for the Telepathy framework that enables support for IRC (Internet Relay Chat) communication protocols.

- Telepathy Indicator | Telepathy plugin that integrates with GNOME’s indicator applet, providing a notification area for chatting and messaging.

- Telepathy Logger | Plugin for Telepathy that logs chat history and interactions. It records messages for later retrieval or review.

- Telepathy Mission Control 5: Core component of the Telepathy framework, providing centralized management of communication connections and managing user accounts for different chat protocols.

- Telepathy Salut | Telepathy plugin that provides support for the Bonjour (ZeroConf) protocol, enabling peer-to-peer communication (like direct messaging and file transfer).

- Totem | The default media player for GNOME, based on GStreamer.

- Totem Common | Contains common files for Totem, such as libraries and plugins that extend its functionality, enabling support for various media formats and codecs.

- Totem Plugins | Set of additional plugins for Totem, enhancing its capabilities with features like subtitle support, audio/video streaming, and more.

- Printer Driver Brlaser | Printer driver package for Brother laser printers.

- Printer Driver Foo2zjs | Printer driver for ZJS (Zebra, Samsung, and others) printers. It provides support for various printers from manufacturers like Samsung, Sharp, and more.

- Printer Driver Foo2zjs Common | Contains common files required for the foo2zjs printer driver, such as configuration files and scripts.

- Printer Driver M2300W | Driver package specifically for the Brother MFC-2300W printer, enabling Linux users to print and scan from the device.

- Printer Driver PTouch | Printer driver for Brother P-Touch label printers.

- GNOME 2048 | Tile-based puzzle game in which the player merges tiles with the same number to form larger numbers, ultimately trying to reach the tile with the number 2048.

- Five or More | Classic puzzle game where the player must align five or more like-colored balls in a row to remove them from the grid.

- Four in a Row | Strategy game, similar to Connect Four, where the player attempts to align four of their colored pieces in a row (either horizontally, vertically, or diagonally).

- Hitori | Logic-based number puzzle game where the player must fill in cells to eliminate repeated numbers in each row and column, while also ensuring that no two black cells are adjacent.

- Iagno | Computerized version of the game Reversi (also known as Othello), where two players take turns placing pieces on the board.

- GNOME Chess | Chess game for the GNOME desktop environment; it provides a graphical interface for playing chess.

- GNOME Taquin | Sliding puzzle game similar to the 15-puzzle, where the goal is to arrange the shuffled tiles into their correct order by sliding them into an empty space.

- acpi | ACPI (Advanced Configuration and Power Interface) is a power management framework that enables the operating system to control the amount of power used by the system's components, allowing for more efficient power usage, such as suspending or hibernating the system.

- acpid | ACPI Daemon, or acpid, listens for ACPI events (such as pressing the power button or closing the laptop lid) and responds accordingly.

- aptitude | Text-based front-end to APT (Advanced Package Tool), aptitude provides a way to interact with the package management system for installing, upgrading, or removing software in a Debian-based distribution, like Ubuntu.

- at | A command-line utility that allows users to schedule tasks to be run once at a specific time. For example, you can use it to run a command in the future without needing to keep the terminal open.

- aspell | A spell-checking program that is often used by various text editors and other applications.

- aspell-en | The English dictionary for Aspell.

- avahi-daemon | Avahi is a system for zero-configuration networking (also called Bonjour or mDNS).

- bash-completion | Package that enhances the Bash shell by providing auto-completion of commands, file names, and other inputs.

- bc | Command-line calculator that supports arbitrary precision arithmetic.

- bin86 | Set of tools and libraries for working with x86 assembly language, often used for low-level system programming.
  
- bind9-host | DNS lookup utility that is part of BIND 9 (Berkeley Internet Name Domain), used for querying DNS servers.

- ca-certificates | Package containing a set of trusted CA (Certificate Authority) certificates used to verify the authenticity of SSL/TLS certificates. It ensures secure HTTPS connections by checking that SSL certificates are signed by recognized authorities.

- console-common | Package that contains common files for managing text console behavior, including settings related to keyboard input and console display. It ensures proper functionality and configuration of text-based interfaces in Linux.

- console-data | Provides data files for managing and configuring various text-based console settings, such as keymaps and character sets for different languages.

- console-tools | Collection of programs for managing and configuring the console, including tools for managing keymaps, fonts, and terminal settings. These are essential for a customized text console experience.

- dc | Command-line calculator that supports reverse Polish notation (RPN), commonly used for doing arithmetic in shell scripts or on the command line. It’s useful for simple calculations with support for arbitrary precision.

- debian-faq | Package that contains the official Debian FAQ, providing essential information for Debian users, including how to use Debian, install packages, configure the system, and other useful tips for new users.

- debian-faq-de | The German-language version of the Debian FAQ. This package includes the FAQ translated into German for German-speaking Debian users.

- debian-faq-fr | French-language version of the Debian FAQ. It provides the FAQ in French, allowing French-speaking users to access essential information about Debian.

- debian-faq-it | Italian-language version of the Debian FAQ, which provides the frequently asked questions and guides in Italian for users who speak the language.

- debian-faq-zh-cn | Chinese (Simplified) version of the Debian FAQ, providing FAQs and basic help for Chinese-speaking users of the Debian system.

- dhcp | Package related to the Dynamic Host Configuration Protocol (DHCP), which allows a system to automatically obtain IP addresses and network configuration from a DHCP server.

- dhcp3-client | DHCP client package for Debian-based systems, allowing the system to obtain network configuration (like IP address, DNS, gateway) from a DHCP server.

- dnsutils | Set of utilities for managing DNS (Domain Name System). It includes tools like dig, nslookup, and others, useful for querying DNS servers and troubleshooting DNS-related issues.

- doc-debian | Documentation package containing general information about Debian, such as guides, manuals, and other materials for users and administrators.

-eject | Command-line tool for ejecting removable media such as CD/DVD drives or USB drives. It can also be used to safely eject mounted devices in Linux.

- fdutils | Utilities for handling floppy disks. These are legacy tools for managing floppy disk drives, typically used in older systems.

- File | A command-line utility that determines the type of a file by examining its content (e.g., text file, image file, executable). It helps in identifying files when the file extension is missing or incorrect.

- Finger | Command-line tool used to gather information about a user on a remote system, such as login name, real name, and other details. It can be used for querying user accounts on a network.

- Foomatic-filters | Package that provides filters used by the Foomatic print system, which helps support various printers under Linux by translating print jobs into a format understood by the printer.

- Gettext-base | Package providing essential components for gettext, a system for internationalization and localization. It allows software to support different languages by translating strings in the code to various languages.

- Groff | Typesetting system used to format and print text. It’s often used for formatting man pages and other text documents into nicely formatted output.

- gnupg | GNU Privacy Guard (GPG) is a tool for encrypting and signing data. It provides encryption for emails and files and is compatible with the OpenPGP standard for cryptography.

- gnu-efi | A library that helps with developing applications for UEFI (Unified Extensible Firmware Interface) systems, allowing programs to interact with UEFI systems and configure boot loaders.

- hplip | Package for HP printers and scanners. It contains drivers and software to support HP’s printers and multifunction devices, providing both printing and scanning capabilities.

- iamerican | The American English dictionary for Ispell, a spell checker. It provides the dictionary files required for spell checking in English.

- ibritish | British English dictionary for Ispell. It provides the dictionary files for spell checking in British English.

- info | Program that reads and displays GNU Info documents. It’s similar to man pages but more powerful, allowing users to navigate complex documentation and manuals.

- ispell | Spell checker that supports various languages. It checks spelling and suggests corrections, often used in word processors and text editors.

- laptop-detect | Package that detects if the system is running on a laptop and makes system configuration adjustments accordingly. It can modify power settings, enable certain drivers, and optimize the system for laptop hardware.

- libavahi-compat-libdnssd1 | Compatibility library for Avahi (a zero-configuration networking service) that provides support for Bonjour (Apple's mDNS) on Linux, enabling services like automatic network device discovery.

- libc6-amd64 | The GNU C Library (libc) for 64-bit systems. This package provides standard system libraries for running programs on 64-bit Debian-based systems.

- manpages | Collection of manual pages for various Linux commands, functions, and libraries. It’s a vital resource for accessing documentation and help about the Linux system.

- mtools | Collection of utilities for working with MS-DOS file systems, often used for interacting with floppy disks, USB drives, or other media formatted with FAT filesystems.

- mtr-tiny | Small and lightweight version of MTR (My Traceroute), a network diagnostic tool that combines the functionality of traceroute and ping to provide information about the network path and latency.

- mutt | Text-based email client for Unix-like systems. It is highly customizable and used by many command-line enthusiasts for managing email from the terminal.

- netcat | Often referred to as the "Swiss army knife" of networking, netcat is a versatile tool for reading and writing data across network connections.

- net-tools | Collection of networking utilities, including essential tools like ifconfig, netstat, and route, used for configuring and troubleshooting network interfaces and connections.

- ncurses-term | Provides terminal definitions for ncurses, a library that supports text-based user interfaces. This package ensures proper terminal behavior on different terminal types (e.g., xterm, vt100).

- openssh-client | Client program for accessing remote systems over SSH (Secure Shell). It is used to securely log into other computers, transfer files, and execute commands remotely.

- openssh-server | Server program for OpenSSH that allows remote users to access the system securely via SSH. It enables you to run an SSH server on your system.

- openssl | Toolkit for the Secure Sockets Layer (SSL) and Transport Layer Security (TLS) protocols, providing cryptographic functionality and command-line tools for managing SSL certificates, encryption, and security tasks.

- pidentd | Daemon used for handling ident requests. It helps identify the user associated with a specific connection (based on the RFC 1413 standard).

- ppp | The Point-to-Point Protocol (PPP) daemon. It is used for establishing a direct connection between two network nodes, typically for dial-up internet or VPN connections.

- pppconfig | Graphical tool for configuring PPP (Point-to-Point Protocol) connections, typically used for setting up dial-up or VPN internet connections.

- pppoe | The Point-to-Point Protocol over Ethernet (PPPoE) client used for connecting to DSL-based internet connections. It allows a computer to connect to the internet via a PPPoE service.

- pppoeconf | Configuration tool for setting up PPPoE internet connections on Debian-based systems.

- read-edid | Tool for reading the EDID (Extended Display Identification Data) from displays (monitors). It helps identify display capabilities like resolution, color depth, and supported modes.

- reportbug | Tool for reporting bugs in Debian packages. It helps users easily file bug reports with the Debian developers.

- ssh | The Secure Shell protocol used for securely accessing remote systems. The package provides both client and server utilities for secure remote logins and file transfers.

- tasksel | Tool used for installing predefined sets of software packages (tasks) based on your needs (e.g., web server, desktop environment, etc.). It simplifies setting up your system with a specific role in mind.

- tcsh | C shell (csh) variant with enhanced features, such as command-line editing and programmable completion. It’s an alternative shell for users who prefer C-like syntax.

- traceroute | A tool used to trace the path that packets take to a destination on the network. It shows the route and the time it takes to get from one point to another, useful for network troubleshooting.

- unzip | utility for decompressing files archived in the ZIP format, commonly used for extracting files from compressed archives.

- usbutils | Set of tools for managing and displaying information about USB devices connected to the system. It includes lsusb, which shows a list of connected USB devices.

- vim-common | Common files required for the Vim text editor. It includes configuration files, syntax files, and documentation, which are shared by all Vim variants.

- vim-tiny | lightweight version of Vim, a text editor. It’s often used for minimal installations or environments where resources are limited.

- wamerican | The American English dictionary for Ispell (a spell checker), used for checking the spelling of words in American English.

- w3m | Text-based web browser that can display HTML pages, images (in the terminal), and follow links from the command line.

- whois | Command-line tool used for querying WHOIS databases, which provide information about domain names, IP address allocations, and other network resources.

- zeroinstall-injector | Tool for using Zero Install, a decentralized software distribution system that allows users to install software without needing to worry about dependencies or package management systems.

- zip | A compression utility used for creating ZIP archives. It’s widely used to package multiple files and directories into a single compressed file for easy distribution and storage.

- ubuntu-desktop | The ubuntu-desktop package is a meta-package that installs all the core components required for a typical Ubuntu Desktop environment.

- ubuntu-session | The ubuntu-session package defines the session configuration for the Ubuntu Desktop, specifically the settings related to the user’s graphical login session.

- Firefox | Firefox is a popular open-source web browser developed by Mozilla.
  
- gnome-todo | GNOME To Do is a simple task management application for the GNOME desktop environment.
  
- gnome-maps | GNOME Maps is a map and navigation application for the GNOME desktop.

- Evolution | Evolution is a comprehensive personal information management tool, primarily known as an email client for Linux-based systems
  
- Quadrapa | "Quadrapa" might refer to a game or puzzle app.


