# Linux-notes

## Navigation commands
```bash
ls (list storage)
ls / (root directory contents)
clear (clear the screen)
ls -l (long listing format)
ls -l / (long listing format in root directory)
pwd (print working directory)
cd (change directory)
```

## Basic file editing
```bash
touch (create empty files or update timestamps)
nano (simple command-line text editor)
cat (concatenate and display file content)
which (show the full path of a command)
vim (powerful text editor in terminal)
```

## Moving and renaming files
```bash
cp (copy file)
diff (difference)
rm (remove file)
mkdir (make directory)
mv (move file)
```

## Understanding Permissions
```bash
chmod (change mode)
(r - read w - write x - execute)
(u - user g - group o - others a - all)
```

## Checking Resource Usage
```bash
free (display free and used memory)
free -m (display memory in megabytes)
df (display disk space usage)
df -h (display disk space in human-readable format)
df -i (display inode usage instead of block usage)
htop (interactive process viewer and system monitor)
uptime (show how long the system has been running)
```

## Intro to Package Management on Debian-based Distributions
```bash
sudo apt update (update package lists from repositories)
sudo apt upgrade (upgrade all available packages)
sudo apt dist-upgrade (upgrade packages with smart dependency handling)
sudo apt install (install a specific package)
sudo apt search (search for a package description)
sudo apt remove (remove a package keeping configuration files)
sudo apt autoremove (automatically remove unused dependency packages)
```
## Managing systemd Units
```bash
systemctl status (show the current status of a service)
systemctl disable (prevent a service from starting automatically at boot)
systemctl stop (stop a running service immediately)
systemctl enable (configure a service to start automatically at boot)
systemctl start (start a service immediately)
systemctl restart (stop and then start a service again)
```
## Viewing Logs
```bash
