# 42_Piscine_Shell00

This project is all about learning and mastering terminal commands and shell scripting. In Shell 00, I explored file permissions, Git, Kerberos, and more, gaining valuable skills in Unix-based environments. Here's how it went!  

 - Exercise 00: Z  

The first task was pretty simple, but it taught me the importance of precision. I had to create a file named z that, when read using cat, would display a "Z" followed by a newline. It seemed easy, but I learned about file creation and basic shell commands like echo and cat in the process.  

- Exercise 01: testShell00  
  
Next, I created a file testShell00 with very specific permissions. The tricky part was understanding how to manage file permissions in Unix using chmod. Once I got the hang of the permission system (read, write, execute), I archived the file using tar. This exercise introduced me to file management and how crucial permissions are in a Unix system.  
  
- Exercise 02: Again, again...  

This one took things a step further. I had to create a directory structure with specific files, each with different permissions. Recreating the structure as described in the task and then archiving everything into exo2.tar was quite a challenge. I learned a lot about managing directories, symbolic links, and different file types. It was my first taste of how detailed shell work can be.  

- Exercise 03: Connect me!  
  
In this exercise, I had to work with Kerberos credentials, something completely new to me. I needed to retrieve and list my credentials in a klist.txt file. It was my first real introduction to working with authentication systems in a shell environment. After a bit of research and testing, I managed to list my Kerberos tickets successfully.  

- Exercise 04: midLS  
  
Here, I created a script that lists all non-hidden files and directories in the current directory, sorted by creation date. The twist was to exclude hidden files and make sure directories were followed by a /. I spent a lot of time experimenting with different ls options and learning about how to format the output exactly as requested.  

- Exercise 05: GiT commit  

This was my first exercise involving Git! I wrote a script that retrieves the last 5 Git commit hashes. Understanding Git's command-line interface was a bit overwhelming at first, but once I figured out how to get the commit history with git log, it was just a matter of formatting the output to fit the requirements. It was a fun way to get more familiar with Git's power.  

- Exercise 06: gitignore  
  
Building on the previous exercise, I had to write a shell script that lists all the files in my Git repository that are currently ignored by .gitignore. This one was tricky because I had to make sure my script detected the ignored files correctly. I played around with git status --ignored to get the result I needed and practiced working with Git in a real project environment.  

- Exercise 07: diff  
  
The task here was to create a file b that would generate a specific diff when compared to another file a. This exercise made me realize how useful the diff command is for comparing files. By experimenting with different file contents, I was able to understand how diff works, and I managed to get the exact output required.  

In this project, I gained a solid foundation in terminal commands and shell scripting. By completing various exercises, I learned to manage files, handle permissions, and utilize Git effectively. This experience not only enhanced my technical skills but also deepened my understanding of Unix-based systems, preparing me for more advanced programming challenges in the future.  