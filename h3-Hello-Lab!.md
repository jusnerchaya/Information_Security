## x) Read/watch/listen and summarize

# Command Line Basics Revisited

This article revisits essential Linux and BSD command-line basics, emphasizing its efficiency, expressiveness, and automation capabilities.

## Navigating and Viewing Files
- **`pwd`**: Prints the current directory.
- **`ls`**: Lists files in the working directory.
- **`cd DIRECTORY`**: Moves into a directory.
- **`cd ..`**: Moves up one directory level.
- **`less FILE`**: Views text files with navigation commands (e.g., `/` for search, `q` to quit).
- **`command | less`**: Pipes command output to `less` for paginated viewing.

## File Manipulation
- **`nano FILE`**: Edits a file using `nano` (save with `CTRL-X y Enter`).
- **`mkdir DIRECTORY`**: Creates a new directory.
- **`mv OLDNAME NEWNAME`**: Moves or renames files.
- **`cp -r ORIGINAL COPY`**: Copies files or directories recursively.
- **`rm FILE` / `rm -r DIRECTORY`**: Deletes files or directories permanently (no trash).

## SSH Remote Control
- **`ssh user@server`**: Securely connects to a remote machine.
- **`scp -r LOCAL_FOLDER user@server:REMOTE_PATH`**: Securely copies files to a remote machine.

## Getting Help
- **`man COMMAND`**: Displays a command’s manual page.
- **`COMMAND --help`**: Shows brief usage instructions.

## Command History and Autocompletion
- **Tab key**: Auto-completes commands and filenames.
- **`history`**: Displays previously run commands.
- **`CTRL-R`**: Searches command history.

## Important Directories
- **`/home/username/`**: User’s home directory.
- **`/etc/`**: System-wide configuration files.
- **`/media/`**: Mounted external drives.
- **`/var/log/`**: System logs.

## Administrative Commands and Software Management
- **`sudo apt-get update`**: Updates package lists.
- **`apt-cache search software`**: Searches for software.
- **`sudo apt-get install PACKAGE`**: Installs software.
- **`sudo apt-get purge PACKAGE`**: Uninstalls software and removes configurations.

The article concludes with an example of installing, running, and removing a game (`nethack`) while advising against getting addicted!

Source: https://terokarvinen.com/2020/command-line-basics-revisited/

