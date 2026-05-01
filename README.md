# Bourne Again Shell (BASH)

A list of linux commands running on Linux Kernel Distro Ubuntu BASH.

## Changing the working directory
**Using absolute pathname**
```bash
cd /path/name
```

**To change the working directory to your home directory.**
```bash
cd 
```

**To change the working directory to the previous working directory**
```bash
cd -
```

## List command**
**To list files sorted by the file modification time**
```bash
ls -lt
```

**To reverse the sort**
```bash
ls -lt --reverse
```

## Files
**To create an empty file.**
```bash
touch filename.ext
```

## File Type
**To determine the file type (revealing extension of the file)**
```bash
file filename
```

**To open a file.**
```bash
xdg-open filename
```

**To close a file.**
```bash
pkill -f filename