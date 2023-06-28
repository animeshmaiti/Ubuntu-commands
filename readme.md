# 50 Linux Commands You Should Know -CodeWithHarry
### ls - list the files and directories in the current directory
```bash
ls
```
### cd - change the current directory
```bash
cd dir_name
```
### mkdir - create a new directory
```bash
mkdir dir_name
```
### rmdir - remove a directory
```bash
rmdir dir_name
```
### pwd - print the current working directory
```bash
pwd
```
### cp - copy files or directories
### We will copy a file called example.txt from the current directory to a directory called backup
```bash
cp example.txt backup/
```
### mv - move or rename files or directories
```bash
mv example.txt backup/
```
### rm - remove files or directories
```bash
rm example.txt
```
### touch - create a new empty file or update the timestamp of an existing file
```bash
touch shayan.txt
```
### cat - concatenate and display files
```bash
cat example.txt
```
### man - manual for a command
```bash
man ls
```
### htop - an interactive process viewer and system monitor
```bash
htop
```
## chmod - change the permissions of a file or directory
### The first digit represents the owner of the file/directory
### The second digit represents the group that the file/directory belongs to
### The third digit represents all other users
### 0 (no permission)
### 1 (execute only)
### 2 (write only)
### 3 (write and execute)
### 4 (read only)
### 5 (read and execute)
### 6 (read and write)
### 7 (read, write, and execute)
```bash
chmod 700 file.txt
```
### chown - change the owner of a file or directory
```bash
chown new_owner example.txt
```
## tar - create or extract compressed archive files
### x: extract files from an archive
### t: list the contents of an archive
### r: append files to an existing archive
### z: use gzip compression
### j: use bzip2 compression
### cf: create file
### xf: extract file
```bash
tar cf archive.tar file1 file2 file3
```
### gzip - compress files
```bash
gzip file.txt
```
### gunzip - decompress compressed files
```bash
gunzip file.txt.gz
```
### ssh - connect to a remote server securely
```bash
ssh username@server_address
```
### scp - securely copy files between systems
```bash
scp myfile.txt user@remotehost:/home/user/
```
### ping - test network connectivity
```bash
ping 8.8.8.8
```
### ifconfig - display or configure network interfaces
```bash
ifconfig
```
### netstat - display network connection information
```bash
netstat
```
### route - view or configure network routing tables
```bash
route [options] [add/delete/show]
```
### top - display system resource usage and processes
```bash
top
```
### ps - display information about running processes
```bash
ps aux
```
### kill - terminate a process
```bash
kill [PID]
```
## systemctl - control system services and settings
### Start the nginx service
```bash
systemctl start nginx
```
### Check the status of the nginx service
```bash
systemctl status nginx
```
### Stop the nginx service
```bash
systemctl stop nginx
```
### service - control system services
```bash
service apache2 start
```
### useradd - add a new user to the system
```bash
useradd harry
```
### passwd - change the password for a user
```bash
passwd harry
```
### userdel - delete a user from the system
```bash
userdel harry
```
### su - switch user to become another user
```bash
su john
```
### sudo - execute a command as another user or with elevated privileges
```bash
sudo
```
### uptime - display system uptime and load average
```bash
uptime
```
### df - display disk space usage
```bash
df
```
### du - display disk usage by file or directory
```bash
du
```
### mount - mount a file system
```bash
sudo mount /dev/sdb1 /mnt/usb
```
### umount - unmount a file system
```bash
sudo umount /mnt/usb
```
### date - display or set the system date and time
```bash
date
```
### whoami - display the current user name
```bash
whoami
```
### which - locate a program or command in the system path
```bash
ls
```
### finger - displays all the information about user
```bash
finger harry
```
### uname - display system information
```bash
uname
uname -a
```
### history - display a list of previously executed commands
```bash
history
```
### echo - display text or variables to the console
```bash
echo 'I need Tshirt from codeswear!'
```
### tee - redirect output to both a file and the console
```bash
$ ls | tee file.txt
```
### locate - locate any file on the system
```bash
locate file.txt
```
### sort - sort lines of text in a file or input
```bash
cat file.txt
```
```
banana
orange
apple
sort file.txt
apple
banana
orange
```
### uniq - remove duplicate lines from a file or input
```bash
cat file.txt
```
```
apple
orange
banana
apple
banana
uniq file.txt
apple
orange
banana
```
### head/tail - display the first/last few lines of a file or input
### display first 10 lines
```bash
head file.txt
```
### display last 10 lines
```bash
tail file.txt
```