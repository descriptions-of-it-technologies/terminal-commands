# Terminal Commands.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [General.](#general)
* [Navigation.](#navigation)
* [File Management.](#file-management)
* [Directory Management.](#directory-management)
* [Console Editors.](#console-editors)
* [Permission.](#permission)
* [Search.](#search)
* [Most used Alias.](#most-used-alias)
* [Git Commands.](https://github.com/Programming-Training-And-Practice/git-main-information/blob/master/git-commands.md)
* [Maven Commands.](https://github.com/Programming-Training-And-Practice/maven-main-information/blob/master/maven-commands.md)
* [Kubernetes Commands.](https://github.com/Programming-Training-And-Practice/kubernetes-main-information/blob/master/kubernetes-commands.md)
* [Articles.](#articles)
* [Conferences.](#conferences)
* [Conference Speakers.](#conference-speakers)
* [Help.](#help)





## About.





## Documentation.





## General.

| Key/Command    | Description                                                                |
| -------------- | -------------------------------------------------------------------------- |
| sudo [command] | Run command with the security privileges of the superuser (Super User DO). |
| pwd            | Full path to working directory.                                            |
| cat            | Concatenate to screen.                                                     |
| clear          | Clears the screen.                                                         |
| top            | Displays active processes. Press q to quit.                                |
| htop           | Displays active processes. Press q to quit.                                |
| open [file]    | Opens a file (as if you double clicked it).                                |
| reset          | Resets the terminal display.                                               |
| alias          | Show all alias.                                                            |
| history        | Show history.                                                              |
| whoami         | Show currently user used.                                                  |

`echo "export PATH=$PATH:/pathToExecutableFile" >> /etc/bash.bashrc`




## Navigation.

| Key/Command              | Description                                      |
| ------------------------ | ------------------------------------------------ |
| cd [folder]              | Change directory e.g. `cd Documents`.            |
| cd [path]                | Change directory e.g. `cd /home/user/Documents`. |
| cd                       | Home directory.                                  |
| cd ~                     | Home directory.                                  |
| cd /                     | Root of drive.                                   |
| cd ..                    | Previous directory.                              |
| cd ../../                | Move 2 levels up.                                |
| ls                       | Short listing.                                   |
| ls -l                    | Long listing.                                    |
| ls -a                    | Listing incl. hidden files.                      |
| ls -la                   | Long listing incl. hidden files.                 |
| ls -lh                   | Long listing with Human readable file sizes.     |
| ls -R                    | Entire content of folder recursively.            |
| colorls                  |                                                  |
| colorls -a               |                                                  |
| colorls -la              |                                                  |





## File Management.

| Key/Command              | Description                                          |
| ------------------------ | ---------------------------------------------------- |
| touch [file]             | Create a new file.                                   |
| rm [file]                | Remove a file, e.g. `rm data.tmp`.                   |
| rm -i [file]             | Remove with confirmation.                            |
| rm -f [file]             | Force removal without confirmation.                  |
| cp [file] [newFileName]  | Copy file to file.                                   |
| cp [file] [dir]          | Copy file to directory.                              | 
| mv [file] [newFileName]  | Move/Rename, e.g. `mv file1.ad /tmp`.                |
| less [file]              | Output file content delivered in screensize chunks.  |





## Directory Management.

| Key/Command          | Description                                             |
| -------------------- | ------------------------------------------------------- |
| mkdir [dir]          | Create new directory.                                   |
| mkdir -p [dir]/[dir] | Create nested directories.                              |
| rmdir [dir]          | Remove directory (only operates on empty directories).  |
| rm -R [dir]          | Remove directory and contents.                          |
| rm -r [dir]          | Remove a directory and contents.                        |





## Console Editors.

| Key/Command    | Description                             |
| -------------- | --------------------------------------- |
| vim [file]     | Opens the file using the vim editor.    |
| nano [file]    | Opens the file using the nano editor.   |





## Permission.

| Key/Command                       | Description                             |
| --------------------------------- | --------------------------------------- |
| chmod +x [file]                   | Give permission to execute the file.    |





## Search.

| Key/Command                       | Description                                                                                     |
| --------------------------------- | ----------------------------------------------------------------------------------------------- |
| find [dir] -name [search_pattern] | Search for files, e.g. `find /Users -name "file.txt"`.                                          |
| grep [search_pattern] [file]      | Search for all lines that contain the pattern, e.g. `grep "Tom" file.txt`.                      |
| grep -r [search_pattern] [dir]    | Recursively search in all files in specified directory for all lines that contain the pattern.  |
| grep -v [search_pattern] [file]   | Search for all lines that do NOT contain the pattern.                                           |
| grep -i [search_pattern] [file]   | Search for all lines that contain the case-insensitive pattern.                                 |





## Most used Alias.

| Alias                             | Command                                                                                               |
| --------------------------------- | ----------------------------------------------------------------------------------------------------- |
| GraalVM20R11                      | sdk default java 20.0.0.r11-grl                                                                       |                       
| GraalVM20R8                       | sdk default java 20.0.0.r8-grl                                                                        |
| JDK8                              | sdk default java 8.0.242-open                                                                         |
| UpdateConsole                     | source /home/trl/.zshrc                                                                               |
| aga                               | sudo apt autoclean                                                                                    |
| agar                              | sudo apt autoremove                                                                                   |
| agp                               | sudo apt purge                                                                                        |
| agr                               | sudo apt remove                                                                                       |
| agu                               | sudo apt update                                                                                       |
| agud                              | sudo apt update && sudo apt dist-upgrade                                                              |
| agug                              | sudo apt upgrade                                                                                      |
| aguu                              | sudo apt update && sudo apt upgrade                                                                   |
| h                                 | history                                                                                               |
| history                           | omz_history                                                                                           |
| hs                                | history | grep                                                                                        |
| hsi                               | history | grep -i                                                                                     |
| l                                 | ls -lah                                                                                               |
| la                                | ls -lAh                                                                                               |
| ll                                | ls -lh                                                                                                |
| ls                                | ls --color=tty                                                                                        |
| lsa                               | ls -lah                                                                                               |
| md                                | mkdir -p                                                                                              | 
| rd                                | rmdir                                                                                                 |





## Articles.





## Conferences.





## Conference Speakers.





## Help.
