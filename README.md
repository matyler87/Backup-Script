Backup-Script
=============

Simple backup bash script that could run as a crontjob on a linux box to backup necessary files and directories. This bash script was written as a means of backing up necessary directories and tarballing (compressing) the files by date. An incremental backup is done as often as the user sees fit but the backup is not full, it's incremental. The backup is finally compressed and ready to be saved off site or to an external disk. 
