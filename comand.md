# important comands in ubuntu
### 1. For acess any directory,folder,file as admin or root user
```bash
sudo chmod 777 <filename>
<password>
```
### 2. Create any directory as admin
```bash
sudo mkdir <folder name>
```
### 3. Delete any directory as admin
```bash
sudo rmdir <folder name>
```

### 4. DocumentRoot directory of the Apache2 Web server
```bash
cd /var/www/html/
```

### 5. Back to home directory
```bash
cd ~
```

### 6. Back prev directory
```bash
cd -
```

### 7. Root directory
In Linux, /etc is a directory that contains configuration files for the system. These files are used to store settings for the kernel, services, and applications. The /etc directory is typically located in the root directory of the filesystem.
```bash
cd /rtc
```
### 8. Stop/start/restart apache server
```bash
sudo /etc/init.d/apache2 stop
```
```bash
sudo /etc/init.d/apache2 start
```
```bash
sudo /etc/init.d/apache2 restart
```
### 9. Change any user password
this command is very useful for change any user password if any permission error occur then use sudo before command or su as root user root help to change directory permissions
```bash
su root
```
 when you switch user you need password of root user if ypu don't know password of root user then use this command
```bash
sudo passwd root
```