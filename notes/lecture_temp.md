# **Shell Scripting**

**Introduction :**
Shell is a command line interpreter (CLI), CLI is a program to read input from user, just like terminal in mac or cmd in windows. This CLI is used to read the commands like cat , grep ,awk etc , and then execute them.
There are several types shell available in Linux like BASH (Bourne Again Shell) , CSH , KSH etc. BASH is the most used shell.

**Working With Shell :**

- A shell file has extension sh.
- It contains a series of linux command which is executed using command:

  > `sh script.sh`
  > OR
  > `./script.sh`

  where script. sh is a shell script file.

- The contents of script file can be viewed using the cat command :

  > `cat script.sh`

- '#' is used for commenting out the lines of shell file and they will
  not be executed.

  >     > #File script.sh
  >     > #This is a comment!
  >     > echo Hello  World  # This is a comment, too!
  >
  > Output :
  > `Hello World`

  As you can see the lines which contain '#' in front of them are not executed
