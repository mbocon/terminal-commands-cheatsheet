# Terminal Commands Cheatsheet

**Note** This is not an exhaustive list of commands. If you have a command that you think should be added to this list, please submit a pull request. Some commands such as `brew` require installation first. [Get Homebrew here](https://brew.sh/)

---

## Linux Cheatsheet

| Command | Description |
|---------|-------------|
| `addgroup` | Adds a group to the system. |
| `apropos <keyword>` | Searches through man pages' descriptions for instances of a given keyword. |
| `apt` | High-level package management command-line utility. |
| `aptitude` | Alternative to apt. |
| `awk` | Pattern scanning and processing language.|
| `bash` or `zsh`  | This command will allow you to switch to a different shell. For example, if you type `bash`, your computer will switch to the bash shell.  |
| `bg` | Puts a process into background. |
| `brew cleanup`| This command will allow you to clean up Homebrew. |
| `brew doctor` | This command will allow you to diagnose problems with Homebrew.  |
| `brew install <package>`  | This command will allow you to install a package. For example, if you type `brew install wget`, your computer will install the wget package. |
| `brew list`   | This command will allow you to view all installed packages. |
| `brew uninstall <package>` | This command will allow you to uninstall a package. For example, if you type `brew uninstall wget`, your computer will uninstall the wget package. |
| `brew update` | This command will allow you to update Homebrew. |
| `brew upgrade`| This command will allow you to upgrade all installed packages. |
| `caffeinate` | This command will prevent your computer from going to sleep. For example, if you type `caffeinate`, your computer will stay awake until you type `control + c`.  |
| `cat` | Concatenate and print files.|
| `cd` | This command will allow you to change directories. For example, if you type `cd Desktop`, your computer will change to the Desktop directory.     |
| `chown` | Changes the owner and group of a file or directory. |
| `chmod` | Changes permission of a file or directory. |
| `clear` | Clears the terminal. |
| `column` | Command-line based utility that formats its input into multiple columns. |
| `cp` | Copy files or directories. |
| `curl` | Command-line utility to transfer data from or to a server. |
| `curl <website>`    | This command will allow you to download a file from a website. For example, if you type `curl https//www.google.com/`, your computer will download the index.html file from the google.com website.   |
| `curl wttr.in`| This command will allow you to view the weather forecast for your location. For example, if you type `curl wttr.in/hawaii`, your computer will show you the weather in Hawaii  |
| `cut` | Removes sections from each line of files. |
| `defaults` | This command will allow you to change the default settings for your computer. For example, if you type `defaults write com.apple.finder AppleShowAllFiles YES`, your computer will show hidden files in Finder. |
| `delgroup` | Removes a group from the system. |
| `dig <website>` | This command will allow you to query DNS records for a website. For example, if you type `dig google.com`, your computer will query DNS records for google.com.  |  
| `df` | Shows disk usage. |
| `df -h`  | This command will allow you to print the disk usage. |
| `diff` | Compares files line by line. |
| `diff <filename1> <filename2>` | This command will allow you to compare two files. For example, if you type `diff file1.txt file2.txt`, your computer will show you the differences between the file1.txt and file2.txt files.  |
| `dpkg` | Install, remove and configure Debian-based packages. |
| `env` | Prints environment or sets and executes a command. |
| `fg` | Puts a process into the foreground. |
| `find` | Searches for files in a directory hierarchy. |
| `find ~/ -name <filename>` | This command will allow you to find a file. For example, if you type `find ~/ -name file.txt`, your computer will find the file.txt file. |
| `gem` | Standard package manager for Ruby. |
| `git` | Revision control system command-line utility. |
| `grep` | Searches for specific results that contain given patterns. |
| `head` | Prints the first ten lines of STDOUT or a file. |
| `history`  | This command will allow you to view the history of commands you have typed. |
| `hostname` | Sets or prints the name of the current host system. |
| `id` | Returns users identity. |
| `ifconfig` | The ifconfig utility is used to assign or view an address to a network interface and/or configure network interface parameters. |
| `ip` | Ip is a utility to show or manipulate routing, network devices, interfaces, and tunnels. |
| `journalctl` | Query the systemd journal. |
| `jobs` | Lists all processes that are running in the background. |
| `kill` | Sends a signal to a process.|
| `kill -9 <pid>`  | This command will allow you to kill a process. For example, if you type `kill -9 1234`, your computer will kill the process with the PID 1234. |
| `less` | An alternative to more with more features. |
| `locate` | Uses the locale database to find contents on the system.|
| `ls` | Lists directory contents. |
| `lsblk` | Lists block devices. |
| `lsof` | Lists opened files. |
| `lsusb` | Lists USB devices. |
| `lspci` | Lists PCI devices.  |
| `man <tool>` | Opens man pages for the specified tool. |
| `mkdir` | Creates a directory. |
| `more` | Pager that is used to read STDOUT or files.|
| `mv` | This command will allow you to move a file or directory. For example, if you type `mv file.txt ~/Desktop`, your computer will move the file.txt file to your Desktop directory. |
| `nano` | Terminal based text editor. |
| `netstat` | Shows network status. |
| `netstat -tulpn` | Shows network status and process information. |
| `nmap` | Network exploration tool and security scanner. |
| `open` | This command will allow you to open a file or directory. For example, if you type `open file.txt`, your computer will open the file.txt file in the default application. |
| `passwd` | Changes user password. |
| `pbcopy` | This command will copy whatever you type after it to your clipboard. For example, if you type `pbcopy hello`, your computer will copy "hello" to your clipboard. |
| `pip`  | Standard package manager for Python. |
| `ping` | Pings a host. |
| `ping -c 4` | Pings a host 4 times. |
| `pkill <process>`| This command will allow you to kill all processes that match a string. For example, if you type `pkill firefox`, your computer will kill all processes that match the string "firefox".  |
| `ps` | Shows process status. |
| `ps -ax` | This command will allow you to view all running processes. |
| `ps -ax  grep <process>` | This command will allow you to view all running processes that match a string. For example, if you type `ps -ax | grep firefox`, your computer will show you all running processes that match the string "firefox". |
| `pwd` | Returns working directory name. |
| `python3 -m http.server` | Starts a Python3 web server on TCP port 8000. |
| `say` | This command will make your computer speak whatever you type after it.|
| `qlmanage -p <filename>` | This command will allow you to preview a file. For example, if you type `qlmanage -p file.txt`, your computer will show you a preview of the file.txt file.  |
| `security find-generic-password -wa <website>` | This command will show you the password for a website that you have saved in your keychain. For example, if you type `security find-generic-password -wa github.com`, your computer will show you the password for your GitHub account. |
| `sed` | A stream editor for filtering and transforming text. |
| `snap` | Install, remove and configure snap packages. |
| `sort` | Sorts the contents of STDOUT or a file. |
| `ss` | Another utility to investigate sockets. |
| `su` | The su utility requests appropriate user credentials via PAM and switches to that user ID (the default user is the superuser). A shell is then executed. |
| `sudo` | Executes a command as another user. |
| `sudo killall -HUP mDNSResponder` | This command will allow you to restart the DNS resolver.|
| `sudo nano /etc/pam.d/sudo`  | This command will allow you to edit the sudoers file. For example, if you type `sudo nano /etc/pam.d/sudo`, your computer will open the sudoers file in the nano text editor. |
| `sudo spctl --master-disable`  | This command will allow you to disable Gatekeeper. |
| `systemctl` | Command-line based service and systemd control manager
| `tail` | Prints the last ten lines of STDOUT or a file. |
|`<tool> -h`   | Prints the help page of the tool.  |
| `top` | This command will allow you to view all running processes in real time. Use `control + c` to stop    |
| `top -o rsize` | This command will allow you to view all running processes in real time, sorted by memory usage. Use `control + c` to stop   |
| `touch` | Creates an empty file. |
| `tr` | Replaces certain characters.|
| `traceroute <website>`  | This command will allow you to trace the route to a website. For example, if you type `traceroute google.com`, your computer will trace the route to google.com. |
| `tree` | Lists the contents of a directory recursively. |
| `uname` | Prints operating system name. |
| `updatedb` | Updates the locale database for existing contents on the system. |
| `uptime`  | This command will allow you to view the uptime of your computer. For example, if you type `uptime`, your computer will show you the uptime of your computer.  |
| `useradd` | Creates a new user or update default new user information. |
| `userdel` | Deletes a user account and related files. |
| `usermod` | Modifies a user account. |
| `vim <filename>` | This command will allow you to edit a file. For example, if you type `vim file.txt`, your computer will open the file.txt file in the vim text editor. |
| `wait` | Waits for a process to complete. |
| `wc` | Prints newline, word, and byte counts for a given input.|
| `wget` | An alternative to curl that downloads files from FTP or HTTP(s) server. |
| `which` | Returns the path to a file or link. |
| `who` | Displays who is logged in. |
| `whoami` | Displays current username. |
| `xargs` | A command that reads items from standard input and executes a command. |
| `yes` | Outputs a string repeatedly until killed. |