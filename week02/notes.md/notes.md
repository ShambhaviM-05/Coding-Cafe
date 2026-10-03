1 pwd prints the current working directory. 
2 'ls -Force', shows hidden files also in addition to normal files whereas 'ls', only show files in that directory.

3 The Mode column in ls output tells you the item types. For Example : 
d---- means directory etc.

4 This works from your home folder because 'coding-cafe\week02' is a relative path as it is interpreted relative to our current location and not from the main drive root.

5 'mv' did two different jobs here:
1. It moved the file into a different folder(week01\),keeping the same name.
2. It renamed the file.

6 There are total 13 folders on my path.

7 C:\Users\shamb\AppData\Local\Programs\Python\Python312\python.exe

8 No, they're not same as my installation method is different from him as he installed it from Anaconda , which land in different folders.

9 The shell returns an error like  "The term 'pyton' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a
path was included, verify that the path is correct and try again."
This means that the shell searched every folder listed in "PATH" for a program named pyton , found no match and stopped, it's basically a typo, not a missing installation.1 pwd- "pwd" prints our current working directory i.e. full path.


10 .venv didn't show with plain ls because folders/files starting with a . are treated as hidden-same reason ls -Force was needed in sect 1 to reveal them.

11  This prompt shows now .venv prefixed at the very beggining , before the rest of the path.

12 This time , the  path will point inside project's .venv folder. This is different from Ques 7.
It tells about Activate.ps1, it doesn't install a new python -it modifies Path for the current session, quietly inserting .venv\Scripts at the front of the list . Since the shell searches PATH folders in order and stops at the first match , python now resolves to the venv copy first before it reaches to system. 

13 The second pip list shows requests itself, plus its dependencies that got pulled in automatically. None of such were in the first , near empty list.

14 python now prints back to originall system Python path because deactivate removes .venv\Scripts from the front of the Path,restoring it to what it was befoere deactivation.

15 -Recusre tells the command to go into all subfolders as well, not just the current directory-so ls -Recusre coding-cafre lists every file and folder at every nested level under coding-cafe, not just the top level.

16 DIFFERENCE BETWEEN Ctrl+C and Ctrl+Z:
Ctrl+C: It send an interupt signal stopping the currently running command or process.
WHEREAS
Ctrl+Z: sends end-of-input , telling the program that no more input is coming which causes python to close and return to Powershell. 


