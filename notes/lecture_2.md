# Lecture- 2
## Topic- File System Commands
## Date- 05 Aug 2021

### ls command

ls lists the files in the current working directory. Files are listed in alphabetical order.

```bash
ls [OPTIONS][FILES]
```
<img src="/images/fig_2.1.png">

**-F option**

-F option is used to bifergate between files and directories. When we use this option a '/' is added at the end of every directory name.

```bash
ls -F
```
<img src="/images/fig_2.2.png">

**-a option**

-a option is used to see all files present in the current working directory. To indicate a file/directory is hidden a '.' is added at the starting of the name of file/directory

```bash
ls -F
```
<img src="/images/fig_2.3.png">

**-x option**

-x lists entries by lines instead of by columns.

<img src="/images/fig_2.4.png">

as you can see in the image in when we used ls command the files/directories are organised in columns. But when we used -x they are printed in a countinous list.

**-l option**

-l is long listing format. By using this option we get a list of all the files and directories along with permitions of files, date and time of modification, author and many other information

<img src="/images/fig_2.5.png">

----
### `cat` command

Concatenate files and print on the standard output
```bash
cat [OPTION]....[FILE]....
```

`cat` command is basically used to read the file contents in the terminal.

<img src="/images/fig_2.6.png">

If you give a name of non existing file the cat command will throw an error.

<img src="/images/fig_2.7.png">

We can even write and create files using cat command using '>'(output redirection operator) like the following example

```bash
cat > file1
```

By doing so you can enter what every you want to write in the file through the terminal.

Once you are done writing you can exit by presing ctrl+d.

<img src="/images/fig_2.8.png">

**-n Option**

-n option is used when you want to number all output lines.

<img src="/images/fig_2.9.png">

----
### `cp` command
----
### `rm` command
----
### `mv` command
----
### `more` command
----
### `wc` command
----
### `gzip` command
----
### `gunzip` command