# testa
This is a very simple collection of folders and files for the purpose of learning how to package for Debian-based GNU/Linux distributions.

This project is simple. All it contains is a text-file called "testfile" that is one line of text and a C binary that is setup to print the contents of that text file.

When the project is created, it *should* copy the textfile from "src" to "/home/$USER/test" according to the "DEBIAN/install" file.
The issue is also simple; this act of copying does not work. The binary installs fine with "dpkg-deb --build," but the text file from "src" is never copied to "/home/$USER/test"

If anyone could help figure out a solution it would be greatly appreciated!

This only called "testa" because "test" is already a program in most Linux distributions.
