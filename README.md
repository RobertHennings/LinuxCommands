# LinuxCommands
This repository holds some useful quick commands and tips (at least for me) for working with the shell in the command line terminal, especially when working with git over the command line in the terminal.

## Getting quick help and manual entries for commands

General structure:

**command -h**

or the longer, explicit format:

**command --help**

**info command**

For some commands there migth also exist a manual page:

**man command**

To get to the manual page for the manual itself:

**man man**

Example:

Show the manual page for the command ls:

**man ls**

## Check the type of a command

**type command**


## List files in a directory or path
List all files inclusive hidden .files (dot files):

**ls -a**

List all the files with additional information regarding access, size and status:

**ls -l**

Sort the files according to their size:

**ls --sort=SIZE**

Sort after last access:

**ls --sort=TIME**

To get a nicer view of especially the file size, type in:

**ls -lh**

## Navigating file paths

General structure:

**cd path/to/navigate/to**

Determine the current full file path:

**pwd**

Switch to the next higher file level:

**cd ..**

Switch to the last path that was in use:

**cd -**

Switch to the home path:

**cd~** or just the bare **cd**

## Copy, Move, Delete and Rename files
To create a new directory simply type in:

**mkdir new/directory**

To create a new file:

**touch new_file**

cp copies files and directories but be careful not to override existing structures

To copy a file into a directory:

**cp file_1 directory_1**

To copy a directory into a directory:

**cp directory_1 directory_2**

To override files:

**cp file_1 file_2**

If the user shoudl be asked if the command should be executed switch to the interactive mode:

**cp -i file_1 file_2**

To rename a file:

**mv file_old_name file_new_name**

To delete files or whole dirs:

**rm file_1**

To delete files recursively:

**rm -r file_path**

To delete dirs, add the -r flag:

**rm -r directory_1**

Delete an empty dir:

**rmdir**

## Working with placeholders
Copy all the existing .txt files in the current dir and copy them into the specified dir:

**cp*.txt text_file_dir**

To delete all files in the current dir:
**rm***

## Searching for files and stuctures

Search for all .pdf files in the current dir:

**find*.pdf**

Search for all .pdb files in the home dir:

**find ~ -name '*.pdb'**

Or use **which** to find a path.

Find the location of python:

**which python3**






