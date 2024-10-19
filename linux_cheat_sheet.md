# Linux Cheat Sheet 📜

Welcome to this cheat sheet with essential Linux commands.

---

## 🐧 Linux Commands

### 1. **File and Directory Management**
| Command                          | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `ls`                              | List files and directories in the current directory.                        |
| `cd [directory]`                  | Change to a specific directory.                                             |
| `pwd`                             | Print the current working directory path.                                   |
| `mkdir [directory_name]`          | Create a new directory.                                                     |
| `touch [file_name]`               | Create a new empty file.                                                    |
| `cp [source] [destination]`       | Copy files or directories from one location to another.                     |
| `mv [source] [destination]`       | Move or rename files and directories.                                       |
| `rm [file_name]`                  | Remove a file (use `rm -r [directory_name]` to remove a directory).         |

### 2. **File Permissions & Ownership**
| Command                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `chmod [permissions] [file]`      | Change file/directory permissions (e.g., `chmod 755 file.sh`).              |
| `chown [user]:[group] [file]`     | Change the ownership of a file or directory.                                |
| `ls -l`                           | List files with detailed information including permissions.                 |

### 3. **Package Management**
| Command                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `sudo apt update`                 | Update the package index (Debian/Ubuntu).                                   |
| `sudo apt upgrade`                | Upgrade all installed packages to the latest versions (Debian/Ubuntu).      |
| `sudo yum update`                 | Update packages on a RedHat/CentOS system.                                  |
| `sudo yum install [package]`      | Install a specific package on RedHat/CentOS.                                |

### 4. **System Monitoring & Management**
| Command                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `top`                             | Display real-time system resource usage.                                    |
| `df -h`                           | Show disk usage with human-readable sizes.                                  |
| `free -m`                         | Display memory usage in megabytes.                                          |
| `systemctl [start|stop|status] [service]` | Start, stop, or check the status of a system service (e.g., `systemctl status docker`). |
| `journalctl -u [service]`         | View logs for a specific service.                                           |

---
