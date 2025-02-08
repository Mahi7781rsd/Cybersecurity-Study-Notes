# **Linux**  

## **What is Linux?**  
Linux is an **open-source, Unix-like** operating system (OS) that powers everything from servers and smartphones to embedded systems. It is known for its **stability, security, and flexibility**.  

### **Who Created Linux & Why?**  
- **Creator**: **Linus Torvalds** (1991)  
- **Why?**: He wanted a free, **customizable** OS since **Unix was expensive**  

---

## **Is Linux an OS? No, It's a Kernel!**  
Many people think Linux is an OS, but it's actually a **kernel**.  

### **What’s the Difference?**  
- **Linux = Kernel** → Manages hardware, memory, and processes.  
- **GNU/Linux = Full OS** → Linux + software tools (shell, compilers, libraries, etc.).  

### **Why Do People Call Linux an OS?**  
- In everyday use, people say "Linux" when they actually mean **GNU/Linux** (the full OS).  
- **Linux distributions** like **Ubuntu, Debian, and Arch** package Linux with utilities, making it a complete OS.  

---

## **What is a Distro (Linux Distribution)?**  
A **Linux distribution (distro)** is a **complete operating system** that packages the **Linux kernel** with essential software, system utilities, and a package manager.  

### **Why Are Distros Needed?**  
The **Linux kernel alone is not usable** for general users. Distros add:  
- **Shell & Terminal** – Command-line interface (e.g., Bash, Zsh).  
- **System Utilities** – Basic tools (`ls`, `cp`, `rm`).  
- **Software Package Manager** – Installs apps (`apt`, `dnf`, `pacman`).  
- **Graphical Interface (Optional)** – Desktop environments (GNOME, KDE).  

### **Examples of Linux Distros**  
1. **Ubuntu** – Beginner-friendly.  
2. **Debian** – Stable & reliable.  
3. **Arch Linux** – Minimal & customizable.  
4. **Fedora** – Cutting-edge software.  
5. **Kali Linux** – Cybersecurity & penetration testing.  

---

## **Linux Architecture (4 Layers)**  

| Layer             | Description                              |  
|------------------|--------------------------------------|  
| **Hardware**     | CPU, RAM, storage, etc.             |  
| **Kernel**       | Manages hardware, memory, and processes |  
| **Shell**        | Allows user interaction via commands |  
| **System Utilities** | Provides essential OS functions  |  

---

## **Components of Linux**  

| Component        | Description                              |  
|-----------------|-----------------------------------------|  
| **Bootloader**  | Starts the OS when you power on        |  
| **Kernel**      | The core of Linux, managing hardware and processes |  
| **Daemons**     | Background services like scheduling and printing |  
| **Shell**       | The command-line interface (e.g., Bash, Zsh) |  
| **Graphics Server** | Provides graphical system support (X-server) |  
| **Window Manager** | Controls GUI appearance (GNOME, KDE) |  
| **Utilities**   | Essential tools (`ls`, `grep`, `cp`)   |  

---

## **Linux Directory Structure (Analogy Included)**  

| Directory | Purpose | Simple Analogy |
|-----------|---------|----------------|
| `/`       | Root directory (everything starts here) | Foundation of a house |
| `/bin`    | Basic system commands | Toolbox |
| `/boot`   | Bootloader & Kernel | Car ignition |
| `/dev`    | Hardware access files | Control panel |
| `/etc`    | System configuration | Settings panel |
| `/home`   | User files | Personal room |
| `/lib`    | Shared system libraries | Engine of a car |
| `/media`  | Auto-mounted external drives | Plug-in station |
| `/mnt`    | Manual mount point | Workbench |
| `/opt`    | Optional third-party software | Guest room |
| `/root`   | Root user’s home | Master bedroom |
| `/sbin`   | Admin system commands | Maintenance room |
| `/tmp`    | Temporary files | Junk drawer |
| `/usr`    | User applications | Storage room |
| `/var`    | Logs, emails, data | Filing cabinet |

---

## **Why Is Linux Preferred by Hackers?**  
Linux is preferred by hackers because it gives full control over the system, unlike Windows, which has many restrictions. It has a powerful command-line interface (shell) that allows automation and scripting for hacking tasks. Linux also comes with built-in security and networking tools like **Nmap, Metasploit, and Aircrack-ng**, which are useful for penetration testing. It is **lightweight, customizable, and more secure**, making it ideal for ethical hackers and cybersecurity professionals. Plus, Linux distributions like **Kali Linux and Parrot OS** are specially designed for hacking and security testing.  

---

## **What is a Shell? (Explained Simply)**  
A **shell** is a **program** that allows you to **interact** with your computer by typing commands. It's like a translator between **you** and the **operating system**.  

### **Understanding the Bash Prompt in Linux**  
The Bash prompt is the text that appears in the terminal, indicating that the system is ready for input. By default, it displays the username, hostname, and current directory. The prompt changes depending on the user’s privileges:  
- A **regular user** sees a `$` at the end.  
- The **root user** (administrator) sees a `#`, indicating higher privileges.  

---

## **Linux Help Commands - Short Notes**  

### `man` (Manual Pages)  
Shows **detailed documentation** about a command.  
**Example:**  
```bash
man ls
```

### `help` (Shell Built-in Help)  
Provides **basic information** about shell commands.  
**Example:**  
```bash
help cd
```


> **Note:** This document is a work in progress and will be updated with more details soon. Stay tuned!

