# Day 2 — Linux File Commands

**Date:** 02 September 2026
**Track:** Foundation

---

##  Objectives

* Learn essential Linux file commands
* Practice copying, moving, renaming and deleting files
* Learn different ways to read file contents
* Understand file content redirection

---

##  Commands Learned

| Command   | Purpose                               |
| --------- | ------------------------------------- |
| `pwd`     | Show current directory                |
| `ls`      | List files and folders                |
| `cd`      | Change directory                      |
| `cd ..`   | Move to parent directory              |
| `mkdir`   | Create a directory                    |
| `touch`   | Create an empty file                  |
| `cp`      | Copy a file or folder                 |
| `mv`      | Move or rename a file or folder       |
| `rm`      | Delete a file                         |
| `rm -r`   | Delete a folder and its contents      |
| `cat`     | Display file contents                 |
| `less`    | Read a file using a scrollable viewer |
| `head`    | Show the beginning of a file          |
| `tail`    | Show the end of a file                |
| `echo`    | Print text                            |
| `>`       | Write or replace file content         |
| `>>`      | Append content to a file              |
| `history` | Show previously executed commands     |

---

##  Hands-on Practice

### 1. File Creation

```bash
mkdir day2-practice
cd day2-practice
touch notes.txt
```

### 2. Writing and Appending Content

```bash
echo "Linux Day 2" > notes.txt
echo "Learning Linux commands" >> notes.txt
```

### 3. Copying and Moving Files

```bash
cp notes.txt backup.txt
mv backup.txt renamed.txt
mkdir backup
mv renamed.txt backup/
```

### 4. Reading Files

```bash
cat notes.txt
less notes.txt
head -n 5 notes.txt
tail -n 5 notes.txt
```

Press `q` to exit `less`.

### 5. Deleting Files and Folders

```bash
rm backup/renamed.txt
rm -r backup
```

---

##  Key Learnings

* `cp` creates a copy while keeping the original file.
* `mv` moves or renames a file.
* `rm` deletes a file.
* `rm -r` deletes a directory and its contents.
* `cat` displays file contents directly in the terminal.
* `less` provides a scrollable view for reading files.
* `head` shows the beginning of a file.
* `tail` shows the end of a file.
* `>` replaces existing file content.
* `>>` appends content without removing existing content.

---

##  Day 2 Status

**COMPLETED**

**Focus:** Linux File Commands
**Practical:** Completed
**Assessment:** 10/10
**GitHub Log:** Completed
