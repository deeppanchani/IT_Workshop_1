# Lecture- 5
## Topic- Introduction to Shell Scripting, `head` and `tail` command
## Date- 21 Aug 2021

### ls * command recursive listing

```bash
ls *
```

<img src="/images/fig_5.1.png">

----

### `head` command

```bash
head [OPTION]... [FILE]
```
Print the first 10 lines of each FILE to standard output.

<img src="/images/fig_5.2.png">

**-n Option**

```bash
head -n 3 [FILE]
```
This command will print only first 3 lines of the FILE.

<img src="/images/fig_5.3.png">

### `tail` command

```bash
tail [OPTION]... [FILE]
```
Print the last 10 lines of each FILE to standard output.

<img src="/images/fig_5.4.png">

**-n Option**

```bash
tail -n 3 [FILE]
```
This command will print only last 3 lines of the FILE.

<img src="/images/fig_5.5.png">

### Introduction to Shell Scripting

#### Linux System Architecture

<img src="/images/architecture-of-linux.png">

The Linux operating system's architecture mainly contains some of the components: **the Kernel, System Library, Hardware layer, System,** and **Shell utility**.

1. **Kernel:-** The kernel is one of the core section of an operating system. It is responsible for each of the major actions of the Linux OS.

    - This operating system contains distinct types of modules and cooperates with underlying hardware directly.

    - The kernel facilitates required abstraction for hiding details of low-level hardware or application programs to the system.
    
    - There are some of the important kernel types which are mentioned below:

        1. Monolithic Kernel
        1. Micro kernels
        1. Exo kernels
        1. Hybrid kernels

2. **System Libraries:-** These libraries can be specified as some special functions. These are applied for implementing the operating system's functionality and don't need code access rights of the modules of kernel.

3. **System Utility Programs:-** It is responsible for doing specialized level and individual activities.

4. **Hardware layer:-** Linux operating system contains a hardware layer that consists of several peripheral devices like CPU, HDD, and RAM.

5. **Shell:-** It is an **interface among the kernel and user**. It can afford the services of kernel. It can take commands through the user and runs the functions of the kernel. 
    
    The shell is available in distinct types of OSes. These **operating systems are categorized into two different types**, which are the **graphical shells** and **command-line shells**.

    However, the graphical user interface shells work slower as compared to the command-line interface shells.

    There are a few types of these shells which are categorized as follows:
    1. Korn shell
    1. Bourne shell
    1. C shell
    1. POSIX shell

#### Types of Shells

In Unix, there are two major types of shells:

1. Bourne shell - If you are using Bourne-type shell, the $ character is the default prompt.
2. C Shell - If you are using a C-type chell, the % character is default prompt.

Usually Bourne shell are faster than C-Type.(Not always)

Bourne shell has the following subcategories:
- **Bourne shell(sh)**: 1st version of Bourne shell. It didn't had capability to see history of commands and even we can't use simple arithmetic and logical commands.
- **Korn shell (ksh)**: It is a Superset of sh.
- **Bourne Again shell (bash)**: It cover all features of ksh.

ksh and bash are faster than C-type Shell.

The different C-type shells follow-
As the name suggest they have C like Programming features. 
- **C shell(csh)**: It also has arithmetic and logical command support but it dosnt have the faclity to see history of commands.
- **TENEX/TOPS C shell(tcsh)**: It is an extension of csh. It is a command line interpreter, command line editor, spell correction, shell scripts. 

##### How to check all the installed Shells

```bash
cat /etc/shells
```
<img src="/images/fig_5.6.png">

##### How to check current shell Shells

```bash
grep {username} /etc/passwd
```
<img src="/images/fig_5.7.png">

##### How to change current shell

```bash
chsh -s {shell-name} {user-name}
```
<img src="/images/fig_5.8.png">
<br>
<img src="/images/fig_5.9.png">

#### Shell Script

- When a group of commands have to be executed regularly, they should be stored in a file.
- The file itself can be executed as a shell script or shell program.
- Shell scripts are executed in a separated child shell process.
- This sub-shell need not be of the same type as your login.
