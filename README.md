### Operating systems :floppy_disk:
# Dropbox-Shell 

The project is a shell that exposes the functionality of the dbxcli utility (ex. cp, mv, mkdir, rm) and connects with the local file system. It was developed by myself and [Valentin Maftei](https://github.com/ValentinMaftei). It is essentially a wrapper around the dbxcli library, which can be found at https://github.com/dropbox/dbxcli.

We have enhanced the functionality of the dbxcli by adding the ability to upload and download entire folders, not just individual files. Additionally, we have implemented the "cd" command to make navigation through remote folders easier, a functionality that was not present in the original dbxcli. The commands that can be used within the program can be consulted using the "help" command.

The shell has a simple design and the commands are highlighted by a similar color palette to the Linux terminal. Overall, our project makes working with Dropbox's functionality through the command line more efficient and user-friendly.
