# Lecture: 1
## Topic: Basic Commands
## Date: 5 Aug 2021

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
### `passwd` command: Calculator
### `who` command: Calculator
### `pwd` command: Calculator
### `mkdir` command: Calculator
### `cd` command: Calculator


