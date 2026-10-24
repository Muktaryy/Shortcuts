# Linux Command Checklist

A practical checklist to learn and master Linux terminal commands, from basic navigation to advanced system administration and developer tools.

## 01. Navigation

* [ ] `pwd` — Print the current working directory
* [ ] `ls` — List files and directories
* [ ] `ls -la` — List all files with detailed information
* [ ] `cd` — Change the current directory
* [ ] `tree` — Display directories as a tree
* [ ] `clear` — Clear the terminal screen

## 02. Files and Folders

* [ ] `touch` — Create an empty file or update timestamps
* [ ] `mkdir` — Create directories
* [ ] `cp` — Copy files and directories
* [ ] `mv` — Move or rename files
* [ ] `rm` — Remove files or directories
* [ ] `rmdir` — Remove empty directories
* [ ] `file` — Identify a file's type
* [ ] `stat` — Display file or filesystem status

## 03. Read and Edit Files

* [ ] `cat` — Display or combine file contents
* [ ] `less` — Read files one screen at a time
* [ ] `head` — Display the beginning of a file
* [ ] `tail` — Display the end of a file
* [ ] `nano` — Edit files in a simple terminal editor
* [ ] `vim` — Edit files in a powerful modal editor
* [ ] `wc` — Count lines, words, and bytes
* [ ] `nl` — Display files with numbered lines

## 04. Search and Text Processing

* [ ] `find` — Search for files and directories
* [ ] `grep` — Search text using patterns
* [ ] `locate` — Find files using a filename database
* [ ] `which` — Locate an executable in `PATH`
* [ ] `whereis` — Locate a command's binary, source, and manual
* [ ] `sort` — Sort lines of text
* [ ] `uniq` — Find or remove adjacent duplicate lines
* [ ] `cut` — Extract sections from lines
* [ ] `tr` — Translate or delete characters
* [ ] `sed` — Edit or transform text streams
* [ ] `awk` — Process structured text and fields
* [ ] `xargs` — Build command arguments from input

## 05. Permissions and Users

* [ ] `whoami` — Display the current username
* [ ] `id` — Display user and group IDs
* [ ] `sudo` — Run commands with elevated privileges
* [ ] `chmod` — Change file permissions
* [ ] `chown` — Change file ownership
* [ ] `chgrp` — Change group ownership
* [ ] `groups` — Display group memberships
* [ ] `passwd` — Change a user's password
* [ ] `su` — Switch to another user

## 06. Processes and System

* [ ] `ps` — Display process information
* [ ] `top` — Monitor processes and system activity
* [ ] `htop` — Interactively monitor processes
* [ ] `pgrep` — Find processes by name or attributes
* [ ] `kill` — Send a signal to a process
* [ ] `pkill` — Send signals to processes by name or pattern
* [ ] `jobs` — List jobs in the current shell
* [ ] `bg` — Resume a job in the background
* [ ] `fg` — Bring a job to the foreground
* [ ] `free` — Display memory usage
* [ ] `uptime` — Show system uptime and load averages
* [ ] `uname` — Display system information
* [ ] `hostname` — Display or configure the system hostname
* [ ] `lscpu` — Display CPU information
* [ ] `lsblk` — List block devices
* [ ] `df` — Display filesystem disk space usage
* [ ] `du` — Estimate file and directory space usage

## 07. Packages and Software

* [ ] `apt` — Manage packages on Debian-based systems
* [ ] `apt update` — Refresh available package information
* [ ] `apt install` — Install packages
* [ ] `apt remove` — Remove installed packages
* [ ] `dpkg` — Manage Debian packages directly
* [ ] `snap` — Install and manage Snap packages

## 08. Networking

* [ ] `ip` — Inspect and configure network interfaces and routes
* [ ] `ping` — Test network reachability
* [ ] `curl` — Transfer data to or from URLs
* [ ] `wget` — Download files from the web
* [ ] `ssh` — Connect to remote systems securely
* [ ] `scp` — Copy files over SSH
* [ ] `ss` — Inspect sockets and network connections
* [ ] `dig` — Query DNS records
* [ ] `nslookup` — Query DNS information
* [ ] `traceroute` — Trace the route to a destination

