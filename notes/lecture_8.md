# Lecture- 8
## Topic- Array and Functions in Shell Scripting
## Date- 03-09-2021

### Arrays

Arrays can be declared as following:
```bash
arr = (0 2 6 9 3 8)
```
If you just want to declare the array then:
```bash
declare -A n[3]
n[0]=54
n[1]=32
n[2]=76
```
You can also pass string but put them in single qouts (').

**Printing Array**
```bash
echo ${n[2]}
```

**Display entire array**
```bash
echo ${n[@]}
```

**Display number of elemnts in the array**
```bash
echo ${#n[@]}
```