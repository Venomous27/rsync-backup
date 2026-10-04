# A simple shell script which uses rsync to take backup of declared directories 

**Make sure your external drive is connected or else it'll copy all the stuff on your local machine**

> How to use?
* Make the script executable:
  ```chmod +x ~/path/to/script/backup.sh```

> To be noted
  * `HDD_PATH` defines external drive's path. Change is according to yours
  * `BACKUP_DIR` defines where you want you store your backup copy. <br> Recommended `BACKUP_DIR="$HDD_PATH/Backup_$(date +%d-%m-%Y)"`
  * `SOURCES` contains the list to directory you want to backup.

**Don't run the script if you're not sure what it does. I don't want you to wipe the main copy on your local machine while you were just trying to take the backup :)**
