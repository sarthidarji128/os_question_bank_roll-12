# 1. Basic File Handling Utilities in Linux and Their Usage

ls: Lists the contents of a directory.
Usage: ls [options] [directory]
Example: ls -l /home

cp: Copies files and directories.
Usage: cp [options] source destination
Example: cp file1.txt /backup/file1.txt

mv: Moves or renames files and directories.
Usage: mv [options] source destination
Example: mv oldname.txt newname.txt

rm: Removes files or directories.
Usage: rm [options] file
Example: rm -rf /unwanted_directory

touch: Creates an empty file or updates the timestamp of an existing file.
Usage: touch filename
Example: touch newfile.txt

cat: Concatenates and displays the contents of files.
Usage: cat [options] file
Example: cat file.txt

mkdir: Creates directories.
Usage: mkdir [options] directory
Example: mkdir new_directory

rmdir: Removes empty directories.
Usage: rmdir directory
Example: rmdir old_empty_directory


# 2. Fundamental Concepts of Files in Computer Systems and Their Representation

 File Name: This is the humanreadable identifier for the file. It's how users recognize and access files without needing to understand the underlying technical details.

 File Path: This represents the location of the file within the file system hierarchy. It typically includes the directories and subdirectories leading up to the file, providing a unique address for each file.

 File Descriptor: In computing, a file descriptor is an integer that uniquely identifies an open file in a computer's operating system. It acts as a handle that programs can use to request read, write, or other operations on the file.

 File Metadata: This includes all the information about the file other than its content. Metadata can consist of the file's size, its permissions (who can read, write, or execute it), timestamps (like creation or last modification times), and the file's owner.

 File Content: This is the actual data or information stored within the file. It could be text, images, executable code, or any other type of data.
