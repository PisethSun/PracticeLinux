1. what does the command stat myfile.txt do? 

- Since I do not have the file named myfile.txt:
- I can create that file using touch command:
    - touch myfile.txt press enter.
    - Then if I type stat myfile.txt It will show me the statistics about that file. 
2. What does the command df -h / do?

- I can use the man df, I can discover it show the disk utilization of the root file system in a human-readable way 

3. what command would I use to search for files in a directory hieerarchy ?

- Using apropos - ab-pro-poo : apropos "Search for files"- to find mroe specific command

4. which option would I use with the LS commands to output a comma-seperated listed of files and directories? 

- using man ls

5. what shows you a brief amount of information about the command you entered?

- ls --help

6. How would you find the manual page for the command ip?

- man ip

7. How can you move to the beginning of a line of text?
- CTRL-A

8. To recall a previous command in Bash, you can use _____.

- ARROW UP

9. The _____ shell is available on many platforms.

- Bash

10. In the statement df -h /home/alice/Documents, the characters -h represent _____.

- an Option

11. The _____ is where we use the command line interface.

- shell 

12. The following string will list all files in the /usr/bin directory. Which part of this string is the argument?
ls -lh /usr/bin

- /usr/bin

13. Why isn't the statement /home/alice ls -l valid?

- The command always needs to come first, so this should read ls -l /home/alice

14. What will happen when you type part of a command, and then select Tab?

- It will autocomplete based on the part of the command you typed.

15. Correct these commands and describe the errors in each :
    cd ~/home/ubuntu
    LS /home
    mv ~/log.tar.gz home ubuntu
    chmod ~/log.tar.gz

    Answer: 

    cd ~ : errror is /home/ubuntu 
    ls should be lowercase l
    mv ~/log.tar.gz . or /home/ubuntu , remove home ubuntu 
    chmod need a group or optical representation. 
    chmod 644 ~/log.tar.gz 

    16. The rmdir command _____? 
     - While the rmdir command can only delete empty directories, you can use rm -rf to delete non-empty directories and trees of directories.

     17. What can you write to delete a directory called Photos which contains many subdirectories?
     - rm -r Photos - The -r option tells rm to remove the file hierarchy, not just files.

     18. The find command lets us look for files by name, size, etc., _____.
     - wherever the user who runs it has permission to view - When we run a command, it has the same access that the user running it does.

     19. While all other users' home directories are kept in /home/, the superuser's home directory is stored at _____.

     - /root 
     - Root is a special user, and it has a special home directory.

     20. What can you write to find files in Alice's home directory with report in the name?
      - find /home/alice -name "*report*"

      21. A symbolic link using a relative path will break if _____.
      - the link or the referenced file is moved

      22. What does the command ln -s outcome.txt report.txt create?
      - A symlink named report.txt that refers to outcome.txt.

      23. You have downloaded a program from the web, and when you try to run it, you receive the error:
-bash: ./newprogram: Permission denied

- Run the command chmod u+x newprogram to add execute permissions to the file.

25. You need to use superuser privileges to _____.
- modify system settings and software

26. How would you alter this command using octal notation to give read, write, and execute permissions to the file's owner, members of the file's designated group, and all other users for the file poems.txt?
chmod poems.txt

- chmod 777 poems.txt

27. 