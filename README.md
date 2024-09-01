# Linux Commands Version SDE1
## A file containing a comprehensive list of Linux commands used in Software Engineering, <br/>including their usage and examples

----------------------------
## Index
1. File and Directory Management
2. File Viewing and Editing
3. File Permissions
4. System Information
5. Networking
6. Process Management
7. Package Management
8. Git Commands
9. Miscellaneous

----------------------------
## File and Directory Management

### `ls`
- **Use**: List directory contents.
- **Example**: `ls -l` (List files with details)

### `cd`
- **Use**: Change directory.
- **Example**: `cd /path/to/directory`

### `pwd`
- **Use**: Print working directory.
- **Example**: `pwd` (Displays the current directory path)

### `cp`
- **Use**: Copy files or directories.
- **Example**: `cp source.txt destination.txt` (Copy a file)

### `mv`
- **Use**: Move or rename files or directories.
- **Example**: `mv oldname.txt newname.txt` (Rename a file)

### `rm`
- **Use**: Remove files or directories.
- **Example**: `rm file.txt` (Delete a file)

### `mkdir`
- **Use**: Create directories.
- **Example**: `mkdir new_directory` (Create a new directory)

### `rmdir`
- **Use**: Remove empty directories.
- **Example**: `rmdir empty_directory`

### `find`
- **Use**: Search for files in a directory hierarchy.
- **Example**: `find /path -name filename.txt` (Find a file named `filename.txt`)

### `touch`
- **Use**: Create an empty file or update the timestamp of an existing file.
- **Example**: `touch newfile.txt`

----------------------------
## File Viewing and Editing

### `cat`
- **Use**: Concatenate and display file content.
- **Example**: `cat file.txt`

### `less`
- **Use**: View file content interactively.
- **Example**: `less file.txt`

### `more`
- **Use**: View file content with pagination.
- **Example**: `more file.txt`

### `head`
- **Use**: Display the beginning of a file.
- **Example**: `head -n 10 file.txt` (Show the first 10 lines)

### `tail`
- **Use**: Display the end of a file.
- **Example**: `tail -n 10 file.txt` (Show the last 10 lines)

### `nano`
- **Use**: Simple text editor.
- **Example**: `nano file.txt`

### `vim`
- **Use**: Advanced text editor.
- **Example**: `vim file.txt`

----------------------------
## File Permissions

### `chmod`
- **Use**: Change file permissions.
- **Example**: `chmod 755 script.sh` (Set read, write, and execute permissions for owner, read and execute for others)

### `chown`
- **Use**: Change file owner and group.
- **Example**: `chown user:group file.txt`

### `chgrp`
- **Use**: Change group ownership of a file.
- **Example**: `chgrp group file.txt`

----------------------------
## System Information

### `top`
- **Use**: Display system processes.
- **Example**: `top`

### `htop`
- **Use**: Interactive process viewer (requires installation).
- **Example**: `htop`

### `df`
- **Use**: Display disk space usage.
- **Example**: `df -h` (Show disk usage in human-readable format)

### `du`
- **Use**: Display disk usage of files and directories.
- **Example**: `du -sh directory` (Show size of a directory)

### `free`
- **Use**: Display memory usage.
- **Example**: `free -h` (Show memory usage in human-readable format)

### `uname`
- **Use**: Display system information.
- **Example**: `uname -a` (Show all system information)

----------------------------
## Networking

### `ping`
- **Use**: Check network connectivity.
- **Example**: `ping google.com`

### `ifconfig`
- **Use**: Configure network interfaces (deprecated, use `ip` instead).
- **Example**: `ifconfig`

### `ip`
- **Use**: Show and manipulate routing, devices, and tunnels.
- **Example**: `ip addr show` (Show IP addresses)

### `netstat`
- **Use**: Network statistics and connections.
- **Example**: `netstat -tuln` (Show listening ports)

