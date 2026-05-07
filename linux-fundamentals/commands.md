# Linux Fundamentals Notes

## Introduction

While learning Linux fundamentals, I practiced different basic commands used for navigation, file management, networking, and permissions. At first using the terminal felt confusing, but after regular practice I became more comfortable with it.

---

# Basic Linux Commands

## pwd
Shows the current working directory.

Example:
pwd

---

## ls
Lists files and folders.

Examples:
ls
ls -la

I learned that `ls -la` also shows hidden files.

---

## cd
Used to move between directories.

Examples:
cd Desktop
cd ..
cd ~

At first I mixed up `cd ..` and `cd ~`, but later understood the difference.

---

## mkdir
Creates a new folder.

Example:
mkdir testfolder

---

## touch
Creates an empty file.

Example:
touch notes.txt

---

## cp
Copies files.

Example:
cp file.txt backup.txt

---

## mv
Moves or renames files.

Examples:
mv old.txt new.txt

---

## rm
Deletes files or folders.

Examples:
rm file.txt
rm -r foldername

Need to be careful while using this command.

---

# Viewing File Content

## cat
Displays file content.

Example:
cat file.txt

---

## head
Shows the first lines of a file.

Example:
head file.txt

---

## tail
Shows the last lines of a file.

Example:
tail file.txt

Useful while checking logs.

---

# Networking Commands

## ping
Checks network connectivity.

Example:
ping google.com

---

## ifconfig / ip a
Displays network interface information.

I noticed newer Linux systems mostly use `ip a`.

---

## netstat
Shows active connections and listening ports.

Example:
netstat -tulnp

---

# Linux Permissions

Linux permissions control who can access or modify files.

## Permission Types

- r → Read
- w → Write
- x → Execute

---

## Viewing Permissions

Command:
ls -l

Example:
-rwxr-xr--

This part was slightly confusing at first, but after practice I understood how permissions are assigned.

---

## chmod
Changes file permissions.

Examples:
chmod 755 script.sh
chmod +x script.sh

---

## chown
Changes ownership of files.

Example:
sudo chown user:user file.txt

---

## sudo
Runs commands with administrative privileges.

Example:
sudo apt update

I learned that sudo should be used carefully because it gives higher privileges.

---

# Important Directories

| Directory | Purpose |
|---|---|
| /home | User files |
| /etc | Configuration files |
| /var | Logs and variable data |
| /tmp | Temporary files |

---

# What I Learned

- Linux is heavily command-line based.
- Small commands can perform powerful tasks.
- Permissions are important for system security.
- Practice is necessary to remember commands properly.

---

# Cybersecurity Relevance

Linux knowledge is very useful in cybersecurity because many servers, tools, and penetration testing environments are Linux-based.
