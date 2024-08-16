# Advanced Linux Command Line Project

## Overview
This project demonstrates advanced proficiency in Linux command-line operations, shell scripting, and system administration tasks. It comprises solutions to various Linux-related challenges, showcasing skills in file manipulation, permissions management, networking, and core Linux concepts.

## Project Structure
The project consists of 10 shell script files, each addressing specific Linux command-line concepts:

1. `q01.sh`: File Renaming
2. `q02.sh`: File Copying with Relative and Absolute Paths
3. `q03.sh`: Understanding Output Redirection
4. `q04.sh`: File Linking Concepts
5. `q05.sh`: File Permissions in Octal Format
6. `q06.sh`: Network Configuration and Connectivity Testing
7. `q07.sh`: Directory Permissions Explained
8. `q08.sh`: File Search Utilities Comparison
9. `q09.sh`: Script for Counting Executable Files
10. `q10.sh`: Advanced Script for Directory Operations and Archiving

## Key Concepts Demonstrated

### 1. File and Directory Operations
- Renaming and copying files using `mv` and `cp` commands
- Understanding and utilizing relative and absolute paths
- Creating directories and manipulating file structures

### 2. Input/Output and Redirection
- Differentiating between `>` and `>>` operators for output redirection
- Understanding the implications of each redirection operator

### 3. File Permissions and Links
- Converting symbolic notation to octal format for the `chmod` command
- Explaining the effects of read (r), write (w), and execute (x) permissions on directories
- Understanding the differences between hard links and soft links

### 4. Networking
- Configuring IP addresses and netmasks
- Testing network connectivity using the `ping` command

### 5. File Search and Management
- Comparing `find` and `locate` commands for file searching
- Understanding the pros and cons of each search method

### 6. Shell Scripting
- Developing scripts to automate tasks and perform complex operations
- Implementing conditional statements and loops in bash
- Handling command-line arguments in scripts

### 7. System Administration
- Creating backups using `tar`
- Understanding and manipulating file system structures

## Advanced Scripts Highlight

### Executable File Counter (q09.sh)
This script demonstrates:
- Iterating through command-line arguments
- Checking file types and permissions
- Counting executable files

### Directory Operations and Archiving (q10.sh)
This complex script showcases:
- Argument validation
- Directory creation based on current date
- Archiving and compressing directories using `tar`

## Skills Showcased
- Advanced command-line proficiency
- Shell scripting and automation
- File system navigation and manipulation
- Understanding of Linux file permissions and linking mechanisms
- Basic networking configuration and troubleshooting
- System administration tasks

## Usage
Each script file contains a specific Linux-related challenge and its corresponding solution. To run any script, use the following command in a Linux terminal:

```bash
bash script_name.sh
