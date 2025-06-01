# 📁 Folder (Directory) Commands in Linux Terminal

## 🔍 Show Current Directory
```bash
pwd
````

> Print working directory — shows where you are now.

---

## 📂 List Files and Folders

```bash
ls
```

> List files and folders in current directory.

```bash
ls -l
```

> List with details (permissions, size, date).

```bash
ls -a
```

> List including hidden files/folders (those starting with `.`).

---

## ➕ Create Folder (Directory)

```bash
mkdir folder_name
```

> Create a new folder.

```bash
mkdir -p path/to/folder
```

> Create nested folders (creates intermediate folders if they don’t exist).

---

## 🗑️ Delete Folder

```bash
rmdir folder_name
```

> Delete empty folder only.

```bash
rm -r folder_name
```

> Delete folder and everything inside (recursive).

```bash
rm -rf folder_name
```

> Force delete folder and contents without prompt (dangerous! ⚠️).

---

## ✏️ Rename or Move Folder

```bash
mv old_folder_name new_folder_name
```

> Rename folder or move it to a new location.

---

## 📥 Change Directory (Navigate)

```bash
cd folder_name
```

> Enter folder.

```bash
cd ..
```

> Go up one directory (parent folder).

```bash
cd ~
```

> Go to your home directory.

```bash
cd -
```

> Go to previous directory you were in.

---

## 🧹 Remove All Files Inside Folder (Keep Folder)

```bash
rm -r folder_name/*
```

> Delete all files and folders inside, but keep the main folder.

---

## 📄 Create Empty File Inside Folder

```bash
touch folder_name/file.txt
```

> Create an empty file inside a folder.

---

## 🌟 Extra Tips

* Use `ls -lh` for human-readable file sizes.
* Use `tree` (if installed) to see folder structure visually.
* Use tab completion to auto-complete folder/file names.
* Combine commands: `mkdir new_folder && cd new_folder` to create and enter immediately.

---

# 📋 Quick Reference Table

| Action                   | Command                      | Emoji |
| ------------------------ | ---------------------------- | ----- |
| Show current folder      | `pwd`                        | 📍    |
| List folder contents     | `ls` / `ls -l` / `ls -a`     | 📋    |
| Create folder            | `mkdir folder_name`          | ➕     |
| Create nested folders    | `mkdir -p path/to/folder`    | 🏗️   |
| Delete empty folder      | `rmdir folder_name`          | 🗑️   |
| Delete folder + content  | `rm -r folder_name`          | ⚠️    |
| Force delete folder      | `rm -rf folder_name`         | 💥    |
| Rename/move folder       | `mv old_name new_name`       | ✏️    |
| Enter folder             | `cd folder_name`             | 🚪    |
| Go up one folder         | `cd ..`                      | 🔙    |
| Go home folder           | `cd ~`                       | 🏠    |
| Go previous folder       | `cd -`                       | 🔄    |
| Remove all inside folder | `rm -r folder_name/*`        | 🧹    |
| Create empty file        | `touch folder_name/file.txt` | 📄    |

---
😊🚀

