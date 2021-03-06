# Lecture: 1
## Topic: Basic Commands
## Date: 30 Jul 2021

### `cal` Command
`cal` command is used to print the calander of the current month.

<img src="/images/fig_1.1.png">

**1. -y option**

`cal -y` using cal command with -y option you can print the calander of the current year.

<img src="/images/fig_1.2.png">

**2. Print full year calander of a given _year_**

Say we want to print the calander of 2002. To do so we will use the following command

General Commnad: `cal <year>` here year is the number of year you want the calander to be.

<img src="/images/fig_1.3.png">

**3. Print a particular _month_ of a given _year_**
Lets say I want to print the calander of september of 2020.

We will you the following command:`cal <month> <year>`

Here `<month>` can be either the number of month or the name of the month. 

<img src="/images/fig_1.4.png">

### `date` command

```bash
date
```
will display current date and time. 

<img src="/images/fig_1.5.png">

**1. +%m option**

+%m is used to display current month.

_**NOTE:** +%m will give the number of the month_

```bash
date +%m
```
<img src="/images/fig_1.6.png">

**2. +%h option**

+%h is used to display current month in words

_**NOTE:** +%h will give the name of the month_

```bash
date +%h
```
<img src="/images/fig_1.7.png">

_+%m will give number of current month and +%h will give name of current month_

**3. +%d option**

+%d is used to display current date.

```bash
date +%d
```
<img src="/images/fig_1.8.png">

**4. +%y option**

+%y is used to display current year.

**NOTE:** +%y will only print the last 2 digits of the year.

```bash
date +%y
```
<img src="/images/fig_1.9.png">

**5. +%H option**

+%H is used to display current hour.

```bash
date +%H
```

**6. +%M option**

+%M is used to display current minute.

```bash
date +%M
```

**7. +%S option**

+%S is used to display current second.

```bash
date +%S
```

<img src="/images/fig_1.10.png">

**7. +%D option**

+%D is used to display current date in MM/DD/YY formate.

```bash
date +%D
```

<img src="/images/fig_1.11.png">

**7. +%T option**

+%T is used to display current time in HH:MM:SS formate.

```bash
date +%T
```

<img src="/images/fig_1.12.png">

### `bc` command: Calculator
It is the calculator command in shell. Here we can excevute mathematical equations. As done in the example:

<img src="/images/fig_1.13.png">

We can even execute multiple expressions by seperating them wit ';' and the shell with give output of each expression in newline.

<img src="/images/fig_1.14.png">

To return back to terminal you can either type `quit` or press ctrl+d.
### `passwd` command

**passwd** command used to change the user login password for the system.

<img src="/images/fig_1.15.png">

### `who` command

**who** command displays all the users logged in to the system.

<img src="/images/fig_1.16.png">

### `pwd` command

**pwd** command is used to see the path of current working directory. 

<img src="/images/fig_1.17.png">

### `mkdir` command
mkdir = make + directory.

mkdir command is used to make new directory.

<img src="/images/fig_1.18.png">

You can make more than one directories at a time also.

<img src="/images/fig_1.19.png">

### `cd` command
cd = change + directory

cd command is used to move forward and backward in the file directory.

```bash
cd path_where_you_want_to_go
```

we can go to the parent directory with the command.
```bash
cd ..
```

<img src="/images/fig_1.20.png">

### `rmdir` command: Calculator
rmdir = remove + directory.

rmdir command is used remove empty directory.

<img src="/images/fig_1.21.png">

We are not able to delete test because it was not an empty directory. But once we deleted test1 we were able to delete test.