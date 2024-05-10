- File command tell you where the folder located but not in-detail . 

- stat command tell more detail about the folder/directory

---

Highest to low for file system:
1. root: / 
2. Home directories: /home 
    - Located user personal file 
    - each user should have one
    - Bash and many other shell should have (~)
    - /home usually have Document , download and other folders

3. Common configuration files: /etc - most programs keep their configuration files.
4. Common programs or commands: /bin,/sbin - where system relies on to work to kept,
5. Shared libraires and modules: /lib - are store 
6. Standard location for mounting other file systems: /mnt,/media - USB drive , optical drive 


Folder that are related to the system and Kernel :

- dev folder -  is where the system keeps references  to all the hardware it has. CPU etc..

- proc folder which contain refrence to processess. contain al other aspects  of the system as well.

- Sys folder - which hold files representing different kernek parameters and system inforamtion. 
