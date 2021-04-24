### MYSQL SHUTDOWN AND DATABASE CRASH ###

## HOW TO FIX
1. Backup folder/file xampp>mysql>data
  - iblogfile0
  - iblogfile1
  - ibdata1
  - all folder in folder data ( your database scheme and phpmyadmin)
  - or you can backup all folder data
2. Stopped apache and mysql or quit xampp ( if your xampp running ) 
3. Delete folder/file xampp>mysql>data data
4. You can copy folder/file xampp>mysql>data ( in this file xampp v.7.2)
5. Paste and replace your backup folder/file(1) in xampp
  - iblogfile0
  - iblogfile1
  - ibdata1
  - all folder ( not your all file except iblogfile0, iblogfile1 and ibdata1)
6. Start your xampp ( apache and mysql )
7. Success, your database had save!


## PROBLEM 
USSUALLY HAPPENS BECAUSE YOU SHUT DOWN YOUR PC BUT YOU FORGET TO STOP YOUR APACHE AND MYSQL OR QUIT XAMPP