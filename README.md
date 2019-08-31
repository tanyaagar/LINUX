# LINUX
Linux is an operating system or a kernel. It is distributed under an open source license. Its functionality list is quite like UNIX.
The main advantage of Linux was that programmers were able to use the Linux Kernel to design their own custom operating systems. 
It is the backbone of popular operating systems like Debian, Knoppix, Ubuntu, and Fedora.
KERNEL
 A kernel is a program at the heart of any operating system that takes care of fundamental stuff, like letting hardware communicate with software.
 The benefits of using Linux are as follows.
 Being open-source, anyone with programming knowledge can modify it.
 Linux is a highly secure system. 
 Linux is the OS of choice for Server environments due to its stability and reliability .
 In Microsoft Windows, files are stored in folders on different data drives like C: D: E:
But, in Linux, files are ordered in a tree structure starting with the root directory.


 
 # COMMANDS IN LINUX
 
 cd or cd~  Navigate to HOME directory
 cd ..      Move one directory level up
 cd /       Move to root directory
 cd         To change a particular directory
 ls         To list all the files in the current directory.
ls -R       To show all the files present not only in the directory but also subdirectory.
ls -a       To show all the hidden files.
cat > filename                   to create a new file 
cat filename                      Displays the file content
cat file1 file2 > newfilename    The syntax to combine 2 files
rm filename                       remove file
mv filename new_file_location     moving the file
mv filename newfilename           renaming the file name
history                           shows all the commands that you have used in the past for the current terminal session.
clear                             clears the terminal
apt                               commands to install or remove a package
sudo apt-get update               updates the installed package
sudo apt-get install packagename  installes the given package
sudo                              Allows regular users to run programs with the security privileges of the superuser or root
ls - l                            tells us about the permissions given to the owner, user group and the world.
chmod                             used to change modes ie we can chane the permissions of owner group and world
permissions are of three types 
1) read(r) 2) write(w) 3) execute(x)
chmod command can be used in 2 ways
1) Numeric method eg - chmod 777 sample
Here the different perissions have octal no assigned to them eg 7 means R+W+X
2) Symbolic method eg chmod o=rwx sample or chmod g+x sample
sudo chown owner_name file_name       used to change owner
mkdir directoryname                   used for making new directory
rmdir directoryname                   used for removing directory






