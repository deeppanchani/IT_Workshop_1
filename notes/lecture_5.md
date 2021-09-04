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

<img src="/images/fig_5.3.png">

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

5. **Shell:-** It is an interface among the kernel and user. It can afford the services of kernel. It can take commands through the user and runs the functions of the kernel. The shell is available in distinct types of OSes. These operating systems are categorized into two different types, which are the graphical shells and command-line shells.


    The graphical line shells facilitate the graphical user interface, while the command line shells facilitate the command line interface. Thus, both of these shells implement operations. However, the graphical user interface shells work slower as compared to the command-line interface shells.

    There are a few types of these shells which are categorized as follows:
    1. Korn shell
    1. Bourne shell
    1. C shell
    1. POSIX shell
#### Types of Shells

The different C-type shells follow-
- C shell(csh)
- 
