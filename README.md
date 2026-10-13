# as2-iib

## 1. About This Project

This project is part of the IIB assignment. It shows how to use Linux commands, create a Bash script, and manage files using Git. The project includes a script called `sysinfo.sh`. It shows basic information about the computer and its system.

## 2. Project Goals

The goals of this project are to:

- Learn how to use Linux commands.
- Create folders and manage file permissions.
- Write and run a Bash script.
- Use Git to save changes.
- Create a new branch and merge it into the main branch.
- Upload the project to GitHub.

## 3. Folder Structure

```text
DS1202-project/
├── docs/
├── logs/
├── scripts/
│   └── sysinfo.sh
└── README.md
```

## 4. System Information Script

The `sysinfo.sh` script shows information about the system, including:

- Username
- Computer name
- Date and time
- Operating system
- System uptime
- Disk usage

To run the script it is by using this command:

```bash
./scripts/sysinfo.sh
```

The script must have permission to run before it can be executed.

## 5. Git and GitHub

Git is used to track changes made to the project. GitHub is used to store the project online.

The steps include:

1. Create a Git repository.
2. Save the first version of the project.
3. Create a branch called `feature-logging`.
4. Add a logging feature.
5. Merge the branch into `main`.
6. Push the project to GitHub.

## 6. File Permissions

File permissions control who can read, change, or run a file.
The script can be given permission to run using:

chmod +x scripts/sysinfo.sh

DUE BY : 17/10/26
