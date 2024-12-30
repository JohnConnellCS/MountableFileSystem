# Hey! I'm Filing Here

In this lab, I successfully implemented an ext2 file system image that can be mounted. The resulting image contains a root directory which holds a file 'hello-world', a symbolic link 'hello' that points to the 'hello-world' file, and a directory 'lost+found'. Navigation commands such as '.' and '..' are valid with the directories and metadata is correctly set.

## Building

Run 'make' to build the executable

## Running

Run the executable 'ext2-create' to create the file system image

'mkdir mnt' creates a new directory

'sudo mount -o loop cs111-base.img mnt' mounts the file system to mnt


## Cleaning up
'sudo umount mnt' unmounts the file system

'rmdir mnt' removes the created directory

Run 'make clean' to remove the executable
