# Directory Cleanup Bash Script

## Overview

This Bash script is designed to organize files in a specified directory by moving them into subdirectories based on their file extensions. It also dynamically creates subdirectories as needed.

## Usage

1. **Run the Script:**
    - Make the script executable: `chmod +x your_script_name.sh`
    - Execute the script: `./your_script_name.sh`

2. **Input Directory Path:**
    - You will be prompted to input the directory path where the files are located.

3. **Organizing Files:**
    - The script identifies each file's extension and moves it to a corresponding subdirectory.

4. **File Criteria:**
    - Regular files (not directories) that are not executable are considered for organization.
    - The script distinguishes empty files and determines their type using the `file` command or extracts the extension directly.

5. **Directory Creation:**
    - Subdirectories are created dynamically based on file extensions if they do not already exist.

6. **Cleanup Message:**
    - Once all files are processed, a message is displayed indicating that the directory has been successfully cleaned.

## Prerequisites

- Bash environment (Linux, macOS, Git Bash on Windows, etc.)
- The `file` command for accurate file type determination.

## Important Note

- The script assumes that the `file` command is available in your environment for accurate file type identification.
- It is recommended to review and customize the script based on specific use cases or requirements.
