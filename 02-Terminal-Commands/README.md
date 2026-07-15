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
