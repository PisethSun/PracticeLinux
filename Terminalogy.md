What is a Line? 
- Long commands or long series of commands can wrap at the window boundrym but ther are still considered one line

- A line is any text we type at the command prompt before pressing return

What is df command?
- Report file system disk space

What is -h ? Human readable way

-print size of the power of 1024 . 

What is -R command? 

- it mean to list directories recursively 
- Example: ls  -R departments/ 

what is cd - ? 
- if you try to navigate or switch from on path to another it is easier that way to switch around. jump in a directory and back with out losing it place. 

what happen if you run ls -lh or -l -h command? -l mean long list

- this will list all listing in a directory and will show all the file would contain , permission , group , time and file size. 

what is -p?
- used to create a new directory
mkdir department/legal/contracts

how do I delete that directory?

- rmdir  department/legal/contracts, delete directory the directory must be empty 

- What is cp command? 

- stand for Copy.
Example: if you want to cop a file name simple.txt into 
directory call departments/hr/employee info

- Then here - cp simple_data.txt departments/hr/employee\ info /

-what is mv command? 
- stand for move command
eg: mv {filename} {directory or folder name } {subdirectory } 
eg: mv poems.txt departments/marketing

- can you rename using MV command?
- Yes,
- example rename poems2.txt to reading.txt
 mv departments/marketing/poems2.txt departments/marketing/reading.txt
- you can move that file to the directory by typing :
eg:  mv departments/marketing/reading.txt . 


- what is the different between ? and *?  => this are wildcard 

- any chracter * all and ? one character . 

eg: if you want to move any file that has .txt extension than you would do this: 

mv *.txt departmens/marketing

- if you want to move back to it previous directory you would do this: 

- eg:  mv departments/marketing/* . 

Now here is the example for ? wildcard:

- Let say you have reading.txt and reading2.txt and reading3.txt

- To delete u have reading.txt and reading2.txt and reading3.txt the you would use this command. 

- rm reading?.txt - this way you don't delete all but only selected one.


- if you want to delete directory and it files :
eg: rm -r departents/customerservice/

- what is find command?

- used to find file if you dont know where it is 
- eg: find . -name "Poe*" - find a file in the working directory with all keyword starting with  "Poe" 

- helpful find : find . -name "*d*" - Find anything file and directory starting , mixing , ending with letter d.
