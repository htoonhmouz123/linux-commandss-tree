# 🐧 Linux Commands Reference Tree

<div align="center">

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Status](https://img.shields.io/badge/Commands-13-blue?style=for-the-badge)

A structured directory tree documenting essential Linux file and directory commands — organized by category, with descriptions, syntax, and usage examples for each command.

</div>

---

## 📁 Directory Structure

```
u1241706_sec1_prj1/
└── files_dirs/
    ├── 🗜️ Compress/
    │   ├── tar
    │   └── zip
    ├── 🔨 create_destroy/
    │   ├── touch
    │   ├── mkdir
    │   ├── rm
    │   ├── rmdir
    │   └── ln
    ├── 👁️ display/
    │   ├── cat
    │   ├── less
    │   └── more
    └── ✏️ manipulate/
        ├── cd
        ├── cp
        └── mv
```

---

## 📋 Commands Reference

### 🗜️ Compress

| Command | Syntax | Description |
|---------|--------|-------------|
| `tar` | `tar [options] [archive] [files]` | Creates or extracts an archive containing files and directories |
| `zip` | `zip [options] archive files` | Compresses files into a zip archive to save space |

**Examples:**
```bash
tar -cvf archive.tar file1 file2     # Create archive
tar -xvf archive.tar                 # Extract archive
zip myarchive.zip file1 file2        # Create zip
```

---

### 🔨 Create & Destroy

| Command | Syntax | Description |
|---------|--------|-------------|
| `touch` | `touch [options] filename` | Creates a new empty file or updates timestamp |
| `mkdir` | `mkdir [options] dirname` | Creates one or more new directories |
| `rm` | `rm [options] file` | Permanently removes files or directories |
| `rmdir` | `rmdir [options] dirname` | Removes empty directories |
| `ln` | `ln [options] source link` | Creates hard or symbolic links between files |

**Examples:**
```bash
touch newfile.txt                    # Create empty file
mkdir myfolder                       # Create directory
mkdir -p parent/child/grandchild     # Create nested directories
rm file.txt                          # Remove file
rm -r myfolder                       # Remove directory recursively
rmdir emptyfolder                    # Remove empty directory
ln -s target linkname                # Create symbolic link
```

---

### 👁️ Display

| Command | Syntax | Description |
|---------|--------|-------------|
| `cat` | `cat [options] file` | Displays entire file contents in the terminal |
| `less` | `less [options] file` | Views file content page by page — supports forward & backward navigation |
| `more` | `more [options] file` | Views file content one screen at a time — forward only |

**Examples:**
```bash
cat file.txt                         # Display file
cat file1 file2 > combined.txt       # Combine files
less largefile.txt                   # Page through file (q to quit)
more largefile.txt                   # Page through file
```

---

### ✏️ Manipulate

| Command | Syntax | Description |
|---------|--------|-------------|
| `cd` | `cd [directory]` | Changes the current working directory |
| `cp` | `cp [options] source destination` | Copies files or directories to another location |
| `mv` | `mv [options] source destination` | Moves or renames files and directories |

**Examples:**
```bash
cd /home/user/Documents              # Go to specific directory
cd ..                                # Go up one level
cd ~                                 # Go to home directory
cp file.txt backup.txt               # Copy file
cp -r folder/ backup_folder/        # Copy directory recursively
mv file.txt newname.txt              # Rename file
mv file.txt /home/user/              # Move file to directory
```

---

## 📄 File Format

Each command file in the tree follows this structure:

```
[Description of the command]

[Syntax]

[Usage examples]

[Author name]
[Student ID]
```

---

## ▶️ How to Use

```bash
# Clone the repository
git clone https://github.com/htoonhmouz123/linux-commands-tree.git
cd linux-commands-tree/u1241706_sec1_prj1/files_dirs

# Read any command reference
cat manipulate/cp
cat display/less
cat create_destroy/mkdir
cat Compress/tar
```

---

## 👩‍💻 Author

**Hatoon Hmouz** 
Computer Science Student @ Birzeit University  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hatoon-hmouz-28819333a)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/htoonhmouz123)

