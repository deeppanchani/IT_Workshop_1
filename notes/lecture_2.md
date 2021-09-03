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