## 09. Archives and Storage

* [ ] `tar` — Create or extract archives
* [ ] `gzip` — Compress files
* [ ] `gunzip` — Decompress gzip files
* [ ] `zip` — Create ZIP archives
* [ ] `unzip` — Extract ZIP archives
* [ ] `mount` — Attach a filesystem to the directory tree
* [ ] `umount` — Detach a mounted filesystem
* [ ] `fdisk` — Inspect or manage disk partitions

## 10. Redirection and Pipes

* [ ] `echo` — Print text or variable values
* [ ] `printf` — Print formatted output
* [ ] `>` — Redirect output and overwrite a file
* [ ] `>>` — Append output to a file
* [ ] `<` — Read command input from a file
* [ ] `|` — Pass one command's output to another
* [ ] `tee` — Write output to a file and the terminal
* [ ] `2>` — Redirect standard error
* [ ] `/dev/null` — Discard output sent to it

## 11. Environment and Shell

* [ ] `echo $PATH` — Display executable search paths
* [ ] `env` — Display or run commands with environment variables
* [ ] `export` — Set environment variables for child processes
* [ ] `source` — Run a file in the current shell
* [ ] `alias` — Create command shortcuts
* [ ] `history` — Display command history
* [ ] `man` — Read command manuals
* [ ] `help` — Get help for shell built-ins
* [ ] `type` — Identify how a command is interpreted
* [ ] `exit` — Exit the current shell

## 12. System Logs and Services

* [ ] `systemctl` — Manage systemd services and units
* [ ] `journalctl` — Read systemd journal logs
* [ ] `dmesg` — Display kernel messages
* [ ] `service` — Manage services on compatible systems
* [ ] `crontab` — Schedule recurring commands
* [ ] `date` — Display or format the date and time
* [ ] `timedatectl` — Inspect or configure system time settings

## 13. Developer Tools

* [ ] `git` — Track changes with version control
* [ ] `python3` — Run Python programs
* [ ] `pip` — Install and manage Python packages
* [ ] `python3 -m venv` — Create a Python virtual environment
* [ ] `ssh-keygen` — Generate SSH keys
* [ ] `make` — Run tasks defined in Makefiles
* [ ] `gcc` — Compile C programs
* [ ] `docker` — Build and run containers

## 14. Advanced Administration

* [ ] `rsync` — Synchronize files and directories
* [ ] `ln` — Create hard or symbolic links
* [ ] `readlink` — Display or resolve symbolic links
* [ ] `chmod -R` — Change permissions recursively
* [ ] `chown -R` — Change ownership recursively
* [ ] `lsof` — List open files and their associated processes
* [ ] `strace` — Trace system calls and signals
* [ ] `watch` — Repeat a command at regular intervals
* [ ] `xclip` — Access the clipboard from the command line (X11)
* [ ] `tmux` — Manage persistent terminal sessions

---

## Progress Tracker

* **Total checklist items:** 120
* **Completed:** 0
* **Goal:** Learn each command, understand its options, and practice it with real examples.

## Learning Resources

* [Linux man pages](https://man7.org/linux/man-pages/)
* [GNU Coreutils Manual](https://www.gnu.org/software/coreutils/manual/)
* [The Linux Command Line](https://linuxcommand.org/tlcl.php)
* [Ubuntu Documentation](https://help.ubuntu.com/)
* [ArchWiki](https://wiki.archlinux.org/)

---

## Practice Tips

* Practice in a test directory or virtual machine.
* Use `man command` or `command --help` to explore options.
* Be careful with destructive commands such as `rm`, `fdisk`, `chmod -R`, and `chown -R`.
* Some commands require installation or administrator privileges and may vary across Linux distributions.
* Check off each item only after you've practiced it.

⭐ **Keep learning, keep practicing, and build your Linux skills one command at a time!**
