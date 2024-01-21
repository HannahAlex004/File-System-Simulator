# File-System-Simulator
SEM III _Data Structures and Its Applications_MiniProject

## Directory Management Program
This is a simple command-line directory management program written in C. It allows users to create directories, create files within directories, list directory contents, change the current directory, delete files and directories, search for files, and edit file content.
### Getting Started
To use the program, compile the source code using a C compiler. For example:
##### gcc file_system.c -o file_system
##### Run the compiled executable:
##### ./file_system
#### Usage
The program provides a command-line interface for interacting with directories and files. Supported commands include:
##### createDir: Create a new directory.
##### createFile: Create a new file in the current directory.
##### listDir: Display the contents of all directories and files.
##### changeDir: Change the current directory.
##### deleteFile: Delete a file in the current directory.
##### deleteDir: Delete the current directory and its contents.
##### searchFile: Search for a file in the current directory and its subdirectories.
##### editFile: Edit the content of a file in the current directory.
##### quit: Exit the program.
#### Example Usage
##### _Creating a directory:_
Enter command (createDir, createFile, listDir, changeDir, deleteFile, deleteDir, searchFile, editFile, quit): createDir 
##### Enter directory name: my_directory 
##### _Creating a file:_
Enter command (createDir, createFile, listDir, changeDir, deleteFile, deleteDir, searchFile, editFile, quit): createFile Enter file name: my_file.txt 
##### Enter file content: This is the content of my file. 
##### _Listing directories and files:_
Enter command (createDir, createFile, listDir, changeDir, deleteFile, deleteDir, searchFile, editFile, quit): listDir 
##### _Changing the directory:_
Enter command (createDir, createFile, listDir, changeDir, deleteFile, deleteDir, searchFile, editFile, quit): changeDir
##### Enter directory name: my_directory 
##### _Deleting a file:_
Enter command (createDir, createFile, listDir, changeDir, deleteFile, deleteDir, searchFile, editFile, quit): deleteFile 
##### Enter file name: my_file.txt 
##### _Deleting a directory:_
Enter command (createDir, createFile, listDir, changeDir, deleteFile, deleteDir, searchFile, editFile, quit): deleteDir 
###### Contributing
Contributions are welcome. Please fork the repository, create a branch, make your changes, and submit a pull request.
