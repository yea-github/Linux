# Linux

### Print Hello World

```sh
$ echo "Hello World"
```

### Create directory

```sh
$ mkdir testing
```

### Change directory

```sh
$ cd testing
```

### List contents inside a directory

```sh
$ ls -l
```

### Find logged in user

```sh
$ whoami
```

```sh
$ users
```

```sh
$ who
```

```sh
$ w
```
### Findout used disk space in the system by user

```sh
$ df -h
```

### Bring the system down immediately

```sh
$ halt
```

### Powers off the system using predefined scripts to synchronize and clean up the system prior to shutting down

```sh
$ init 0
```

### Reboots the system by shutting it down completely and then restarting it

```sh
$ init 6
```

### Shuts down the system by powering off

```sh
$ poweroff
```

### Reboot the system

```sh
$ reboot
```

### Shut down the system

```sh
$ shutdown
```

### Listing all files

```sh
$ ls
```

### Listed files with more information

```sh
$ ls -l
```

### List hidden or invisible files

```sh
$ ls -a
```

### Create file in Linux

```sh
$ vi filename
```

### Display content of a file

```sh
$ cat filename
```

### Display file content with line number

```sh
$ cat -b filename
```

### Counting words in a file

```sh
$ wc filename
```

### Get information about multiple files

```sh
$ wc filename1 filename2 filename3
```

### Copying contents from one file to another file

```sh
$ cp source_file destination_file
```

### Make a copy of existing file

```sh
$ cp filename copyfile
```

### Change the name of existing file

```sh
$ mv old_file new_file
```

### Rename the existing file

```sh
$ mv file_name new_file
```

### Rename the existing file

```sh
$ mv filename newfile
```

### Delete a file

```sh
$ rm filename
```

### Remove multiple files at a time

```sh
$ rm filename1 filename2 filename3
```

### Create symbolic link to a file name

```sh
$ ln -s filename symlink
```

### Create hard link to a filename

```sh
$ ln filename hardlink
```

### Got to home directory

```sh
$ cd ~
```

### Go to users home directory

```sh
$ cd ~username
```

### Got o last directory

```sh
$ cd -
```

### Get current full path

```sh
$ pwd
```

### List the files in a directory

```sh
$ ls dirname
```

```sh
$ ls /usr/local
```

### Create multiple directory

```sh
$ mkdir docs pub
```

### Remove directory

```sh
$ rmdir dirname
```

### Remove multiple directory

```sh
$ rmdir dirname1 dirname2 dirname3
```

### Change directory

```sh
$ cd dirname
```

### Rename directory

```sh
$ mv old_dir new_dir
```

### Add executive permission of the owner

```sh
$ chmod u+x file
```

### Remove write permission from the group

```sh
$ chmod g-w file
```

### Set others to read-only (wipes other permissions)

```sh
$ chmod o=r file
```

### Give everyone read and write access

```sh
$ chmod a+rw file
```

### Give all permissions

```sh
$ chmod 777
```

### Owner can edit, others can run

```sh
$ chmod 755
```

### Owner can edit, others can only read

```sh
$ chmod 644
```

### Only owner can read/write

```sh
$ chmod 600
```

### Read only for owner

```sh
$ chmod 400
```

### Change ownership of a file

```sh
$ chown user filelist
```

### Changing owner of the file

```sh
$ chown amrood testfile
```

### Changing group of the file

```sh
$ chgrp developers testfile
```

### Assign a String in a variable and print

```sh
$ MESSAGE="I LOVE JESUS"
```

```sh
echo $MESSAGE
```

### Using XAMPP in Linux

```sh
/opt/lampp/htdocs
sudo mkdir demo-site
sudo chown -R $USER:$USER test-site
```

```sh
cd /opt/lampp
sudo ./xampp start
sudo ./xampp stop
```

```sh
sudo service apache2 stop
```

```sh
cd /opt/lampp
sudo ./manager-linux-x64.run
```

### Install application

```sh
sudo dpkg -i packagename.deb
```
