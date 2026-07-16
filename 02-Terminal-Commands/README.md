# Terminal Commands 🖥️

Terminal commands are used to interact with the Linux operating system through the command-line interface (CLI).

---

# 1. pwd

Displays the current working directory.

### Syntax

```bash
pwd
```

### Example

```bash
/home/vishnu/Documents
```

---

# 2. ls

Lists files and directories.

### Basic

```bash
ls
```

### List hidden files

```bash
ls -a
```

The `-a` option displays all files, including hidden files (those starting with `.`).

Example:

```
.
..
.bashrc
.profile
Documents
Downloads
```

### Long listing format

```bash
ls -l
```

Displays:

- File permissions
- Number of links
- Owner
- Group
- File size
- Date & time
- File name

Example:

```
drwxr-xr-x 2 vishnu users 4096 Jul 15 Documents
```

### Human-readable file sizes

```bash
ls -lh
```

Example:

```
4.2K notes.txt
2.1M project.zip
```

### Show hidden files in long format

```bash
ls -la
```

or

```bash
ls -al
```

Displays hidden files with detailed information.

---

# 3. cd

Changes the current directory.

### Go to a folder

```bash
cd Documents
```

### Go back one directory

```bash
cd ..
```

### Go to home directory

```bash
cd
```

or

```bash
cd ~
```

### Go to previous directory

```bash
cd -
```

---

# 4. mkdir

Creates a new directory.

### Syntax

```bash
mkdir Linux
```

Creates a folder named **Linux**.

### Create multiple directories

```bash
mkdir Projects Notes Scripts
```

### Create nested directories

```bash
mkdir -p Linux/Basics/Commands
```

---

# 5. touch

Creates an empty file.

### Syntax

```bash
touch notes.txt
```

### Create multiple files

```bash
touch file1.txt file2.txt file3.txt
```

### Update timestamp

```bash
touch notes.txt
```

If the file already exists, its modification time is updated.

---

# Quick Summary

| Command | Description |
|---------|-------------|
| `pwd` | Show current directory |
| `ls` | List files |
| `ls -a` | Show hidden files |
| `ls -l` | Detailed list |
| `ls -lh` | Human-readable file sizes |
| `ls -la` | Hidden files + detailed list |
| `cd folder` | Change directory |
| `cd ..` | Move one level up |
| `cd ~` | Home directory |
| `cd -` | Previous directory |
| `mkdir` | Create directory |
| `mkdir -p` | Create nested directories |
| `touch` | Create empty file |

---

# 6. cp

Copies files and directories.

### Syntax

```bash
cp source destination
```

### Copy a file

```bash
cp notes.txt Backup/
```

Copies `notes.txt` to the **Backup** directory.

### Copy and rename a file

```bash
cp notes.txt notes_backup.txt
```

Creates a copy of the file with a new name.

### Copy a directory

```bash
cp -r Project Backup
```

The `-r` option copies directories recursively.

---

# 7. mv

Moves or renames files and directories.

### Move a file

```bash
mv notes.txt Documents/
```

Moves `notes.txt` into the **Documents** folder.

### Rename a file

```bash
mv oldname.txt newname.txt
```

Renames the file without changing its contents.

### Move a directory

```bash
mv Project Backup/
```

Moves the **Project** folder into the **Backup** directory.

---

# 8. rm

Removes files and directories.

### Delete a file

```bash
rm notes.txt
```

Deletes the specified file.

### Delete multiple files

```bash
rm file1.txt file2.txt file3.txt
```

Deletes multiple files at once.

### Delete a directory

```bash
rm -r Folder
```

The `-r` option removes directories recursively.

### Force delete

```bash
rm -rf Folder
```

The `-f` option forces deletion without confirmation.

> ⚠️ Be careful when using `rm -rf` because deleted files cannot be recovered easily.

---

# 9. rmdir

Removes an empty directory.

### Syntax

```bash
rmdir EmptyFolder
```

Deletes the directory only if it is empty.

---

# 10. cat

Displays the contents of a file.

### Syntax

```bash
cat notes.txt
```

Displays the entire contents of the file.

### Display multiple files

```bash
cat file1.txt file2.txt
```

Shows the contents of both files.

### Create a file

```bash
cat > notes.txt
```

Type your text and press **Ctrl + D** to save.

---

# 11. clear

Clears the terminal screen.

### Syntax

```bash
clear
```

Removes all previous commands from the terminal screen.

### Shortcut

```text
Ctrl + L
```

Clears the screen without typing the command.

---

# 12. echo

Displays text or writes text into a file.

### Display text

```bash
echo "Hello Linux"
```

Outputs the text on the terminal.

### Write text to a file

```bash
echo "Linux Basics" > notes.txt
```

Creates or overwrites the file.

### Append text to a file

```bash
echo "Shell Commands" >> notes.txt
```

Adds text to the end of the file without deleting existing content.

---

# 13. whoami

Displays the current logged-in user.

### Syntax

```bash
whoami
```

### Example

```bash
vishnu
```

---

# 14. hostname

Displays the system hostname.

### Syntax

```bash
hostname
```

### Example

```bash
ubuntu
```

---

# 15. uname

Displays system information.

### Display kernel name

```bash
uname
```

### Display kernel version

```bash
uname -r
```

### Display all system information

```bash
uname -a
```

Shows kernel name, version, architecture, hostname, and more.

---

# Quick Summary

| Command | Description |
|---------|-------------|
| `cp` | Copy files or directories |
| `mv` | Move or rename files |
| `rm` | Delete files |
| `rm -r` | Delete directories |
| `rm -rf` | Force delete directories |
| `rmdir` | Delete empty directory |
| `cat` | Display file contents |
| `clear` | Clear terminal screen |
| `echo` | Display or write text |
| `whoami` | Show current user |
| `hostname` | Show system hostname |
| `uname` | Show system information |
| `uname -a` | Show complete system information |
