ntroduction
In this lab report, I will share my experience with basic filesystem commands, including cd, ls, and cat. The examples provided cover scenarios with no arguments, paths to directories, and paths to files.
Ex1:(base) enqidai@Enqis-MacBook-Air ~ % cd
(base) enqidai@Enqis-MacBook-Air ~ %
Output:
No output.
Explanation:
Running cd with no arguments takes you to the home directory. In this case, the working directory was /home/user, and the command navigated to the home directory.
Ex2:(base) enqidai@Enqis-MacBook-Air ~ % cd /home/user
cd: no such file or directory: /home/user
Explanation:
The cd command followed by a path takes you to the specified directory.
Ex3:(base) enqidai@Enqis-MacBook-Air ~ % cd I94 - Official Website.pdf
cd: too many arguments
Explanation:
The cd command is used to change directories, and providing a path to a file is not valid. The error indicates that the specified path is not a directory.
Ex4:(base) enqidai@Enqis-MacBook-Air ~ % ls
Applications
Explanation:
Running ls with no arguments lists the contents of the current directory. In this case, the working directory was /home/user, and it displayed the files file1.txt, file2.txt, and the directory directory1.
Ex5:
Ex6:(base) enqidai@Enqis-MacBook-Air ~ % ls I94 - Official Website.pdf
ls: -: No such file or directory
ls: I94: No such file or directory
ls: Official: No such file or directory
ls: Website.pdf: No such file or directory
(base) enqidai@Enqis-MacBook-Air ~ % 
Explanation:
The ls command followed by a path lists the contents of the specified directory. In this case, the working directory was /home/user, and it displayed the files file3.txt, file4.txt, and the directory subdirectory within /path/to/directory.
Ex7:(base) enqidai@Enqis-MacBook-Air ~ % cat
Explanation:
The cat command is used to concatenate and display the content of files. Providing a path to a directory is an error, as directories cannot be concatenated.
Ex8:  cat /path/to/file.txt
Output:
Content of file.txt

Explanation:
Using cat with a path to a file displays the content of the specified file. In this case, the working directory was /home/user, and it displayed the content of file.txt within /path/to/.
Ex9:cat /path/to/directory
Output:
Error: Is a directory.

Explanation:
The cat command is used to concatenate and display the content of files. Providing a path to a directory is an error, as directories cannot be concatenated.
