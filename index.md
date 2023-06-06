# Part 1  

![Image](labf1.png)  
![Image](TA1.png)  

>**STUDENT**: After trying the `ls` command, I confirmed I was in the correct directory.  
>![Image](labf2.png)  
>But after double checking my files like you said, I found out that I actually had the correct `method` name, but incorrect `file` name so this might be why it wasn't being found!  
>![Image](labf3.png)  
>After changinge the name of the file, I ran the same command as before, to which the tests now passed.  
>![Image](labf4.png)  
>It seems that the bug I had faced was not related to the directory, but was rooted inside my file name within the github repository being graded by my script. Although the method name was correct, the file name was incorrect and since my grading script searches for a specific file name, it showed an error becuase it was named incorrectly before I changed it.  

  
**SETUP**:  Download visual studio code: https://code.visualstudio.com/download ,  
Github repository for setup on visual studio code: https://github.com/ucsd-cse15l-s23/list-examples-grader  
Github repository for submission being graded by the grading script: https://github.com/dperez1026/list-methods-filename  
Make sure you are in a `GitHub Bash` terminal, then make sure you're in the directory  `~/Documents/GitHub/list-examples-grader`.  
The contents of the file containing the bug before being fixed are:  
![Image](labf5.png)  





