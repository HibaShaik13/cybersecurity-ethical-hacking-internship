# Linux Command Cheat-Sheet

## File System Navigation
| Command | Description |
|---|---|
| `pwd` | Print current directory |
| `ls` | List files in current directory |
| `ls -la` | List all files (including hidden), with details |
| `cd <dir>` | Change directory |
| `cd ..` | Move up one directory |

## File & Directory Permissions
| Command | Description |
|---|---|
| `chmod 755 file` | Set permissions (owner: rwx, group/others: r-x) |
| `chmod +x script.sh` | Make a file executable |
| `chown user:group file` | Change file owner/group |

## Package Management
| Command | Description |
|---|---|
| `sudo apt update` | Refresh package lists |
| `sudo apt upgrade -y` | Upgrade all installed packages |
| `sudo apt install <pkg>` | Install a package |
| `dpkg -l` | List installed packages |

## Networking Commands
| Command | Description |
|---|---|
| `ifconfig` | Show network interfaces and IP addresses |
| `ping <ip>` | Test connectivity to a host |
| `netstat -tulnp` | Show active listening ports |
| `traceroute <ip>` | Trace the network path to a host |

## Useful shortcuts
- `Ctrl+Shift+C` / `Ctrl+Shift+V` — copy/paste inside terminal (not Ctrl+C/V, which cancels a command)
- `Ctrl+C` — cancel a running command
- `sudo !!` — re-run the last command with sudo
