# Awesome-Terminal-File-Manager-CLI-Productivity
# Awesome-Terminal-File-Manager-CLI-Productivity

# Top Terminal File Manager & CLI Productivity Ecosystem

**Curated List of Proprietary/Cloud-Enabled File Managers & Open-Source GitHub Projects**  
*Focused on Terminal User Interface (TUI) File Managers, Dual-Pane Commanders & Modern CLI File Utilities*  
**Last updated: November 2026**

This repository tracks notable **proprietary/cloud-integrated file managers** and **open-source projects** for **Terminal File Managers & CLI Productivity**. These tools empower developers, sysadmins, and power users to navigate directories, preview media, manage archives, transfer remote files (SFTP/S3/WebDAV), and manipulate files at keyboard speed.

**Examples** include yorukot/superfile, Yazi, lf, Ranger, nnn, Midnight Commander, VIFM, broot, Far Manager, Double Commander, muCommander, Total Commander, ForkLift, Path Finder, Directory Opus, and Commander One.

**Open-source emphasis**: This list heavily expands on active open-source TUI file managers, dual-pane commanders, and Rust/Go-powered CLI file productivity tools — ideal for terminal power users, Linux/macOS ricers, and developers optimizing keyboard-driven workflows.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Total Commander](https://ghisler.com)**  
  Iconic commercial dual-pane file manager for Windows and Android featuring cloud storage plugins (Google Drive, Dropbox, OneDrive, S3), built-in FTP/SFTP, and batch renaming.

- **[ForkLift](https://binarynights.com)**  
  Commercial dual-pane file manager and file transfer client for macOS with native cloud integrations for Amazon S3, Google Drive, Dropbox, Backblaze B2, and SFTP.

- **[Commander One](https://commander-one.com)**  
  Proprietary dual-pane file manager for macOS built in Swift that mounts cloud drives (AWS S3, Google Drive, OneDrive, Dropbox) as local volumes alongside a built-in terminal emulator.

- **[Directory Opus](https://gpsoft.com.au)**  
  Commercial advanced file manager and Explorer replacement for Windows offering multi-pane layouts, FTP/cloud sync, scripting, and batch file operations.

- **[Path Finder](https://cocoatech.io)**  
  Commercial macOS file browser featuring dual-pane navigation, integrated terminal panes, Dropbox/cloud sync, and advanced batch file manipulation.

- **[FileBrowser / Web Cloud File Managers (Commercial Tiers)](https://files.com)**  
  Cloud-hosted enterprise file management and transfer platforms providing web, CLI, and SFTP access across multi-cloud storage backends.


## Open-Source GitHub Projects

- **[superfile (yorukot/superfile)](https://github.com)**  
  Modern, pretty, and feature-rich terminal file manager written in Go with multi-panel layouts, customizable themes, rich file previews, and intuitive hotkeys.

- **[Yazi](https://github.com)**  
  Blazing-fast terminal file manager written in Rust based on non-blocking async I/O, featuring built-in image/video/code previews, plugin architecture, and Vim-like keybindings.

- **[lf](https://github.com)**  
  Fast, lightweight terminal file manager written in Go inspired by Ranger, featuring client-server architecture, customizable keybindings, and cross-platform support.

- **[Ranger](https://github.com)**  
  Classic console file manager with Miller columns, Vim keybindings, rifle file launcher, and extensible Python previews.

- **[nnn](https://github.com)**  
  Ultra-lightweight, unbloated terminal file manager written in C with near-zero memory footprint, disk usage analyzer, batch renamer, and extensive plugin ecosystem.

- **[Midnight Commander (mc)](https://github.com)**  
  Legendary open-source dual-pane terminal file manager for Unix-like systems featuring built-in VFS (FTP, SFTP, SMB, tar), text editor, and mouse/keyboard navigation.

- **[VIFM](https://github.com)**  
  Dual-pane terminal file manager with deep Vim-like modal keybindings, command-line mode, registers, and directory comparison.

- **[broot](https://github.com)**  
  Interactive terminal directory tree explorer written in Rust with fuzzy search, live file previews, Git status integration, and instant directory jumping.

- **[Far Manager](https://github.com)**  
  Open-source orthodox dual-pane console file and archive manager for Windows (with cross-platform `far2l` port for Linux/macOS) supporting rich plugin ecosystems.

- **[Double Commander](https://github.com)**  
  Cross-platform open-source dual-pane file manager inspired by Total Commander, supporting multi-rename tools, tabbed interfaces, and Total Commander WCX/WFX plugins.

- **[muCommander](https://github.com)**  
  Cross-platform, open-source dual-pane file manager supporting local filesystems alongside FTP, SFTP, SMB, Amazon S3, Google Drive, and Dropbox.

- **[joshuto](https://github.com)**  
  Fast, Ranger-inspired terminal file manager written in Rust with multi-tab support, async file operations, and customizable TOML configuration.

- **[xplr](https://github.com)**  
  Hackable, minimal, fast TUI file explorer written in Rust designed to be extended via Lua scripting and combined with Unix CLI tools.

- **[walk](https://github.com)**  
  Terminal navigator written in Go designed as a fast, interactive replacement for `cd` and `ls` with fuzzy filtering and instant directory switching.

### Additional Strong Open-Source Options

- **[eza](https://github.com)** — Modern, maintained replacement for `ls` written in Rust with Git status, icons, and tree views.
- **[zoxide](https://github.com)** — Smarter `cd` command that learns your most-used directories for instant fuzzy jumping.
- **[fd](https://github.com)** & **[fzf](https://github.com)** — Blazing-fast file finder and general-purpose command-line fuzzy finder that supercharge any terminal file workflow.
- **[dua-cli](https://github.com)** & **[ncdu](https://yorhel.nl)** — Fast terminal disk usage analyzers for interactively finding and deleting large files.
- **[rclone](https://github.com)** — Open-source command-line program ("rsync for cloud storage") to manage and sync files across 70+ cloud providers.
- **[File Browser](https://github.com)** — Single-binary self-hosted web file manager for managing server directories from a browser.

**Frameworks for building custom systems**: Combine **Yazi** or **superfile** with **zoxide**, **fzf**, **fd**, and **rclone** for an ultra-fast terminal file and cloud-storage workflow across local and remote machines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's proprietary/cloud or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Terminal file managers perform direct filesystem deletions and batch renames; verify trash/recycle-bin configuration (`trash-cli` or native OS trash) before running destructive commands.
- Always secure remote SFTP, SMB, and cloud storage credentials when mounting external volumes.

---

**Made for Linux/macOS ricers, sysadmins, keyboard power users, and open-source developers.**  
Let's make terminal file navigation and CLI productivity faster, sharper, and open to everyone.
