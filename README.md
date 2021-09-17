# DevTools
Dev tools wikki for Developer


## Sync tools
Sync files between local copy and your cloud dev instance

### rsync
rysnc is one of most popular utility to sync files. This can used take backup of files and even run deamon process to continues to backup/trasfer file. This is really helpfull in copying changes in dev instances.

**Installing Rsync**

The rsync utility is pre-installed on most Linux distributions and macOS. If you don’t have rsync installed on your system, you can easily install it using your distribution’s package manager.

**Install Rsync on Ubuntu and Debian**

`sudo apt install rsync`

**Install Rsync on CentOS and Fedora**

`sudo yum install rsync`

**Example**
```
rsync -a 
--exclude-from='/exclude-file.txt'

/src_directory/ 

/dst_directory/
```
dst_directory can be in remote host.

 