### `curl`
- **Use**: Transfer data from or to a server.
- **Example**: `curl http://example.com`

### `wget`
- **Use**: Download files from the web.
- **Example**: `wget http://example.com/file.txt`

----------------------------
## Process Management

### `ps`
- **Use**: Display information about active processes.
- **Example**: `ps aux` (Show all processes)

### `kill`
- **Use**: Send signals to processes.
- **Example**: `kill -9 1234` (Terminate process with PID 1234)

### `pkill`
- **Use**: Kill processes by name.
- **Example**: `pkill process_name`

### `jobs`
- **Use**: List active jobs.
- **Example**: `jobs`

### `bg`
- **Use**: Resume a suspended job in the background.
- **Example**: `bg %1`

### `fg`
- **Use**: Bring a background job to the foreground.
- **Example**: `fg %1`

----------------------------
## Package Management

### `apt-get`
- **Use**: Manage packages on Debian-based systems.
- **Example**: `sudo apt-get install package_name`

### `yum`
- **Use**: Manage packages on Red Hat-based systems.
- **Example**: `sudo yum install package_name`

### `dnf`
- **Use**: Manage packages on newer Red Hat-based systems.
- **Example**: `sudo dnf install package_name`

### `rpm`
- **Use**: Manage packages on RPM-based systems.
- **Example**: `sudo rpm -ivh package.rpm`

### `snap`
- **Use**: Install snap packages.
- **Example**: `sudo snap install package_name`

----------------------------
## Git Commands

### `git init`
- **Use**: Initialize a new Git repository.
- **Example**: `git init`

### `git clone`
- **Use**: Clone a repository.
- **Example**: `git clone https://github.com/user/repo.git`

### `git add`
- **Use**: Add files to staging area.
- **Example**: `git add file.txt`

### `git commit`
- **Use**: Commit changes to the repository.
- **Example**: `git commit -m "Commit message"`

### `git push`
- **Use**: Push changes to a remote repository.
- **Example**: `git push origin main`

### `git pull`
- **Use**: Fetch and merge changes from a remote repository.
- **Example**: `git pull origin main`

### `git status`
- **Use**: Show the working tree status.
- **Example**: `git status`

### `git branch`
- **Use**: List, create, or delete branches.
- **Example**: `git branch new-branch`

### `git merge`
- **Use**: Merge changes from another branch.
- **Example**: `git merge branch_name`

----------------------------
## Miscellaneous

### `echo`
- **Use**: Display a line of text.
- **Example**: `echo "Hello World"`

### `grep`
- **Use**: Search text using patterns.
- **Example**: `grep "search_term" file.txt`

### `sed`
- **Use**: Stream editor for filtering and transforming text.
- **Example**: `sed 's/old/new/g' file.txt` (Replace "old" with "new")

### `awk`
- **Use**: Pattern scanning and processing language.
- **Example**: `awk '{print $1}' file.txt` (Print the first column)

### `tar`
- **Use**: Archive files.
- **Example**: `tar -czvf archive.tar.gz directory/` (Create a compressed archive)

### `chmod`
- **Use**: Change file permissions.
- **Example**: `chmod 755 script.sh`

----------------------------
## Conclusion

This README provides a comprehensive list of essential Linux commands used in software engineering. For more detailed information, refer to the man pages (`man command_name`) or online documentation.

----------------------------
## Authors
- [@sbidwai](https://github.com/sbidwaibing)
  <br/>```Please feel free to contribute```

----------------------------
## Acknowledgements

 - [Official Doc](https://linuxcommand.org/lc3_man_page_index.php)

----------------------------
## License

[MIT License](https://choosealicense.com/licenses/mit/)
<br/>[Open Source Initiative](https://opensource.org/license/mit)

Copyright (c) 2024 SukrutB.

<p align="justify"> Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:</p>

<p align="justify">The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.</p>

<p align="justify">THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.</p>
