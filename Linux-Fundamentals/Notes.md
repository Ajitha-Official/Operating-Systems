# Linux Fundamentals: Chapter 1 - Linux Structure

## History
- Inspired by **Unix (1970)** and **GNU Project (1983)**.
- **Linus Torvalds** created the Linux kernel in **1991** as a free, open-source OS kernel.
- Powers **600+ distributions** like Ubuntu, Fedora, and RedHat.
- Widely used in servers, desktops, and Android devices.
- Known for **security**, **stability**, and **performance**, though it has fewer hardware drivers than Windows.

---

## Philosophy
1. **Everything is a File**: Configuration stored in text files (e.g., `/etc/passwd`).
2. **Single-Purpose Programs**: Tools perform one task well.
3. **Chaining Programs**: Combine tools to handle complex tasks.
4. **No Captive Interfaces**: Focus on shell/terminal for user control.
5. **Text-Based Configs**: Easy to manage and edit.

---

## Components
- **Bootloader**: Guides OS boot (e.g., GRUB).
- **Kernel**: Core of Linux, manages hardware and processes.
- **Daemons**: Background services (e.g., printing, scheduling).
- **Shell**: CLI to interact with the kernel (e.g., Bash, Zsh).
- **Graphics Server**: GUI framework (e.g., X-server).
- **Window Manager**: Graphical user interface (e.g., GNOME, KDE).
- **Utilities**: Programs for specific functions.

---

## Linux Architecture
1. **Hardware**: Physical components like CPU and RAM.
2. **Kernel**: Core OS component managing hardware and resources.
3. **Shell**: CLI to interact with the kernel.
4. **System Utility**: Offers OS functionality to the user.

---

## File System Hierarchy
Linux uses a tree-like structure, standardized by FHS (Filesystem Hierarchy Standard).

### Key Directories:
- `/`: Root directory.
- `/bin`: Essential commands.
- `/boot`: Boot files and kernel.
- `/dev`: Device files.
- `/etc`: Configuration files.
- `/home`: User directories.
- `/lib`: Shared libraries.
- `/tmp`: Temporary files.
- `/var`: Variable data like logs.
- `/usr`: User programs and libraries.
