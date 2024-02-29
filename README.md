# System Administration Tasks

## 1. Creating Files and Directories

### Creating "admin_assignment" Directory

```bash
mkdir ~/admin_assignment && cd ~/admin_assignment
```

### Creating Files Inside "admin_assignment" Directory

```bash
touch file1.txt
touch file2.txt
touch file3.txt
touch important_file.txt
```

## 2. Creating Users

### Creating User "azeez"

```bash
sudo useradd --create-home azeez
sudo usermod -c 'Azeez - Linux Admin' azeez
sudo passwd azeez
```

### Creating User "ruth"

```bash
sudo useradd --create-home ruth
sudo usermod -c 'Ruth - Linux Admin' ruth
sudo passwd ruth
```

### Verifying Home Directories and User Information

```bash
ls -la /home
```

## 3. Creating Groups

### Creating "collab_group" and Assigning GID

```bash
sudo groupadd --gid 840 collab_group
```

### Adding Users to "collab_group"

```bash
sudo usermod -a -G collab_group azeez
sudo usermod -a -G collab_group ruth
```

---

# Readme

## System Administration Tasks

This document outlines the steps to perform various system administration tasks. Follow the instructions carefully for creating directories, files, users, and groups.

### 1. Creating Files and Directories

#### Creating "admin_assignment" Directory

```bash
mkdir ~/admin_assignment && cd ~/admin_assignment
```

#### Creating Files Inside "admin_assignment" Directory

```bash
touch file1.txt
touch file2.txt
touch file3.txt
touch important_file.txt
```

### 2. Creating Users

#### Creating User "azeez"

```bash
sudo useradd --create-home azeez
sudo usermod -c 'Azeez - Linux Admin' azeez
sudo passwd azeez
```

#### Creating User "ruth"

```bash
sudo useradd --create-home ruth
sudo usermod -c 'Ruth - Linux Admin' ruth
sudo passwd ruth
```

#### Verifying Home Directories and User Information

```bash
ls -la /home
```

### 3. Creating Groups

#### Creating "collab_group" and Assigning GID

```bash
sudo groupadd --gid 840 collab_group
```

#### Adding Users to "collab_group"

```bash
sudo usermod -a -G collab_group azeez
sudo usermod -a -G collab_group ruth
```

Feel free to reach out for any clarification or assistance.
